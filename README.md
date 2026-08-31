<p align="center">
  <img src="stageflow-logo.png" alt="SiLeMIO StageFlow" width="680">
</p>

<h1 align="center">SiLeMIO StageFlow</h1>

<p align="center">
  <strong>Préparez le patch, les groupes et le plan de scène dans un seul projet.</strong><br>
  Gratuit · Hors ligne · Français / English · Windows 11
</p>

<p align="center">
  <a href="https://github.com/Mamat79/SiLeMIO-StageFlow-Distribution/releases/latest"><strong>⬇ Télécharger StageFlow</strong></a>
</p>

---

## StageFlow, à quoi ça sert ?

StageFlow est un logiciel de préparation pour le spectacle, la captation, le
broadcast et l’événementiel. Il rassemble dans un même projet le patch de
scène, les paires communes, les groupes de travail et un plan simple.

L’objectif est direct : **préparer une seule fois, imprimer ce dont chaque
équipe a besoin et éviter de ressaisir les mêmes informations dans plusieurs
logiciels**.

StageFlow peut être utilisé seul. Il peut aussi devenir le centre d’un flux
partagé avec SMT, Dante Config Editor, StageMark, Stage Monitoring et AutoCAD.
Chaque logiciel reste autonome et vous installez uniquement ceux dont vous avez
besoin.

## Un exemple concret

Vous préparez une scène avec 40 paires, cinq groupes et plusieurs lignes
communes :

1. choisissez le nombre de paires et de groupes — les choix rapides avancent
   par blocs de 20, mais vous pouvez saisir librement une autre valeur ;
2. saisissez les sources, micros et commentaires dans le tableau ;
3. placez les lignes communes dans la section partagée, puis décidez dans
   chaque groupe quelles paires communes doivent apparaître ;
4. utilisez le copier-coller ou tirez une sélection vers le bas pour prolonger
   une liste ;
5. exportez un classeur Excel avec une feuille A4 par groupe ;
6. dessinez les premiers éléments du plan ou poursuivez le travail dans
   AutoCAD ;
7. ouvrez ensuite le même projet dans les autres logiciels SiLeMI/O si vous en
   avez besoin.

Vous gardez ainsi un seul dossier de projet au lieu de plusieurs documents qui
finissent par se contredire.

## Ce que vous pouvez faire avec StageFlow

### Construire un patch à votre taille

- Choisir librement le nombre de paires, avec des raccourcis 20, 40, 60, etc.
- Créer autant de groupes que nécessaire.
- Ajouter des paires communes à tous les groupes.
- Voir les valeurs communes directement dans chaque groupe.
- Afficher ou masquer chaque paire commune, séparément pour chaque groupe.
- Utiliser **Tout afficher** ou **Tout masquer** pour régler un groupe en un clic.
- Modifier les cellules comme dans un tableur.
- Utiliser **Entrée** pour descendre et **Tab** pour passer à la cellule
  suivante, immédiatement prête à saisir.
- Copier et coller depuis ou vers Excel.
- Recopier une valeur ou prolonger une suite en tirant vers le bas.

### Préparer des feuilles faciles à imprimer

StageFlow génère un classeur Excel organisé par groupe. Chaque groupe possède
sa propre feuille, prévue pour tenir sur une page A4 paysage lisible. Les
paires communes masquées dans un groupe restent également absentes de sa page,
tandis que les valeurs propres à ce groupe sont conservées.

Le résultat peut être corrigé dans Excel, imprimé, envoyé ou réimporté dans
StageFlow. Le libellé est **Balances** en français et **Sound check** en
anglais.

### Dessiner un plan de scène

L’éditeur de plan permet de poser les éléments essentiels d’une implantation et
de garder le plan avec le patch du spectacle.

Si AutoCAD 2026 est installé, le connecteur optionnel ajoute l’onglet
**SILEMI/O** et la commande **Patch StageFlow** pour poursuivre le plan
technique dans AutoCAD.

### Conserver un vrai projet

Un projet StageFlow est un dossier portant l’extension
<code>.stageflow</code>. Il peut être sauvegardé, rouvert, copié sur un autre
ordinateur ou archivé avec le reste du dossier de production.

### Choisir le Mode LIVE ou le travail manuel

Activez **Mode LIVE** lorsque StageFlow doit coordonner le spectacle. Les pages
de groupes, labels, micros, commentaires et choix de paires communes sont alors
publiés automatiquement et les logiciels compatibles suivent le projet en
temps réel.

