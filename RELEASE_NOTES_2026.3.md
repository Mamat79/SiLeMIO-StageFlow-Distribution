# StageFlow 2026.3

## Français

StageFlow 2026.3 renforce son rôle de console centrale de la suite SiLeMIO,
tout en laissant chaque logiciel entièrement autonome.

### Contrôles externes

- nouvel écran **Outils → OSC · MIDI · Stream Deck** ;
- réception OSC locale active par défaut, choix explicite de l’interface réseau,
  du port et des retours d’état ;
- tableau bilingue des commandes et adresses OSC personnalisables ;
- apprentissage MIDI : actionnez un bouton pour l’associer à une commande ;
- retours MIDI facultatifs vers les contrôleurs compatibles ;
- plugin Stream Deck fourni avec l’installation et configurable depuis
  l’inspecteur de propriétés Stream Deck ;
- une même liste d’identifiants commande StageFlow, StageMark et StageMon sur le
  projet LIVE courant.

### Exploitation LIVE

- console de suite réductible dans un coin de l’écran ;
- découverte et synchronisation des logiciels répartis sur plusieurs postes du
  même réseau local ;
- état clair des applications installées, ouvertes et connectées ;
- passerelle QR adaptée aux téléphones et tablettes ;
- alertes LIVE limitées volontairement aux changements de labels ;
- acquittement des alertes propre à chaque contrôleur, avec remise à zéro
  générale depuis StageFlow.

### Projet et compatibilité

- transport sûr des domaines et fichiers binaires appartenant aux autres
  logiciels de la suite ;
- conservation des domaines futurs inconnus pour permettre l’ajout de nouveaux
  outils sans rendre les anciens incompatibles ;
- paquet `.stageflowpack` pour échanger ou archiver un projet comme un seul
  fichier ;
- dépôt public simplifié : `github.com/Mamat79/StageFlow`.

## English

StageFlow 2026.3 adds one external-control centre for OSC, MIDI learn and the
included Stream Deck plugin. A stable shared command list can control StageFlow,
StageMark and StageMon while they are connected to the same LIVE project.

The suite console can now collapse into a compact control strip. Network LIVE
supports applications distributed across several computers on the same local
network, the QR portal adapts to phones and tablets, and LIVE alerts are
deliberately limited to label changes. Future unknown project domains and
binary assets remain preserved, and `.stageflowpack` can carry a project as one
portable file.

Every application remains usable on its own, with LIVE and all external
control features disabled whenever they are not needed.
