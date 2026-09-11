# Codegen et recursion

Le backend Winterfell traduit AirIR vers l interface attendue par le prouveur Rust.
Le backend ACE convertit les contraintes en circuits adaptes au chiplet Arithmetic Circuit Evaluation.
Cette cible permet a un programme Miden de verifier des calculs algebriques dans une preuve recursive.
La recursion compose plusieurs preuves tout en gardant un objet de verification compact.
Le generateur doit conserver exactement les degres, domaines et conventions du modele source.
Une optimisation correcte syntaxiquement peut etre invalide si elle modifie la semantique des contraintes.
La comparaison entre AirIR et sortie generee constitue donc une etape d audit essentielle.

Suite : [05 — Limites et verification](05-limites-et-verification.md).
