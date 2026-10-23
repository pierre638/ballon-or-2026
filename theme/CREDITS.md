# Crédits du thème « Ballon d'Or 2026 » (ballon-or-2027 v2.6.0)

Fichier généré par `scripts/check-theme.mjs` le 2026-10-23 à partir de `credits[]` dans `theme.json`. Ne pas l'éditer à la main.

| Asset | Auteur | Licence | Source |
|---|---|---|---|
| fonts/display.woff2 | Milena Brandão (Fredoka) | OFL-1.1 | <https://fonts.google.com/specimen/Fredoka> |
| fonts/title.woff2 (Bangers) | Vernon Adams (Bangers) | OFL-1.1 | <https://fonts.google.com/specimen/Bangers> |
| items/tier-1.png a tier-10.png (figurines joueurs) | Le Bonbon, à partir du pack de dix bustes « anime sombre » (ballon-or-2027-anime-attributs-v2) fourni par Pierre le 2026-10-19 | brand-proprietary | v7 formes du pack anime-attributs-v2 (2026-10-19) : dix bustes découpés, un attribut par joueur (mégaphone, cartable, échiquier, trophée, uniforme, micro, chemise de vacances, carnet), générés par Imagegen d'après le brief de Pierre, sans médaillon ni fond. Recalés par script sur le cercle physique (masters docs/propositions/joueurs/figures-v2/, 1024, cercle du corps r 440 centré) : taille et position cherchées pour remplir le cercle, bas des épaules arrondi par l'arc du cercle, tête et accessoires libres jusqu'à +10 % du rayon, contour encre de largeur constante à l'écran, puis recadrage au carré central de 968 et réduction à ceil(4 × rayon × 1,1) (layout.itemArtScale 1.1). Le pack ne contient pas de trophée : le palier 11 reste le ballon doré. Mêmes réserves que les versions précédentes (droit à l'image des joueurs, marque Ballon d'Or, attribut « Mobutu » choisi par Pierre). |
| items/tier-11.png (figurine trophée) | Le Bonbon, redessiné à partir du trophée SVG de Le Bonbon (2026-10-16) | brand-proprietary | figurine de la même série : ballon doré sans socle, redessiné le 2026-10-18 à partir du trophée SVG de Le Bonbon (2026-10-16) sans médaillon ni fond, contour encre, étalonnage kit v2, même recadrage et même échelle que les joueurs ; évoque le trophée Ballon d'Or (marque France Football / Groupe Amaury), usage non officiel à autoriser avant diffusion |
| hero.png | Le Bonbon, à partir du pack de dix bustes « anime sombre » (ballon-or-2027-anime-attributs-v2) fourni par Pierre le 2026-10-19 | brand-proprietary | visuel titre 1024 × 1024 transparent : bustes Yamal, Kane et Mbappé du pack anime-attributs-v2 derrière la figurine ballon doré, ombres portées douces, 2026-10-19 ; mêmes réserves (droit à l'image, marque Ballon d'Or) |
| logo.svg | Le Bonbon | CC0-1.0 | emblème ballon doré sur badge sombre avec arc de laurier, SVG sans texte, 2026-10-16 |
| bg.svg | Le Bonbon | CC0-1.0 | stade nocturne vu de la tribune (ciel, mâts de projecteurs, gradins de points de foule, brume, pelouse à bandes de tonte, lignes blanches, confettis dorés) généré en SVG (seed 2027) et rasterisé avec sharp, 2026-10-16 ; source vectorielle v4, non utilisée en jeu quand bg.png existe |
| bg.png (réétalonné v5) | Le Bonbon | CC0-1.0 | rendu de bg.svg réétalonné le 2026-10-17 vers l’éclairage des médaillons (scratchpad v5-content/regrade-v5.mjs avec sharp) : ciel et tribunes navy, pelouse émeraude profonde, lumière chaude en haut, faisceaux des mâts, vignette navy, lignes et confettis dorés conservés, grain ordonné ±3 contre les bandes, PNG palette 1080 × 2400 ; aucun texte |
| sfx/* | Le Bonbon | CC0-1.0 | sons synthétisés avec scripts/make-sfx.mjs --preset football (coup de pied, sifflet d’arbitre, corne de stade + foule, rugissement) puis scripts/sfx-convert.sh, 2026-10-17 |
| prize/banner.png, prize/card.jpg, prize/item-1.png à item-4.png (lot) | Le Bonbon | CC0-1.0 | illustrations du lot (billets de la cérémonie, train générique, hôtel, dîner, skyline) dessinées en SVG avec le kit des médaillons et rasterisées avec sharp (masters docs/propositions/dotation/, 2026-10-17), dérivées pour le thème : bannière 1080 × 420 et vignettes 256 en PNG palette, affiche 1080 × 1350 en JPEG q82 ; aucune marque, aucun logo, aucune livrée ; illustrations non contractuelles |

## Notes

- Police d'affichage : `Fredoka` 600 (`fonts/display.woff2`), texte de licence livré dans `fonts/LICENSE.txt`.
- Police des titres : `Bangers` 400 (`fonts/title.woff2`).
- Placeholders générés : inactifs.
- Les assets `brand-proprietary` restent la propriété de l'annonceur ; référence du contrat ou du mail dans la colonne Source.
