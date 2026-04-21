# Market Brief — Newsletter LinkedIn de Robin Dubosq

Page web premium hébergée sur GitHub Pages, version HTML responsive de la newsletter mensuelle Market Brief consacrée à l'analyse du marché cadres et des décisions RH.

## Édition en ligne

**N°01 — Avril 2026 — La reprise qui ne répare rien.**
+4 % de recrutements cadres en 2026, −12 % d'accès pour les débutants.

## Contenu du dépôt

| Fichier | Rôle |
|---|---|
| `index.html` | Page web responsive, point d'entrée du site |
| `Market-Brief-N01.pdf` | Version PDF téléchargeable de l'édition |
| `og-image.png` | Image de prévisualisation (1200×630) pour LinkedIn et autres réseaux |
| `profile.jpg` | Photo de l'auteur, embarquée dans la page et l'image OG |

## Mise en ligne sur GitHub Pages — 5 étapes

1. **Créer un dépôt public** sur GitHub, nom suggéré : `market-brief` (ou `marketbrief`).
2. **Uploader les fichiers** : glisser-déposer `index.html`, `Market-Brief-N01.pdf`, `og-image.png` et `profile.jpg` à la racine du dépôt.
3. **Activer GitHub Pages** : aller dans **Settings → Pages**, choisir **Source: Deploy from a branch**, sélectionner la branche `main` et le dossier `/ (root)`, puis **Save**.
4. **Attendre 1 à 2 minutes** que GitHub Pages publie. L'URL sera de la forme :
   ```
   https://VOTRE-USERNAME.github.io/market-brief/
   ```
5. **Tester** : ouvrir l'URL pour vérifier que la page s'affiche bien et que le PDF se télécharge.

## Connecter à LinkedIn

### Section Sélection (Featured) du profil
1. Profil LinkedIn → **Ajouter à la sélection** → **Lien**.
2. Coller l'URL GitHub Pages.
3. LinkedIn récupère automatiquement le titre, la description et l'image OG. Le rendu est piloté par les balises `<meta property="og:*">` du fichier `index.html`.

### Champ Site web du profil
1. Profil LinkedIn → **Modifier l'intro** → **Coordonnées** → **Site web**.
2. Type : **Personnel** (ou **Portfolio**), URL : l'URL GitHub Pages.

## Mise à jour pour les éditions suivantes

À chaque nouvelle édition mensuelle :
1. Renommer le dossier ou créer un sous-dossier `n02/`, `n03/` etc. pour archiver les anciennes éditions sans casser les liens.
2. Régénérer `index.html` et `og-image.png` avec le nouveau contenu.
3. Régénérer le PDF et le déposer comme `Market-Brief-N02.pdf`.
4. Push sur `main`. GitHub Pages redéploie automatiquement en 1-2 minutes.

## Nom de domaine personnalisé (optionnel)

Si vous achetez un domaine type `marketbrief.fr` ou `robindubosq.com`, GitHub Pages permet de le brancher gratuitement :
1. **Settings → Pages → Custom domain** : indiquer le domaine.
2. Chez votre registrar, ajouter un enregistrement CNAME pointant vers `VOTRE-USERNAME.github.io`.
3. Cocher **Enforce HTTPS** une fois le domaine vérifié.

## Vérification du preview LinkedIn

Avant de partager le lien sur LinkedIn, tester le rendu du preview avec l'outil officiel :
**LinkedIn Post Inspector** : https://www.linkedin.com/post-inspector/

Coller l'URL GitHub Pages, vérifier que le titre, la description et l'image OG s'affichent correctement. Si LinkedIn a mis en cache une ancienne version, l'inspector force un rafraîchissement.

---

*Conçu et rédigé par Robin Dubosq, avril 2026.*
