# docs-offres-tech

Documentation publique d'offres.tech, rendue par Mintlify depuis ce dépôt. Chaque push sur `main` redéploie le site.

## Règles

- **Source de vérité** : les sections produit du README du dépôt `nosh6/jobs-editeurs-fr`. Cette doc les réécrit pour un lecteur externe, elle n'invente rien.
- **Rien d'interne** : aucun contenu de `docs/` du dépôt principal (backlog, monétisation, revues, VPS, mesures) ne passe ici. Dans le doute, on n'écrit pas.
- **Vocabulaire** : dire « entreprise », pas « éditeur », sauf pour le filtre « non-éditeurs », le Top 25 et l'éditeur du site.
- **Entretien** : une section produit du README qui change entraîne la page correspondante ici, dans la même session de travail.
- **Format** : MDX, front matter `title` + `description` obligatoires, pages listées dans `docs.json` sinon elles n'apparaissent pas.
- Aperçu local : `npx mint dev` à la racine.
