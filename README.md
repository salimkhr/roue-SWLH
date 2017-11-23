# roue-SWLH
**Les participants**

Pour définir la liste des participants, il faut modifier le contenu du tableau `option`:
```javascript
var options=["ApuTicket","predict'it","lc chain","Potatown","MonenK","OhMyBook-family","Havr"];
```
Pour définir la couleur de chaque equipes il faut modifier le contenu du tableau `colors`:
```javascript
var colors=["red","orange","Aqua","Green","Blue","Indigo","grey"];
```
les couleurs peuvent etre definit en rgb (#ab1245)

L'ordre des couleurs est lié a l'ordre des équipes. ("ApuTicket" sera rouge ...)

**La durée**

Pour changer la durée de rotation, il faut modifier dans la ligne: 
```javascript
    spinTimeTotal = Math.random() * 3 + 10 * 1000;
```
la derniére valeur pour la mettre la durée en milliseconde. (`1000`)

**Lancer la roue**

Pour lancer la roue il suffit de cliquer sur l'écran.
A la fin de la rotation, le nom de l'équipe va apparaitre.
il suffit de recliquer sur l'écran pour relancer la roue sans l'équipe selectionné