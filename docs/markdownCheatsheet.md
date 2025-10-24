# Markdown Language

## Einführung
Markdown ist eine leicht verständliche Formatierungssprache, mit der  Textdokumente im Klartext formatiert werden können. Markdown wurde 2004 von [John Gruber](https://daringfireball.net/projects/markdown/) entwickelt und ist heute eine der weltweit beliebtesten Formatierungssprachen. Hilfreiche Informationen gibt es auch [hier](https://www.markdownguide.org)

Das übergeordnete Designziel für die Formatierungssyntax von Markdown ist es, sie so lesbar wie möglich zu gestalten. Die Idee dahinter ist, dass ein mit Markdown formatiertes Dokument auch unverändert als einfacher Text veröffentlicht werden kann, ohne dass es so aussieht, als wäre es mit Tags oder Formatierungsanweisungen versehen worden. 

Zu diesem Zweck besteht die Syntax von Markdown ausschließlich aus Satzzeichen, die sorgfältig ausgewählt wurden, damit sie so aussehen, wie sie gemeint sind. Beispielsweise sehen Sternchen um ein Wort herum tatsächlich wie *Hervorhebungen* aus. 

Markdown ist kein Ersatz für HTML und kommt diesem auch nicht annähernd gleich. HTML ist ein Veröffentlichungsformat, Markdown ist ein Schreibformat. Daher befasst sich die Formatierungssyntax von Markdown nur mit Problemen, die in reinem Text vermittelt werden können. Für alle Markups, die nicht von der Syntax von Markdown abgedeckt sind, verwenden Sie einfach HTML selbst.

Sie verwenden einfach die HTML-Tags. 
Die einzigen Einschränkungen bestehen darin, dass HTML-Elemente auf Blockebene – z. B. `<div>`, `<table>`, `<pre>`, `<p>` usw. – durch Leerzeilen vom umgebenden Inhalt getrennt werden müssen und die Start- und End-Tags des Blocks nicht mit Tabulatoren oder Leerzeichen eingerückt werden dürfen. 

Span-Level-HTML-Tags – z. B. `<span>`, `<cite>` oder `<del>` – können überall in einem Markdown-Absatz, Listenelement oder einer Überschrift verwendet werden.


## Grundlegende Syntax

### Überschriften
**Markdown Syntax**
```markdown
# Hauptüberschrift (H1)
## Unterüberschrift (H2)
### Unterunterüberschrift (H3)
#### Unterunterunterüberschrift (H4)
##### Unterunterunterunterüberschrift (H5)
###### Unterunterunterunterunterüberschrift (H6)
```
**Gerendert:**
# Hauptüberschrift (H1)
## Unterüberschrift (H2)
### Unterunterüberschrift (H3)
#### Unterunterunterüberschrift (H4)
##### Unterunterunterunterüberschrift (H5)
###### Unterunterunterunterunterüberschrift (H6)

### Textformatierung
- **Fett**: `**fett**` oder `__fett__`
- *Kursiv*: `*kursiv*` oder `_kursiv_`
- ~~Durchgestrichen~~: `~~durchgestrichen~~`

### Listen
#### Aufzählung
**Markdown Syntax**
```markdown
- Element 1
- Element 2
  - Unterelement 2.1
  - Unterelement 2.2
```
**Gerendert:**
- Element 1
- Element 2
  - Unterelement 2.1
  - Unterelement 2.2


#### Nummerierte Liste

**Markdown Syntax**
```markdown
1. Erster Punkt
2. Zweiter Punkt
   1. Unterpunkt 2.1
   2. Unterpunkt 2.2
```

**Gerendert:**
1. Erster Punkt
2. Zweiter Punkt
   1. Unterpunkt 2.1
   2. Unterpunkt 2.2


### Links
**Markdown Syntax:**
```markdown
[Linktext](https://www.example.com)
```
**Gerendert:**

### Bilder
**Markdown Syntax:**
```markdown
![Alternativtext](https://www.example.com/bild.jpg)
```
**Gerendert:**
[Linktext](https://www.example.com)

### Zitate

**Markdown Syntax:**
```markdown
> Dies ist ein Zitat.
```
**Gerendert:**
> Dies ist ein Zitat.

### Code
#### Inline-Code
**Markdown Syntax:**
```markdown
Hier ist `inline code`.
```
**Gerendert:**
```markdown
Hier ist `inline code`.
```

#### Codeblock
**Markdown Syntax:**
```markdown
```
Mehrzeiliger Code
```
```

## Erweiterte Features

### Tabellen
**Markdown Syntax:**
```markdown
| Header 1 | Header 2 |
|----------|----------|
| Zeile 1  | Zeile 2  |
| Zeile 3  | Zeile 4  |
```
**Gerendert:**
| Header 1 | Header 2 |
|----------|----------|
| Zeile 1  | Zeile 2  |
| Zeile 3  | Zeile 4  |


### Aufgabenlisten
**Markdown Syntax:**
```markdown
- [ ] Aufgabe 1
- [x] Aufgabe 2 (erledigt)
- [ ] Aufgabe 3
```
**Gerendert:**
- [ ] Aufgabe 1
- [x] Aufgabe 2 (erledigt)
- [ ] Aufgabe 3


### Fußnoten
**Markdown Syntax:**
```markdown
Dies ist ein Satz mit einer Fußnote.[^1]

[^1]: Dies ist die Definition der Fußnote.
```
**Gerendert:**
Dies ist ein Satz mit einer Fußnote.[^1]

[^1]: Dies ist die Definition der Fußnote.

## HTML-Elemente
Du kannst auch HTML-Tags verwenden:
**Markdown Syntax:**
```html
<b>Fett</b>
<i>Kursiv</i>
```
**Gerendert:**
<b>Fett</b>
<i>Kursiv</i>

## Weitere Ressourcen
- [Markdown Guide](https://www.markdownguide.org/)
- [Dillinger Markdown Editor](https://dillinger.io/)
