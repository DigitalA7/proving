# 02 — AIR, opcodes et lookups

Les composants AIR couvrent les instructions et builtins du CPU Cairo.
Chaque composant produit des contraintes locales sur ses colonnes de témoin.
Les lookups relient des tables réparties : mémoire, plages, opcodes et relations auxiliaires.
Les multiplicités garantissent que producteurs et consommateurs s’équilibrent.
Une instruction mal reliée peut satisfaire ses contraintes locales tout en rompant l’état global.
Les interactions constituent donc une surface de soundness critique.
Les fichiers générés ne doivent pas être modifiés directement : leur source canonique est l’outil AIR amont.
Une revue doit suivre composant, relation et générateur de témoin ensemble.

Suite : [Circle STARK et M31](03-circle-stark-m31.md).
