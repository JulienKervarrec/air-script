# Pipeline du compilateur

Le crate parser reconnait modules, sections de trace, evaluations periodiques et contraintes.
Le MIR resout les noms et fournit une representation intermediaire independante de la syntaxe.
La conversion vers AirIR remplace les expressions par un graphe algebrique partageable.
Les passes peuvent alors simplifier ou reutiliser des sous-expressions sans changer la preuve visee.
Le codegen Winterfell produit une structure Rust implementant le trait Air.
Le codegen ACE vise les circuits arithmetiques verifies recursivement dans Miden VM.
Chaque frontiere du pipeline est un point de controle utile pour une revue de securite.

Suite : [03 — Traces et contraintes](03-traces-et-contraintes.md).
