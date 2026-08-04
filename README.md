# BiblioPerso V1.2 — PWA iPhone

Cette version est prête à être publiée sur une adresse HTTPS, puis installée sur l’écran d’accueil d’un iPhone.

## Ce que contient la V0.8
- application installable sur iPhone ;
- fonctionnement hors ligne après la première ouverture ;
- scan ISBN avec caméra lorsque l’application est servie en HTTPS ;
- stockage local sur l’appareil ;
- sauvegarde JSON manuelle et sauvegardes automatiques ;
- recherche, séries, intégrales et inventaire.

## Important
Le ZIP seul ne peut pas activer la caméra sur iPhone. Il faut publier le dossier sur un hébergement HTTPS gratuit.

## Étape suivante
Publier ce dossier sur GitHub Pages ou Cloudflare Pages. Une fois l’adresse obtenue :
1. l’ouvrir dans Safari ;
2. toucher Partager ;
3. choisir « Sur l’écran d’accueil ».

Les 1 800 ouvrages ne seront pas stockés dans l’hébergement : ils resteront sur l’iPhone ou le PC.


## Nouveautés V0.9
- tableau de bord avec total, séries, ouvrages à acheter et dernier emplacement ;
- accès direct à une étagère par son code (ex. D4) ;
- fiche d’ouvrage plus lisible avec statut et emplacement mis en avant.


## Ajustement V0.9.1
- tableau de bord masqué au démarrage ;
- bouton d’affichage placé entre « Ajouter un ouvrage » et « Scanner un ISBN ».


## Nouveautés V0.10
- structure Univers → Cycle → Tome ;
- cycles facultatifs ;
- regroupement visuel par cycle ;
- anciennes données « Série » reprises automatiquement comme univers ;
- suggestions automatiques pour les univers et cycles déjà connus.


## Nouveautés V0.11
- nombre de tomes parus par cycle ;
- détection automatique des tomes manquants ;
- prochain tome annoncé et date prévue ;
- page « Ce qui me manque » ;
- intégrales et recueils pris en compte dans la détection.


## Nouveautés V0.12
- page « Sorties à venir » ;
- tri automatique par date ;
- indication « disponible » lorsque la date est passée ;
- ajout direct d’un prochain tome à la liste « À acheter » ;
- détection d’un tome déjà possédé ou déjà présent dans la liste d’achats.


## Nouveautés V1.0
- recherche filtrée par catégorie, statut, type, lecture, favori et emplacement ;
- contrôle de cohérence ;
- détection des ISBN invalides ;
- détection des ISBN en double ;
- signalement des emplacements manquants et doublons possibles ;
- version considérée comme prête pour l’inventaire réel.


## Nouveautés V1.1
- mode inventaire amélioré ;
- emplacement automatiquement repris ;
- conservation facultative de l’auteur, univers, cycle, éditeur, collection et type ;
- compteur de séance ;
- changement rapide d’emplacement ;
- proposition de sauvegarde à la fin d’une séance ;
- page « Emplacements » ;
- favoris sur trois niveaux.


## Correctif V1.1.1
- rétablit les écrans manquants ;
- corrige les boutons Ajouter, Scanner et Inventaire ;
- répare le champ de favori à trois niveaux.


## Nouveautés V1.1.2
- remplacement de BarcodeDetector par ZXing Browser ;
- scan EAN/ISBN compatible Safari sur iPhone ;
- caméra arrière avec résolution élevée ;
- cadre de visée ;
- arrêt automatique après reconnaissance ;
- vibration après détection ;
- détection des doublons ;
- saisie manuelle toujours disponible.

## Premier essai sur iPhone
Après la mise à jour GitHub, ouvre d’abord l’adresse dans Safari et recharge la page. Ferme ensuite l’application de l’écran d’accueil et rouvre-la. Au premier scan, accepte l’accès à la caméra.


## Correctif V1.1.3
- version UMD vérifiée de ZXing Browser ;
- initialisation corrigée du lecteur ;
- contraintes caméra simplifiées pour Safari/iPhone SE ;
- bouton « Tester uniquement la caméra » ;
- message d’erreur technique détaillé en cas d’échec.

## Test conseillé
1. Mettre à jour GitHub.
2. Ouvrir le site dans Safari et recharger.
3. Ouvrir Scanner un ISBN.
4. Appuyer d’abord sur « Tester uniquement la caméra ».
5. Si l’image apparaît, arrêter puis tester « Ouvrir la caméra ».


## Nouveautés V1.2
- scan ISBN puis récupération automatique des informations bibliographiques ;
- titre, auteur, éditeur, année, nombre de pages et langue ;
- aucune couverture stockée ni affichée ;
- suggestion automatique d’univers, cycle et tome à partir des données existantes ;
- détection renforcée des doublons par ISBN et par ouvrage proche ;
- confirmation avant enregistrement d’un doublon volontaire.
