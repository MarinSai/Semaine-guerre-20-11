# Semaine-guerre-20-11

Graphique pour Le Grand Continent : actions hostiles contre l'Europe recensées par l'Observatoire de la guerre politique en Europe, par période de sept jours (du samedi au vendredi, date d'entrée dans la base), du 19 septembre au 20 novembre 2026. La période du 14 au 20 novembre est mise en avant ; chaque hexagone ouvre la fiche de l'action.

Fichiers uniques `index.html` (FR), `es.html`, `it.html`, prévus pour une intégration en iframe (hauteur automatique via iframe-resizer v5). Sources dans `sources/` (Svelte 4 + Vite + vite-plugin-singlefile) : `preparer.py` lit les données publiées de l'Observatoire (dépôt obs_russie), `VITE_LANGUE=fr|es|it npx vite build`.