Coupez LIVE à tout moment pour revenir à un fonctionnement entièrement manuel :
**Enregistrer** et **Recharger** restent sous votre contrôle et chaque logiciel
continue de fonctionner seul. Une mise à jour StageMark ne déclenche jamais une
projection et une mise à jour Dante ne commande jamais le réseau en direct.

## Un seul projet, plusieurs outils

~~~mermaid
flowchart LR
    P[("Projet .stageflow")]
    SF["StageFlow<br/>Patch + plan"] <--> P
    SMT["SMT<br/>Préparation console"] <--> P
    DCE["Dante Config Editor<br/>Réseau Dante"] <--> P
    SM["StageMark<br/>Implantation + projection"] <--> P
    MON["Stage Monitoring<br/>Écoutes live"] <--> P
    CAD["AutoCAD<br/>Plan technique"] <--> P
~~~

Vous installez uniquement les outils dont vous avez besoin. StageFlow est
gratuit et facultatif, et les autres logiciels peuvent ouvrir le projet commun
sans que StageFlow soit lancé.

- [SMT — transférer labels et réglages entre consoles et logiciels](https://github.com/Mamat79/Save-My-Time-SMT/releases/latest)
- [Dante Config Editor — préparer un réseau Dante hors ligne](https://github.com/Mamat79/Dante-Config-Editor/releases/latest)
- [StageMark — dessiner, implanter et projeter des repères](https://github.com/Mamat79/StageMark/releases/latest)
- **Stage Monitoring — deux écoutes stéréo et sélection rapide des sources**

## Installation Windows

1. Ouvrez la [dernière version](https://github.com/Mamat79/SiLeMIO-StageFlow-Distribution/releases/latest).
2. Téléchargez <code>SiLeMIO-StageFlow-Setup.exe</code>.
3. Lancez l’installateur.
4. Gardez l’option AutoCAD cochée si vous souhaitez installer le connecteur.

L’application et le connecteur AutoCAD peuvent être installés ou utilisés
indépendamment selon votre méthode de travail.

## Aide intégrée

Le menu **Aide** et la touche **F1** ouvrent un guide directement dans
l'application. Il explique la création du projet, les paires communes, les
groupes, Excel, l'impression A4 et le lien avec les autres outils SiLeMIO.

---

## English

### What is StageFlow for?

StageFlow is a free offline preparation tool for live events, broadcast,
recording and production work. It keeps the stage patch, shared lines, working
groups and a simple stage plan in one project.

The goal is simple: **prepare the information once, print the right sheet for
each team and avoid entering the same data in several applications**.

### A typical workflow

1. Choose the required number of pairs and groups. Quick choices use blocks of
   20, while any custom value can still be entered.
2. Enter sources, microphones and comments in the spreadsheet-style grid.
3. Add shared lines, then choose which common pairs appear in each group.
4. Copy, paste or drag down to continue a list.
5. Export an Excel workbook with one printable A4 sheet per group.
6. Draw the first stage elements or continue the technical plan in AutoCAD.
7. Open the same project in other SiLeMI/O applications when needed.

StageFlow works on its own. The shared <code>.stageflow</code> project can also
be opened by SMT, Dante Config Editor, StageMark, Stage Monitoring and the
optional AutoCAD 2026 connector.

### Main features

- Any number of pairs and groups, with quick 20-pair increments.
- Shared values visible directly inside individual groups.
- Per-pair, per-group common-line visibility plus **Show all** and **Hide all**.
- Spreadsheet-style editing, copy/paste and smart fill.
- Fast keyboard entry: **Enter** moves down and **Tab** opens the next cell for
  immediate typing.
- Excel export and refresh.
- One landscape A4 page per group, respecting its common-line choices.
- Localized Excel labels: **Balances** in French and **Sound check** in English.
- Simple stage-plan editor.
- Optional AutoCAD connector.
- Explicit **LIVE mode** for real-time coordination with compatible apps.
- French and English interface.
- Built-in help from the **Help** menu or `F1`.
- Local, offline projects with no mandatory cloud service.

Turn LIVE mode off at any time to restore manual Save/Reload operation in
every application. All SiLeMIO tools remain fully standalone.

### Download

StageFlow is currently available for Windows 11 x64.

**[Download the latest StageFlow release](https://github.com/Mamat79/SiLeMIO-StageFlow-Distribution/releases/latest)**

---

<p align="center"><strong>SiLeMIO · By Mamat----[]---</strong></p>
