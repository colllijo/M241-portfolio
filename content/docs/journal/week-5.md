---
weight: 250
title: "Woche 5 (09.09.2024)"
description: "Lernjournal zur 5. Woche"
icon: "calendar_month"
date: "2024-09-09T14:04:49+02:00"
lastmod: "2024-09-09T14:04:49+02:00"
draft: false
toc: true
---

{{< table >}}

| Thema                       | Beschreibung                                          |
| --------------------------- | ----------------------------------------------------- |
| [Einführung](#einführung)   | Kurzegefasste Einführung zum Inhalt der zweiten Woche |
| [Erarbeitung](#erarbeitung) | Mein Vorgen zum Lösen des Arbeitsauftrags zum HZ 5    |

{{< /table  >}}

{{< alert context="info" >}}

Marktforschung anwenden, Informationen auswerten und aussagekräftig darstellen.

{{< /alert >}}


## Einführung

Heute haben wir uns mit dem Auswerten und Erfassen von Daten beschäftigt.
Dabei ging es vor allem um das Erstellen von Sinnvollen und Hilfreichen Diagrammen,
welche die Daten verständlich darstellen. Dabei sollen diese verhindern, dass
unwichtige Informationen in den Vordergrund rücken und die wichtigen Informationen
vergessen werden.

## Erarbeitung

Als Applikation für, welche ich meine Daten erfinden und auswerten möchte habe ich mich für chess.com entschieden.
Eine Website auf welcher Online-Schach gespielt werden kann. Dabei habe ich mich dazu entschieden folgende Attribute
zu erfassen:

- Alter
- Geschlecht
- Häufigkeit der Nutzung (Tage pro Woche)
- Elo-Rating
- Anzahl der gespielten Partien
- Zeitart der Partien (Blitz, Bullet, Rapid, Daily)
- Premium-Mitgliedschaft (Ja/Nein)
- Bereitschaft für ein Abo (Ja/Nein)

{{< expand "Daten" >}}

{{< table "table-striped" >}}

| Id | Alter | Geschlecht | Nutzung (Tage/Woche) | Elo-Rating | Gespielte Partien | Partien Typ | Premium | Abo-Bereitschaft |
|----|-------|------------|----------------------|------------|-------------------|-------------|---------|------------------|
| 1  | 24    | M          | 5                    | 1500       | 200               | Blitz       | Ja      | Nein             |
| 2  | 30    | F          | 3                    | 1300       | 150               | Rapid       | Nein    | Ja               |
| 3  | 27    | M          | 2                    | 1700       | 300               | Bullet      | Ja      | Ja               |
| 4  | 35    | F          | 6                    | 1800       | 400               | Daily       | Nein    | Nein             |
| 5  | 22    | M          | 4                    | 1600       | 250               | Blitz       | Ja      | Ja               |
| 6  | 31    | F          | 1                    | 1400       | 100               | Rapid       | Nein    | Nein             |
| 7  | 28    | M          | 3                    | 1550       | 220               | Bullet      | Ja      | Ja               |
| 8  | 36    | F          | 5                    | 1750       | 330               | Daily       | Nein    | Nein             |
| 9  | 23    | M          | 2                    | 1650       | 210               | Blitz       | Ja      | Ja               |
| 10 | 32    | F          | 4                    | 1350       | 160               | Rapid       | Nein    | Nein             |
| 11 | 26    | M          | 5                    | 1450       | 190               | Bullet      | Ja      | Ja               |
| 12 | 33    | F          | 3                    | 1550       | 210               | Daily       | Nein    | Nein             |
| 13 | 29    | M          | 2                    | 1650       | 230               | Blitz       | Ja      | Ja               |
| 14 | 34    | F          | 4                    | 1750       | 250               | Rapid       | Nein    | Nein             |
| 15 | 25    | M          | 5                    | 1850       | 270               | Bullet      | Ja      | Ja               |
| 16 | 30    | F          | 3                    | 1950       | 290               | Daily       | Nein    | Nein             |
| 17 | 29    | M          | 3                    | 1450       | 190               | Bullet      | Ja      | Ja               |
| 18 | 33    | F          | 4                    | 1600       | 210               | Rapid       | Nein    | Ja               |
| 19 | 28    | M          | 5                    | 1700       | 230               | Bullet      | Ja      | Ja               |
| 20 | 34    | F          | 2                    | 1800       | 250               | Daily       | Nein    | Nein             |
| 21 | 25    | M          | 3                    | 1900       | 270               | Blitz       | Ja      | Ja               |
| 22 | 31    | F          | 4                    | 2000       | 290               | Rapid       | Nein    | Nein             |
| 23 | 27    | M          | 5                    | 2100       | 310               | Bullet      | Ja      | Ja               |
| 24 | 35    | F          | 2                    | 2200       | 330               | Daily       | Nein    | Nein             |
| 25 | 24    | M          | 3                    | 2300       | 350               | Blitz       | Ja      | Ja               |
| 26 | 32    | F          | 4                    | 2400       | 370               | Rapid       | Nein    | Nein             |
| 27 | 26    | M          | 5                    | 2500       | 390               | Bullet      | Ja      | Ja               |
| 28 | 33    | F          | 4                    | 1200       | 210               | Rapid       | Nein    | Ja               |
| 29 | 28    | M          | 5                    | 1100       | 230               | Bullet      | Ja      | Ja               |
| 30 | 34    | F          | 2                    | 1000       | 250               | Daily       | Nein    | Nein             |
| 31 | 25    | M          | 3                    | 900        | 270               | Blitz       | Ja      | Ja               |
| 32 | 31    | F          | 4                    | 800        | 290               | Rapid       | Nein    | Nein             |
| 33 | 27    | M          | 5                    | 700        | 310               | Bullet      | Ja      | Ja               |
| 34 | 35    | F          | 2                    | 600        | 330               | Daily       | Nein    | Nein             |
| 35 | 24    | M          | 3                    | 500        | 350               | Blitz       | Ja      | Ja               |
| 36 | 32    | F          | 4                    | 400        | 370               | Rapid       | Nein    | Nein             |
| 37 | 26    | M          | 5                    | 300        | 390               | Bullet      | Ja      | Ja               |
| 38 | 33    | F          | 4                    | 1200       | 210               | Rapid       | Nein    | Ja               |
| 39 | 28    | M          | 5                    | 1100       | 230               | Bullet      | Ja      | Ja               |
| 40 | 34    | F          | 2                    | 1000       | 250               | Daily       | Nein    | Nein             |
| 41 | 25    | M          | 3                    | 900        | 270               | Blitz       | Ja      | Ja               |
| 42 | 31    | F          | 4                    | 800        | 290               | Rapid       | Nein    | Nein             |
| 43 | 27    | M          | 5                    | 700        | 310               | Bullet      | Ja      | Ja               |
| 44 | 35    | F          | 2                    | 600        | 330               | Daily       | Nein    | Nein             |
| 45 | 24    | M          | 3                    | 500        | 350               | Blitz       | Ja      | Ja               |
| 46 | 32    | F          | 4                    | 400        | 370               | Rapid       | Nein    | Nein             |
| 47 | 26    | M          | 5                    | 300        | 390               | Bullet      | Ja      | Ja               |
| 48 | 33    | F          | 4                    | 1600       | 210               | Rapid       | Nein    | Ja               |
| 49 | 28    | M          | 5                    | 1700       | 230               | Bullet      | Ja      | Ja               |
| 50 | 34    | F          | 2                    | 1800       | 250               | Daily       | Nein    | Nein             |
| 51 | 25    | M          | 3                    | 1900       | 270               | Blitz       | Ja      | Ja               |
| 52 | 31    | F          | 4                    | 2000       | 290               | Rapid       | Nein    | Nein             |
| 53 | 27    | M          | 5                    | 2100       | 310               | Bullet      | Ja      | Ja               |
| 54 | 35    | F          | 2                    | 2200       | 330               | Daily       | Nein    | Nein             |
| 55 | 24    | M          | 3                    | 2300       | 350               | Blitz       | Ja      | Ja               |
| 56 | 32    | F          | 4                    | 2400       | 370               | Rapid       | Nein    | Nein             |
| 57 | 26    | M          | 5                    | 2500       | 390               | Bullet      | Ja      | Ja               |
| 58 | 33    | F          | 4                    | 1200       | 210               | Rapid       | Nein    | Ja               |
| 59 | 28    | M          | 5                    | 1100       | 230               | Bullet      | Ja      | Ja               |
| 60 | 34    | F          | 2                    | 1000       | 250               | Daily       | Nein    | Nein             |
| 61 | 25    | M          | 3                    | 900        | 270               | Blitz       | Ja      | Ja               |
| 62 | 31    | F          | 4                    | 800        | 290               | Rapid       | Nein    | Nein             |
| 63 | 27    | M          | 5                    | 700        | 310               | Bullet      | Ja      | Ja               |
| 64 | 35    | F          | 2                    | 600        | 330               | Daily       | Nein    | Nein             |

{{< /table >}}

{{< /expand >}}

<br/>

**Lösung:**  
[Chess.com Auswertung](/docs/portfolio/handlungsziel-5/chess.com-auswertung)

### Reflexion

Die Statistiken und Diagramme sind gut.  
Es hat eine gute und Verständliche Struktur.

Man könnte jedoch noch das Loch an Personen, welche 29 und 30 Jahre alt sind hervorheben.
