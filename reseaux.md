# Découpage de réseaux

## Pourquoi découper les réseaux ?

- Pour définir un nombre X de réseaux, on définit un nombre X de **bits réseaux**.
- Un masque ne peut pas aller au-delà d'un /30
### Exemple :

**192.168.0.0 /25**  

- Les bits du **masque de sous-réseau** seront donc :  
 **1111 1111 . 1111 1111 . 1111 1111 . 1**000 0000

 ---

- Donc, les **25** premiers bits des **adresses machines** ne sont **PAS MANIPULABLES** :  
**1100 0000 . 1010 1000 . 0**000 0000 . 0000 0000


Les **bits réseau** (en gras) sont bloqués par le masque de sous-réseau tandis que les **bits machines** sont manipulables.

## Réseau 1 :

En découpant le réseau en deux comme vu ci-dessus, le **réseau 1** compose ses bits de la sorte :

- **1100 0000 . 1010 1000 . 0**000 0000 . 0000 0000 : Adresse réseau
- **1100 0000 . 1010 1000 . 0**000 0000 . 0000 0001 : Première adresse utilisable
- **1100 0000 . 1010 1000 . 0**111 1111 . 1111 1110 : Dernière adresse utilisable
- **1100 0000 . 1010 1000 . 0**111 1111 . 1111 1111 : Adresse broadcast
---
Le **réseau 2** se compose donc :

- **1100 0000 . 1010 1000 . 1**000 0000 . 0000 0000 : Adresse réseau
- **1100 0000 . 1010 1000 . 1**000 0000 . 0000 0001 : Première adresse utilisable
- **1100 0000 . 1010 1000 . 1**111 1111 . 1111 1110 : Dernière adresse utilisable
- **1100 0000 . 1010 1000 . 1**111 1111 . 1111 1111 : Adresse broadcast
---



Avec un **octet** d'une adresse, nous pouvons faire 256 sous-réseaux au total


