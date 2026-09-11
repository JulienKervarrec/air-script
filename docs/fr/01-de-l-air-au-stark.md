# De l AIR au STARK

Un STARK prouve qu une trace respecte des contraintes algebriques sans reveler toutes ses cellules.
AirScript rend ces contraintes explicites dans un langage specialise plutot que dans du Rust generaliste.
Le parseur transforme le texte en AST avant toute interpretation algebrique.
Le MIR normalise ensuite les declarations, les acces de trace et les contraintes.
AirIR porte l AlgebraicGraph exploite par les passes d optimisation et les generateurs.
Cette separation permet d auditer la semantique avant de regarder le code produit.
Le depot avertit toutefois qu il est alpha, non audite et impropre a la production.

Suite : [02 — Pipeline du compilateur](02-pipeline-du-compilateur.md).
