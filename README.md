# Markdown-Dokumentation

## Einleitung

Markdown ist eine leichte und einfach zu erlernende Auszeichnungssprache zur Formatierung von Texten. In diesem Dokument werden verschiedene Funktionen von Markdown vorgestellt, um eine übersichtliche und gut strukturierte Dokumentation zu erstellen.

---

## Überschriften

### H1 - Hauptüberschrift

Markdown ermöglicht das Erstellen von Überschriften unterschiedlicher Ebenen. Hier sind einige Beispiele:

# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternativ können auch Unterstriche verwendet werden:

H1
===

H2
---

---

## Trennstriche

Trennstriche werden häufig verwendet, um Abschnitte zu unterteilen:

---

## Hervorgehobene Wörter

Markdown ermöglicht das Hervorheben von Wörtern in verschiedenen Formen:

*Dieser Text ist kursiv.*

**Dieser Text ist fett.**

_Alternativ kann auch ein Unterstrich für Kursiv verwendet werden._

__Für Fettschrift kann auch zwei Unterstriche genutzt werden.__

---

## Aufzählungen

### Ungeordnete Aufzählungen

- Punkt 1
- Punkt 2
  - Unterpunkt 2.1
  - Unterpunkt 2.2

### Geordnete Aufzählungen

1. Erster Punkt
2. Zweiter Punkt
   1. Unterpunkt 2.1
   2. Unterpunkt 2.2

---

## Links

Verweise können mit [Text](URL) erstellt werden, wie zum Beispiel: [GitHub](https://github.com/).

---

## Quellcode

Quellcode kann einfach mit Backticks (\`) eingeschlossen werden. Syntax-Highlighting kann durch Hinzufügen der Sprache erfolgen.

```python
def hello_world():
    print("Hello, World!")

```
## Durchgestrichene Absätze

~~Dieser Text ist durchgestrichen.~~

---

## Text Highlighting

==Dieser Text wird hervorgehoben.==

---

## Hoch- und Tiefgestellte Zeichen


Hochgestelltes Zeichen: 2<sup> 3</sup>

Tiefgestelltes Zeichen: H<sub>2 </sub>O


---

## Deaktivierte URL-Verknüpfungen

https://example.com

Diese URL ist deaktiviert.

---
## Blockzitate

Blockzitate werden durch ein vorangestelltes ">" erstellt:

> Dies ist ein Blockzitat.
> Es kann mehrere Zeilen umfassen.

---

## Fußnoten

Fußnoten können wie folgt erstellt werden[^1]:

[^1]: Dies ist der Fußnotentext.

---

## Task Listen

- [x] Erledigter Task
- [ ] Nicht erledigter Task

---
## Quellcode ohne Syntax
 hello_world():
    print("Hello, World!")

---
## Tabellen mit unterschiedlicher Textausrichtung

Tabellen können mit verschiedenen Ausrichtungen erstellt werden:

| Links ausgerichtet | Zentriert | Rechts ausgerichtet |
| :------------------ | :-------: | -------------------: |
| Text links          | Text Mitte | Text rechts          |
| 123                 |   456     |                   789 |
---
## Bilder mit Textangabe

Bilder können mit einem Ausrufezeichen und eckigen Klammern eingefügt werden:


![Markdown Logo](https://markdown-here.com/img/icon256.png)

