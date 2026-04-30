# Exercice 6: Tester les Champs static en Java

## Description
Ce projet illustre la différence entre un compteur **static**
et un compteur **non-static** en Java.

## Classes
- `Personne` : contient deux compteurs (static et non-static)
- `Main` : crée plusieurs instances et affiche les valeurs

## Résultat attendu
(1,4)
- nbLocal = 1 (réinitialisé à chaque nouvel objet)
- nbInstances = 4 (partagé entre tous les objets)

## Comment exécuter
1. Compiler : javac Main.java Personne.java
2. Exécuter : java Main