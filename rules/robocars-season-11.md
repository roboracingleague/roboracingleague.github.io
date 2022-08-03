Règlement DIY Robocars France Saison 11
=======================================

## Objectifs de la Saison 11
* Exploiter l'accélération et le freinage des voitures pour améliorer les temps
* Implémenter l'évitement de voitures obstacles statiques sur la piste

## Calendrier des 6 journées de courses
* 10 septembre 2022 au Cristallin (lieu peut changer)
*  8 octobre   2022 au Cristallin (lieu peut changer)
*  5 novembre  2022 au Cristallin (lieu peut changer)
*  3 décembre  2022 au Cristallin (lieu peut changer)
*  7 janvier   2022 au Cristallin (lieu peut changer)
* 28 janvier   2022 au Cristallin (lieu peut changer)

## Robocar
* Echelle entre 1/18 et 1/10 (1/10 recommandé)
* Les voitures doivent fonctionner en autonomie totale lors des épreuves
* Tous les types de caméras sont autorisées, mono, stéréo...
* Les capteurs de vitesse sont recommandés
* Les IMUs sont recommandés
* Un émetteur spécifique pour le système de chronométrage sera peut-être obligatoire
* Les LIDARs sont autorisés mais non recommandés (Meetup basé sur la vision) et placent automatiquement la voiture dans une catégorie spécifique LIDAR
* Les carrosseries ne sont pas obligatoires mais permettent d'obtenir des point de championnat bonus

## Courses
* **Urban Sprint** CW+CCW – with obstacles (CW = ClockWise / CCW = Counter ClockWise)

  - Chaque voiture a 2 essais pour établir le meilleur temps possible en empruntant la piste dans le sens horaire sur 2 tours.  
  Puis à nouveau  2 essais pour établir le meilleur temps possible en empruntant la piste dans le sens anti-horaire sur 2 tours

  - Le temps comptabilisé sera la somme des meilleurs temps dans chaque sens.  
  Le chronométrage sera manuel ou automatique suivant le matériel disponible
  
  - Le départ pour chaque essai sera donné par l'organisation
  
  - Il y aura 4 voitures obstacles statiques positionnées dans les lignes droites soit à gauche soit à droite de la piste pour permettre l'évitement.  
  Toucher l'arrière d'une voiture obstacle statique invalide le chronométrage en cours et l'essai est perdu

  - En cas d'une incapacité d'une voiture à établir un chronométrage validé, le nombre de virages franchis sera retenu pour le classement

  - Les points de championnat associés au classement de la course ne seront attribués que si le challenge est complété (2 tours complets dans chaque sens sans toucher de voiture obstacle)


* **Urban Battle** CW or CCW – with obstacles (CW = ClockWise / CCW = Counter ClockWise)

  - Un tableau de 1/16 ou 1/8 de finale permettra de positionner les participants en fonction du classement du ***Urban Sprint***.  
  Le premier du classement du Urban Sprint affrontera le dernier.  
  Le 2e affrontera l'avant-dernier.  
  Le premier du classement du Urban Sprint affrontera le dernier.   
  etc.

  - Chaque affrontement sera remporté par celui des 2 adversaires qui remporte 2 des 3 manches
  
  - Chaque manche verra les 2 opposants se positionner aux opposés de la piste pour le départ (La position sera alternée à chaque manche)
  
  - Le départ sera donné par l'organisation

  - La première voiture à compléter 2 tours remportera la manche.  
  Si une voiture rattrape l'autre en s'approchant à moins de 30cm de son pare-choc arrière elle remporte la manche

  - Il y aura 4 voitures obstacles statiques positionnées dans les lignes droites soit à gauche soit à droite de la piste pour permettre l'évitement.   
  Toucher l'arrière d'une voiture obstacle statique est éliminatoire pour la manche

* **Pure Speed** CW+CCW – without obstacles  (CW = ClockWise / CCW = Counter ClockWise)

  - La piste sera modifiée pour maximiser la vitesse en ligne droite et un assortiment de quelques virages lents et rapides

  - Chaque voiture a 2 essais pour établir le meilleur temps possible en empruntant la piste dans le sens horaire sur 2 tours  
  Puis à nouveau  2 essais pour établir le meilleur temps possible en empruntant la piste dans le sens anti-horaire sur 2 tours

  - Le temps comptabilisé sera la somme des meilleurs temps dans chaque sens

  - Le chronométrage sera manuel ou automatique suivant le matériel disponible

  - Le départ pour chaque essai sera donné par l'organisation

