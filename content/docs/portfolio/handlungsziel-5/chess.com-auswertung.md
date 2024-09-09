---
weight: 151
title: "Chess.com Auswertung"
description: ""
icon: "article"
date: "2024-09-09T14:42:43+02:00"
lastmod: "2024-09-09T14:42:43+02:00"
draft: false
toc: true
---

## Auswertung

Hier sind die Diagramme zu den Erfassten Daten von chess.com

### Alter

Das Durchschnittsalter der Spieler liegt bei 29 Jahren.
Jedoch gibt es sehr wenige Spieler, welche Tatsächlich 29 und 30 Jahre alt sind.

```mermaid
%%{init: {'theme':'dark'}}%%
xychart-beta
    title "Alter"
    x-axis "Alter in Jahren" 20 --> 40
    y-axis "Personen" 0 --> 10
    bar [0, 0, 1, 1, 5, 6, 5, 6, 6, 2, 2, 6, 5, 6, 6, 6, 1, 0, 0, 0, 0]
```

### Geschlecht

Die Geschlechterverteilung ist sehr ausgeglichen und endet bei 50/50

```mermaid
%%{init: {'theme':'forest'}}%%
pie
    title Geschlecht
    "Männlich" : 32
    "Weiblich" : 32
```

### Nutzung (Tage/Woche)

Die Nutzung von chess.com ist sehr unterschiedlich, wobei die meisten Spieler 4 oder 5 Tage pro Woche spielen.

```mermaid
%%{init: {'theme':'dark'}}%%
xychart-beta
    title "Nutzung"
    x-axis "Tage pro Woche" [1, 2, 3, 4, 5, 6, 7]
    y-axis "Personen" 0 --> 20
    bar [1, 13, 14, 17, 18, 1, 0]
```

### Partien Typ

Die meisten Nutzer bevorzugen kurze Partien und spielen Bullet oder Rapid.

```mermaid
%%{init: {'theme':'forest'}}%%
pie
    title Partien Typ
    "Bullet" : 19
    "Blitz" : 13
    "Rapid" : 18
    "Daily" : 14
```

### Abo Bereitschaft

Die Bereitschaft für ein Abo ist bei den meisten Nutzern gegeben.

```mermaid
%%{init: {'theme':'forest'}}%%
pie
    title Bereitschaft für ein Abo
    "Ja" : 37
    "Nein" : 27
```
