# 03 — Circle STARK et corps M31

Le système s’appuie sur le nombre premier de Mersenne `2^31 - 1`.
Cette taille permet des opérations rapides avec des mots machine et une vectorisation efficace.
Les Circle STARK utilisent le groupe du cercle pour retrouver une structure adaptée aux FFT.
Le domaine, l’ordre des points et les extensions de corps doivent rester cohérents.
Le faible degré est contrôlé par le protocole PCS/FRI du cœur Stwo.
Les paramètres fixent compromis entre temps, taille de preuve et solidité conjecturée.
Le dépôt cible 96 bits avec sa configuration par défaut documentée.
Changer ces valeurs exige une justification cryptographique, pas un simple benchmark.

Suite : [récursion et sérialisation](04-recursion-serialization.md).
