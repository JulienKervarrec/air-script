# Limites et verification

AirScript facilite l expression des AIR mais ne garantit pas qu un modele capture toute la specification.
Les risques majeurs restent les contraintes manquantes, indices hors domaine et hypotheses implicites.
Le projet est annonce alpha et non audite : aucune utilisation de production ne doit etre deduite de ce guide.
Le repertoire docs/examples fournit des cas lisibles relies a la documentation mdBook.
La suite docs_sync transpile ces exemples pour detecter les divergences entre documentation et compilateur.
Ce parcours repose uniquement sur la lecture du README, des crates parser, MIR, AIR et codegen.
Aucune installation, compilation ou execution nouvelle n a ete effectuee.
Pour verifier, consulter les tests du depot et reproduire les commandes de sa documentation dans un environnement isole.
