# Palindrome

Le but de cet exercice est d'écrire un algorithme qui va verifier si un mot, n'importe lequel est un palindrome ou pas.
Pour rappel, un palindrome est un mot qui peut se lire dans les 2 sens. Par exemple : kayak, ressasser, anna.
Pour ce faire, nous créerons une fonction en la nommant Est_Palindrome dont le but est de faire la vérification en question.
Partant du principe qu'une chaine vide et tout mot à 1 seul caractère sera considéré comme un palindrome, l'alternative restante consistera a vérifier successivement chaque lettre à son opposé
dans le mot. Ainsi, la première lettre sera comparée a la dernière, la deuxieme a l'avant derniere et ainsi de suite.
Si l'on arrive a atteindre la lettre du milieu avec toutes les correspondances respectees alors le mot en question est un palindrome,sinon ce n'en est pas un.
