# TP7 — Astro, Leaflet et GeoJSON

- Nom : Tebrouri
- Prénom : Leila
- Groupe : MMI2 B1
- URL du site Netlify : à compléter après la publication

## Pages réalisées

- `/leaflet` : carte interactive des principaux établissements français
  d'enseignement supérieur avec Leaflet, filtre par région et tableau accessible.
- `/geojson/serveur` : carte de population générée côté serveur avec
  Observable Plot.
- `/geojson/client` : carte générée côté client et actualisée avec trois
  sélecteurs (année, sexe et âge), un bouton de réinitialisation, un résumé et
  un tableau accessible synchronisé.

## Données

- Ministère de l'Enseignement supérieur : principaux établissements
  d'enseignement supérieur.
- Insee : estimations de population au 1er janvier par département, sexe et
  grande classe d'âge (2015, 2020 et 2025).
- France GeoJSON : contours simplifiés des départements métropolitains.

Les fichiers ont été filtrés pour ne conserver que les champs utiles au TP.

## Accessibilité

- langue du document et titres de pages renseignés ;
- lien d'évitement et navigation structurée ;
- libellés associés aux trois champs de sélection ;
- région Leaflet nommée pour les technologies d'assistance ;
- titres, sous-titres, légendes, descriptions et `ariaLabel` sur les cartes Plot ;
- zone `aria-live` annonçant l'actualisation de la carte interactive ;
- alternative tabulaire aux représentations cartographiques ;
- contrastes et focus clavier visibles, avec respect de la préférence de
  réduction des animations.

### Vérification dans Chrome

1. Ouvrir les DevTools puis le panneau **Lighthouse**.
2. Sélectionner **Accessibilité** et lancer l'analyse pour chaque page.
3. Dans le panneau **Éléments**, ouvrir l'arborescence d'accessibilité et
   contrôler les titres, les champs de formulaire, les boutons et les tableaux.
