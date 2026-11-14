# Fiche Google Play : Elohîm m'aime ! Le jeu

Tout ce qu'il faut copier-coller dans la Play Console. Les limites de longueur de Google sont indiquées entre parenthèses.

## Identité de l'appli

| Champ | Valeur |
|---|---|
| Identifiant (définitif) | `com.corde3.elohimmaime` |
| Fichier à envoyer | `Elohîm m'aime.aab` (dans le ZIP PWABuilder, dossier Téléchargements) |
| Langue par défaut | Français (France) – fr-FR |
| Appli ou jeu | Jeu |
| Catégorie | Éducatif |
| Gratuite ou payante | Gratuite |
| Contient des annonces | Non |
| Politique de confidentialité | https://elohim-maime-jeu.netlify.app/privacy.html |
| Site web | https://elohim-maime-jeu.netlify.app |

## Fiche du Store

**Nom de l'appli** (30 caractères max) :

```
Elohîm m'aime ! Le jeu
```

**Description courte** (80 caractères max) :

```
30 jeux parlés pour découvrir la Bible en s'amusant, de 3 à 6 ans.
```

**Description complète** (4 000 caractères max) :

```
Elohîm m'aime ! est un jeu d'éveil chrétien pour les enfants de 3 à 6 ans, tiré du livre « Elohîm m'aime ! Mon livre d'éveil chrétien ».

Toutes les consignes sont lues à voix haute : même les enfants qui ne savent pas encore lire peuvent jouer.

10 AVENTURES, 30 JEUX
• Les 7 jours : range les jours de la création, retrouve ce qu'Elohîm a créé chaque jour.
• L'arche de Noé : fais monter les animaux deux par deux, joue au mémo des animaux, raconte l'histoire dans l'ordre.
• L'arc-en-ciel : colorie l'arc-en-ciel de la promesse, « rouge comme la pomme », chasse aux couleurs.
• Je compte : compte les animaux, touche les nombres de 1 à 10, trouve où il y en a le plus.
• Les formes : le cercle, le triangle, l'étoile de Bethléem, le cœur…
• L'ABC de la Bible : la première lettre des mots, les lettres à l'oreille, les premières syllabes (ma, pa, Jé-sus).
• La brebis perdue : aide le bon berger à retrouver sa brebis.
• Qui ? Quoi ? Où ? : Noé, David, Daniel, Jonas, la naissance de Jésus.
• Je fais plaisir à Elohîm : dire merci, partager, pardonner, dire la vérité.
• Les versets : tape dans tes mains sur chaque mot, retrouve le mot qui manque.

AUSSI DANS LE JEU
• Les petites prières du matin, du repas et du soir, lues à voix haute.
• 30 étoiles à gagner et un diplôme à la fin.
• Une voix douce au choix, avec les voix installées sur l'appareil.

POUR LES PARENTS
• Aucune publicité, aucun achat intégré, aucun compte à créer.
• Aucune donnée personnelle collectée : les étoiles restent sur l'appareil.
• Fonctionne sans internet après la première ouverture.
• 10 minutes par jour suffisent. Jouez ensemble !

Versets : Bible de Yéhoshoua ha Mashiah (BYM).
```

## Éléments graphiques

| Élément | Fichier | Taille exigée |
|---|---|---|
| Icône de l'appli | `icons/icon-512.png` | 512 × 512 |
| Image de présentation | `icons/feature-graphic-1024x500.png` | 1024 × 500 |
| Captures téléphone (2 à 8) | `store/screenshots/01.png` à `06.png` | 1080 × 1920 |

Ordre conseillé des captures : 01 (accueil), 03 (arche de Noé), 04 (arc-en-ciel), 05 (compter), 06 (formes), 02 (choix des jeux).

## Contenu de l'appli (questionnaires)

**Accès à l'appli** : toutes les fonctionnalités sont disponibles sans restriction (pas de connexion).

**Annonces** : non, l'appli ne contient pas d'annonces.

**Public cible et contenu**
- Tranches d'âge : **5 ans et moins** et **6 à 8 ans**.
- L'appli peut-elle attirer involontairement les enfants : sans objet (elle est faite pour eux).
- Accepter de respecter les règles du programme **Familles** de Google Play.

**Classification du contenu (questionnaire IARC)**
- Catégorie : Jeu.
- Violence : non. L'histoire de David et Goliath est racontée sans image violente (« le géant tombe »).
- Peur : non. Sexualité, langage grossier, drogues, alcool, tabac, jeux d'argent : non.
- Interaction entre utilisateurs, partage de position, achats numériques : non.
- Résultat attendu : tout public (PEGI 3 / Tous).

**Sécurité des données**
- L'appli collecte-t-elle ou partage-t-elle des données utilisateur : **Non**.
- Les données sont-elles chiffrées en transit : **Oui** (HTTPS).
- Possibilité de demander la suppression des données : sans objet (aucune donnée collectée ; les étoiles s'effacent depuis le diplôme ou en vidant les données de l'appli).

**Appli d'actualités** : non. **Appli de santé** : non. **Appli financière** : non. **Programme gouvernemental** : non.

## Coordonnées du développeur

Google affiche publiquement une adresse e-mail de contact. Utilisez une adresse que vous acceptez de rendre publique (par exemple une adresse créée exprès pour l'appli).

## Après le premier envoi

1. Dans la Play Console : **Tester et publier → Configuration → Intégrité de l'appli → Signature d'application**.
2. Copier l'empreinte **SHA-256** de la « clé de signature d'application ».
3. L'ajouter dans `.well-known/assetlinks.json` (à côté de l'empreinte actuelle), puis envoyer sur GitHub. Sans cela, l'appli installée depuis le Play Store affichera une barre d'adresse.

## Test fermé (comptes personnels récents)

Google demande un **test fermé avec au moins 12 testeurs pendant 14 jours** avant de pouvoir publier pour tout le monde. Ajoutez les adresses Gmail de 12 personnes (famille, église…) dans « Test fermé », envoyez-leur le lien, et demandez-leur de garder l'appli installée 14 jours.
