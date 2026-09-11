# 01 — Du programme Cairo à la preuve

Le dépôt transforme une exécution Cairo en preuve Circle STARK.
L’adaptateur convertit la trace de `cairo-vm` en entrées organisées par opcode et builtin.
Le témoin contient les colonnes nécessaires aux composants de l’AIR.
Les contraintes établissent que ces colonnes décrivent une exécution Cairo valide.
Le prouveur engage ensuite les traces et applique le protocole FRI.
Le vérificateur Rust contrôle la preuve sans rejouer le programme complet.
Un second vérificateur écrit en Cairo rend la récursion possible.
Cette séparation matérialise les frontières exécution, preuve et vérification.

Suite : [AIR et lookups](02-air-lookups.md).
