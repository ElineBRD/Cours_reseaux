# Adressage IPv4

## Classe A :

Une adresse IP de classe A dispose **d'un seul** octet pour identifier le **réseau** et de ***trois octets** pour identifier les **machines** sur ce réseau. 

La notation CIDR des adresses de classe A &rarr; **/8**
- **Plage** : 0 . 0 . 0 . 0 &rarr; 127 . 255 . 255 . 255  
- **Masque de sous-réseau** : 255 . 0 . 0 . 0
- **Réservée** : 127 . 0 . 0 . 0 (boucle locale)
- **Privée** : 10 . 0 . 0 . 0

## Classe B :

Une adresse IP de classe B dispose de **deux octets** pour identifier le **réseau** et de **deux octets** pour identifier les **machines** sur ce réseau.

La notation CIDR des adresses de classe B &rarr; **/16**

- **Plage** : 128 . 0 . 0 . 0 &rarr; 191 . 255 . 255 . 255  
- **Masque de sous-réseau** : 255 . 255 . 0 . 0  
- **Réservées** : 172 . 16 . 0 . 0 &rarr; 172 . 31 . 0 . 0  

## Classe C :

Une adresse IP de classe C dispose **de trois** octets pour identifier le **réseau** et de **un ocet** pour identifier les **machines** sur ce réseau. 

La notation CIDR des adresses de classe C : **/24**

- **Plage** : 192 . 0 . 0 . 0 &rarr; 223 . 255 . 255 . 255 
- **Masque de sous-réseau** : 255 . 255 . 255 . 0 
- **Réservées** : 192 . 168 . 0 . 0 &rarr; 192 . 168 . 255

## Classe D

Les adresses de classe D sont des adresses réservées pour le **multicast**. 
- **Plage** : *non défini*

## Classe E

Les adresses de classe E sont des adresses réservées à [l'IANA](https://www.iana.org/about/presentations/davies-atlarge-iana101-paper-080929-fr.pdf) à des fins d'expériences/tests informatiques.

- **Plage** : *non défini*



---
### Petites définitions :
- **Multicast** : c'est une diffusion provenant **d'un seul émetteur** à destination de **plusieurs récepteurs** simultanément.  
&rarr; Par exemple : Twitch est une palteforme de multicast.