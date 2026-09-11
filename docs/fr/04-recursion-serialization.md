# 04 — Vérification récursive et sérialisation

Le vérificateur Cairo exécute la logique de contrôle à l’intérieur de la VM Cairo.
Son exécution peut donc être prouvée à son tour pour agréger plusieurs preuves.
La récursion exige une représentation compatible des éléments de corps, engagements et ouvertures.
Les crates de sérialisation convertissent la preuve vers des tableaux de felts Cairo.
Tout écart de packing ou d’ordre transforme une preuve valide en entrée différente.
Les options Blake2s et Poseidon252 correspondent à des canaux et usages distincts.
Poseidon252 vise notamment une meilleure compatibilité avec le règlement Ethereum.
Proveur et vérificateur doivent partager exactement configuration et format.

Suite : [périmètre et limites](05-perimetre-limites.md).
