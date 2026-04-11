# CarbuLoc - Changelog

## v0.8.1 (2025-04-11)
- **Amélioration** : Messages de géolocalisation plus explicites (indiquent d'activer le GPS)

## v0.8.0 (2025-04-11)
- **Feature** : Clusters "pizza" — cercles bleus divisés en secteurs (2 à 10) selon le nombre de stations regroupées
- **Feature** : Icône de localisation personnalisée
- **Amélioration** : Recherche unifiée — affichage "Ville, Région" pour Photon et Nominatim
- **Amélioration** : Navigation clavier dans les résultats de recherche (flèches haut/bas)
- **Fix** : Recherche par code postal corrigée (extraction de la ville depuis addresstype=postcode)
- **Suppression** : Message d'instruction initial supprimé

## v0.7.13 (2025-04-02)
- **Amélioration Mobile** : Header réorganisé sur 3 lignes
  - Ligne 1: Logo (plus grand) + Thème + Gouv
  - Ligne 2: Recherche + Rayon
  - Ligne 3: Carburants + Localiser (icône seule) + Refresh + Heure
- **Amélioration Mobile** : Plus de scroll horizontal dans le header

## v0.7.12 (2025-04-02)
- **Amélioration** : Logo "Loc" descendu à -0.35em

## v0.7.11 (2025-04-02)
- **Amélioration** : Logo "Loc" en gris clair (var(--text-muted)) au lieu de blanc
- **Amélioration** : Logo "Loc" descendu de 0.1em (margin-bottom: -0.15em → -0.25em)
- **Amélioration** : Contour du "Loc" utilise var(--surface) au lieu de var(--text-muted)

## v0.7.10 (2025-04-02)
- **Amélioration** : Logo Gouv conserve ses proportions (hauteur 32px = même que les boutons)

## v0.7.9 (2025-04-02)
- **Amélioration** : Logo Gouv déplacé dans le header (à droite de l'heure)
- **Amélioration** : Logos Maps/Waze/Plans agrandis (pleine largeur du panneau)
- **Amélioration** : Suppression des labels texte sous les logos de navigation

## v0.7.8 (2025-04-02)
- **Feature** : Lien vers le site gouvernemental prix-carburants.gouv.fr avec logo

## v0.7.7 (2025-04-02)
- **Amélioration** : Logo Apple Plans intégré

## v0.7.6 (2025-04-02)
- **Feature** : Lien Apple Plans ajouté (sans logo pour l'instant)

## v0.7.5 (2025-04-01)
- **Amélioration** : Logos Maps et Waze (style app smartphone) pour les liens de navigation

## v0.7.4 (2025-04-01)
- **Feature** : Liens Maps et Waze sous les coordonnées GPS dans le panneau détails

## v0.7.3 (2025-04-01)
- **Fix** : Recherche par code postal utilise Nominatim directement (Photon ne gère pas bien les CP)

## v0.7.2 (2025-04-01)
- **Fix** : Panneau de gauche en mode overlay (ne pousse plus la carte)
- **Fix** : Centrage du repère prend en compte le panneau de droite (320px)
- **Fix** : Tri par distance corrigé (currentCenter.lat/.lng au lieu de [0]/[1])

## v0.7.1 (2025-04-01)
- **Amélioration** : Pentagone plus grand (64x64px, rayon 28)
- **Amélioration** : Contour noir plus épais (stroke-width 6)
- **Fix** : Fonction centerMapOnStation() pour centrer entre les panneaux

## v0.7.0 (2025-04-01)
- **Feature** : Panneau de classement à gauche avec tous les résultats
- **Feature** : Mode réduit du classement (ronds seulement, 56px)
- **Feature** : Bouton toggle réduire/agrandir (chevrons)
- **Feature** : Synchronisation bidirectionnelle classement ↔ carte ↔ détails
- **Feature** : Toggle mobile pour switcher classement/détails

## v0.6.7 (2025-03-31)
- **Feature** : Pentagone de sélection animé (rotation + pulse)
- **Amélioration** : Double contour noir + vert avec glow

## v0.6.6 (2025-03-31)
- **Feature** : Distinction nom enseigne vs nom entreprise
- **Amélioration** : toTitleCase() pour harmoniser les noms

## v0.6.3 (2025-03-31)
- **Feature** : Gestion des ruptures de stock
- **Feature** : Markers rouge foncé avec diagonale barrée
- **Feature** : Badges rupture dans le panneau détails

## v0.6.1 (2025-03-31)
- **Feature** : Logos des 48 enseignes
- **Feature** : API 2aaz pour noms de stations
- **Fix** : Correction casse Brand (majuscule)
