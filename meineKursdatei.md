<!--
author: Max Mustermann

email: max@mustermann.de

version: 0.1

narrator: Max Mustermann

comment:  Willkommen zu meinem LiaScript Kurs...

logo: ./data/twillo_logo.png

icon: ./data/twillo_logo.svg

language: de

mode: Textbook

link: some.css

-->

# Mein LiaScript Kurs

Herzlich Willkommen zu meinem Kurs!

---

**Inhaltsverzeichnis:**

1. Grundlagen
2. Bilder, Audio & Video
3. Interaktive Elemente

---

**Nützliche Links:**

[Hier gehts zur LiaScript Homepage](https://liascript.github.io/ "LiaScript Homepage")

[Hier gehts zum LiaScript Handbuch](https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#1 "LiaScript Handuch")

## Kapitel 1: Grundlagen

*Allgemeines:*

- *Dieser Text ist Kursiv*
- **Dieser Text ist Fett**
- ***oder beides***

*Links:*

- Einfach als URL: https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#1

- oder [innerhalb](https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#1 "LiaScript Handbuch") des Textes.

### Unterkapitel 1.1:

Platz für mehr...

## Kapitel 2: Bilder, Audio & Video

![img1](data/Beispiel_Image.png)

?[Audio1](data/Beispiel_Audio.mp3)

!?[Video1](https://www.youtube.com/watch?v=8pTEmbeENF4)

!?[](https://youtu.be/8pTEmbeENF4)


## Kapitel 3: Interaktive Elemente

***Single Choice:***

- [(X)] Richtige Antwort
- [( )] Falsche Antwort

---

***Multiple Choice:***

- [[ ]] Empty means not checked
- [[X]] Uppercase `X` means checked ...
- [[x]] ... and lowercase `x` too ...

---

***Eingabefeld mit Hinweisen und Erklärung:***

What is $37 + 15$?

[[solution]]
[[?]] the solution is larger than 50
[[?]] it is less than 55
[[?]] it should be an even number
***********************************************************************
52 is the correct solution, you get this by adding:

``` ascii
                        .------.
                        |      |
                        |      v
                        |
                        |     (1)
  37           3(7)     |     (3)x          37
+ 15         + 1(5)     |   + (1)x        + 15
---- -->     ------ --> |   ------ -->    ----
  ??           (12)     |     (5)2          52
                |       |                 ====
                '-------'
                  carry
```
***********************************************************************

---

***Auswahlfelder:***

What is the derivative function of $f(x) = x^6$?

[[ $f'(x) = 6$ | ( $f'(x) = 6x^5$ ) | $f'(x) = 5x^6$ ]]

Can be also written as:

    [[  $f'(x) = 6$
    | ( $f'(x) = 6x^5$ )
    |   $f'(x) = 5x^6$
    | ( **This will be counted as correct too...** )
    ]]

### Unterkapitel 2.1: Coding

```python +example.py

code goes here...
...
...

```

```javascript -example.js

code goes here...
...

```

## Weiteres

https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#1

[LiaScript Handbuch](https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#1)

![](/data/Beispiel_Image.png)

?[](/data/Beispiel_Audio.mp3)

Wofür steht die Abkürzung "IT"?

- [[ ]] Italien
- [[X]] Informationstechnik

## Video

<iframe width="560" height="315" scrolling="no" src="https://av.tib.eu/player/45544" frameborder="0" allowfullscreen></iframe>
Das Video "Didaktik der Informatim I - Kapitel 2" von Andreas Schwill ist lizenziert unter [CC BY-ND 3.0 DE](https://creativecommons.org/licenses/by-nd/3.0/de/legalcode).


<iframe width="560" height="315" src="https://www.youtube.com/embed/E955up7vtCk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
