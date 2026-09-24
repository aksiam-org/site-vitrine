# Site de l'AKSIAM

Source du site public de l'Association Khoja Shia Ithna Asheri de Madagascar, destiné à `aksiam.mg`.

> **Aperçu de validation.** Les textes soulignés en pointillé orange sont **provisoires**. Les pages
> portent `noindex` : les moteurs de recherche ne les référencent pas tant que le site n'est pas validé.

## Contenu

| Chemin | Page |
|---|---|
| `index.html` | page d'accueil (présentation, domaines d'action, éducation en chiffres, calendrier, sections, Consultation 360°, services, contact) |
| `calendrier/` | calendrier chiite complet, consultable mois par mois |
| `consultation360/` | page de la Consultation 360° |

Tous les liens entre pages sont **relatifs** : le site fonctionne à l'identique en aperçu
(`aksiam-org.github.io/site-vitrine/`) et à la racine d'`aksiam.mg`.

## Le calendrier ne se copie pas

Les pages **lisent en direct** les fichiers du dépôt [`aksiam-org/calendrier`](https://github.com/aksiam-org/calendrier),
ceux auxquels les membres sont abonnés. Une date corrigée là-bas apparaît ici sans rien toucher.
⚠️ Ne jamais changer l'adresse de ces fichiers, ni en publier un nouveau pour l'année suivante :
les téléphones abonnés ne suivraient pas.

## Ce qui bouge, et pourquoi

- **La lune de ce soir**, dans l'arche : calcul astronomique (lunaison moyenne), dessinée telle qu'on la
  voit depuis Madagascar (hémisphère sud : le croissant montant est éclairé à gauche). Elle ne dépend pas
  du calendrier et reste juste s'il ne répond pas.
- **Les animations** ne jouent que si l'appareil n'a pas demandé moins de mouvement ; la classe qui les
  prépare est posée dans l'en-tête, et le contenu reste visible sans le script.

## Crédits

Contour de Madagascar : [Natural Earth](https://www.naturalearthdata.com/), domaine public.

## Règles de rédaction

- Aucun nom, aucune photo, aucun chiffre sur la communauté à ce stade. **Seule exception : la rubrique
  Éducation**, qui affiche deux totaux datés (bourses scolaires, prêt universitaire). Jamais de détail par
  section ni par pays : il désignerait des élèves. À mettre à jour une fois par an, à cet endroit seulement.
- Aucun montant ni critère de décision pour les aides : on explique la démarche, pas le barème.
- Aucun cadratin ni demi-cadratin dans le texte affiché.
- Toute page externe s'ouvre dans un nouvel onglet.

## Avant la mise en production

1. Remplacer les textes provisoires par les textes validés, et retirer le bandeau « Maquette ».
2. Retirer `noindex` des trois pages.
3. Déposer le contenu du dépôt à la racine de l'hébergement d'`aksiam.mg`.
