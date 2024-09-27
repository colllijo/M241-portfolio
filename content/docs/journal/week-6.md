---
weight: 260
title: "Woche 6 (16.09.2024)"
description: "Lernjournal zur 6. Woche"
icon: "calendar_month"
date: "2024-09-16T13:11:48+02:00"
lastmod: "2024-09-16T13:11:48+02:00"
draft: false
toc: true
---


{{< table >}}

| Thema                           | Beschreibung                                          |
| ------------------------------- | ----------------------------------------------------- |
| [Einführung](#einführung)       | Kurzegefasste Einführung zum Inhalt der zweiten Woche |
| [Übersicht](#übersicht)       | Übersicht über Mögliche Methoden und Faktroen der unterschiedlichen Bereiche. |
| [Erarbeitung](#erarbeitung) | Mein Vorgen zum Lösen des Arbeitsauftrags zum HZ 6    |

{{< /table  >}}

{{< alert context="info" >}}

Lösungsvarianten bewerten.

{{< /alert >}}


## Einführung

Heute ging es um HZ 6, dass Bewerten von Lösungsvarianten. Ziel dabei war es
Methoden zu Analysierung von Risiken und Chancen zu erlernen und anzuwenden.
Dazu haben wir uns auch mit technischen und betriebswirtschaftlichen Faktoren
beschäftigt, welche für die Lösungswahl relevant sein können.

## Übersicht

{{< split type="start" >}}

**Risikianalysierungsmethoden:**

- [SWOT-Analyse](https://de.wikipedia.org/wiki/SWOT-Analyse)
- [Risiko Matrix](https://de.wikipedia.org/wiki/Risikomatrix)
- [Failure Mode and Effects Analysis (FMEA)](https://de.wikipedia.org/wiki/Failure_Mode_and_Effects_Analysis)
- [Szenarioanalyse](https://de.wikipedia.org/wiki/Szenarioanalyse)

**Potenzialabschätzungsmethoden:**

- [Marktanalyse](https://de.wikipedia.org/wiki/Marktanalyse)
- [Wettbewerbsanalyse](https://de.wikipedia.org/wiki/Wettbewerbsanalyse)
- [Kundenfeedback und Bedarfsanalyse](https://de.wikipedia.org/wiki/Kundenbefragung)
- [Technische Machbarkeitsstudie](https://de.wikipedia.org/wiki/Machbarkeitsstudie)
- NABC Modell
- [Business Canvas Model](https://de.wikipedia.org/wiki/Business_Model_Canvas)

**Qualitative Methoden:**

- Experteneinschätzungen
- [Delphi-Methode](https://de.wikipedia.org/wiki/Delphi-Methode)
- Stakeholder-Analyse

{{< split >}}

**Technische Faktoren:**

- Technische Machbarkeit:
- Prüfung
- Evaluierung
- Skalierbarkeit und Flexibilität:
- Integration und Interoperabilität:
- Kompatibilität
- Sicherheit und Datenschutz:

**Betriebswirtschaftliche Faktoren:**

- Kosten und Budget
- Return on Investment (ROI)
- Zeitrahmen und Projektzeitplan
- Betriebliche Auswirkungen
- Markt- und Wettbewerbssituation

{{< split type="end" >}}

## Erarbeitung

Für die Aufgabe habe ich mich für eine eigene Idee entschieden.
Dies ist ein CTF-Solver, eine Applikation welche das Lösen von Capture the Flags (CTFs) erleichtern soll.
Hier gibt es unterschiedliche Tätigkeiten, welche manuell durchgeführt werden müssen in sich selber jedoch
nicht dazu beitragen, dass Rätsel zu lösen.

Dabei soll der CTF-Solver mit dem Namen "CTFp" eine freie und Open-Source Software sein, welche
von allen genutzt werden kann. Die Software soll dabei die folgenden Funktionen bieten:

- Automatisches Herunterladen von CTFs
- Erstellen von zur Lösung notwendigen Strukturen (z.B. Initialisieren eines Python venv)
- Möglichkeit zur Einsendung einer Flagge
- Möglichkeit eine Flagge direkt nach Ausführung eines Skripts zu senden
- Anzeigen von Statistiken zu gelösten CTFs
- Anzeigen der aktuellen Rangliste
- Automatisches aktualisieren der heruntergeladenen CTFs
- Markieren von bereits gelösten CTFs

Der Business Case für die CTFp-Software ist in der [Portfolio-Dokumentation](/docs/portfolio/handlungsziel-6/ctfp) zu finden.
