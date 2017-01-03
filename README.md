#Adaptateur relais pour carte Remora

Cet adaptateur permet de positionner le relais SSR *G3MC-202P-5V* de Omron pour le pilotage du contacteur jour/nuit du ballon d'eau chaude.

En effet, ce relais fonctionne à l'aide d'un triac et possède un snubber (pont RC série) pour piloter des charges inductives, contrairement au précédent relais électro-mécanique.

Pour le bon fonctionnement du relais, il est nécessaire de supprimer la diode *D15* de la carte Remora.
Le seul moyen que j'ai trouvé pour installer cet adaptateur est de le poser avec des headers. Ce ne sera pas très stable pour la soudure, mais cela s'adapte bien et ça passe dans le boîtier Rail DIN.

**PCB**

![PCB adaptateur](/AdaptorBoard.png)