* Entre 2 et 5 robocars, soumises aux mêmes règles que tous, seront engagées par l'organisation à chaque course pour pimenter les courses 

## Piste

* Il y aura 2 pistes, la urban track et la speed track. Les tracés seront communiqués sous peu.  
**Urban track 16 virages**
![alt text](https://roboracingleague.github.io/images/urban-track-16-virages.png "Urban track 16 virages")


**Speed track**
![alt text](https://roboracingleague.github.io/images/speed-track.png "Speed track")

* La piste est délimitée par du ruban de masquage beige d'un largeur de 5cm.  
La piste à une largeur uniforme de 1m incluant les rubans de 5 cm de chaque côté de la piste.   
Le rayon de courbure au milieu de la piste dans les virage est de 1m.  
Il n'y a pas de murets délimitant la piste.  
Les LIDARs ne peuvent donc pas être utilisés pour détecter la piste.  
Les LIDARs peuvent cependant faciliter la détections des autres robocars

* Court-circuiter un virage en passant à l'intérieur d'un cône ou en touchant se dernier annule l'essai ou la manche en cours pour le fautif

* L'intérieur des virages comportera des ralentisseurs depuis la ligne de délimitation intérieure jusqu'au cône

* Un système de chronométrage sera installé et deviendra obligatoire(avec période de probation) dès que validé

* Un système de panneaux à chaque sortie de virage en bordure de circuit indiquera la distance au prochain virage et le type de virage si cette distance supérieure à 1m.  
Un panneau à 1m de l'entrée du virage sera également disposé pour le freinage. 

Si nous prenons comme exemple la grande ligne droite de la urban track dans le sens horaire, il y aura 2 panneaux.  
Le premier à la sortie du virage au début de la ligne droite et un second au bout de la ligne droite avant le virage.  
Les informations sur le panneau se répartiront en 3 lignes
  - première ligne est la distance au virage en mètres
  - deuxième ligne est l'angle du virage en degrés
  - troisième ligne indique le sens du virage L pour gauche et R pour droite  
la police utilisée est de l'Arial 170 couleur noire  
le fond sera une fiche bristol couleur jaune pâle

**Panneau virage à 17m qui tourne à 90 degrés à droite**
<p align="center">
  <img src="https://roboracingleague.github.io/images/Panneau-virage-17m-90deg-R.png" alt="Panneau virage 17m 90deg R" height="500">
</p>

**Panneau virage à 1m qui tourne à 90 degrés à droite**
<p align="center">
  <img src="https://roboracingleague.github.io/images/Panneau-virage-1m-90deg-R.png" alt="Panneau virage 1m 90deg R" height="500">
</p>

## Résultats des courses, points de championnat et classement

* Les point de championnat sont attribués à l'issue de chaque course du 1er au 10e suivant la répartition suivante:    
25 - 18 - 15 - 12 - 10 - 8 - 6 - 4 - 2 - 1
* Les points de championnat associés au classement de la course ne seront attribués que si l'épreuve est complétée  
* Les points de championnat gagnés lors de chaque course ne seront réellement comptabilisés que si au moins 3 voitures réussissent l'épreuve
* Les points de championnat seront accummulés sur l'ensemble des course, la voiture ayant accummulé le plus de points sera déclarée gagnante du championnat open
* Les participants recevront des points de participation pour chaque départ effectué lors des épreuves (si la voiture ne démarre pas la présence ne sera pas comptabilisée).  
12 points de présence seront donc attribués lors de chaque course aux participants
* La présence d'une carrosserie sera également récompensée.  
12 points de championnat par course effectuée avec une carrosserie
* Les 6 journée de course devraient permettre d'organiser 18 courses, les 15 meilleures courses de chaque voiture seront comptabilisés
* Les classement Vision et LIDAR permettront de comparer des voitures aux capacités comparables

## Journée de course type
Arrivée racers 9h - 9h30 au plus tard
* Courses
  - Installation piste 9h-10h 
  - 10h00 - 11h30 essais libres
  - 11h30 - 12h30 Sprint CW+CCW (w obstacles)
  - 12h30 - 13h30 Battle CW or CCW alternate (w obstacles)
  - 13H30 - 13h45 Preparation SPEED TRACK
  - 13h45 - 14h45 Speed CW+CCW (wo obstacles)
  - 14h45 - 15h00 Debrief

* Essais libres
  - 15h00 - 16h45 Piste libre
  - 16h45 - 17h00 Rangement et Fermeture
