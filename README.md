# Programmieren lernen

## 1. Algorithmen Grundlagen

- [Was sind Algorithmen?](https://www.youtube.com/watch?v=kM9ASKAni_s)
- [Aus welchen Bestandteilen bestehen Algorithmen? Sequenzen, Selektionen und Schleifen](https://www.youtube.com/watch?v=eSYeHlwDCNA)

## 2. Syntax

Definition und Aufruf einer generischen Funktion in C und Python:
```c
return_type function_name(param_type parameter1, param_type parameter2, ...) {
    //Code
    return ...;
}

function_name(2, -3);
```

```python
def function_name(parameter1, parameter2, ...):
    #Code
    return ...

function_name(2, -3)
```

Beispiel: eine Funktion in C und Python, die das Produkt zweier Zahlen berechnet:
```c
int produkt(int faktor1, int faktor2) {
    int ergebnis = faktor1 * faktor2;
    return ergebnis;
}

function_name(2, -3); // => -6
```

```python
def produkt(faktor1, faktor2):
    ergebnis = faktor1 * faktor2
    return ergebnis

produkt(2, -3)
```

## 3. typische Gedankengänge

Eingabe:
1. Woher kommen alle Daten? (z.B. Kommandozeile)
2. Welche Verarbeitungsschritte müssen durchgeführt werden? (z.B. Auswechseln der Umlaute mit ae, oe und ue oder Umwandlungen von Strings in Integer)

Datenstruktur:
3. Welche Datentypen werden benutzt? (z.B. Strings, Integers, ...)
4. Lassen sich die Daten in einer einzelnen Klasse, einer Menge von Arrays oder einem Array von Klassen abspeichern?

Verarbeitung:
5. ?
6. ?

Ausgabe:
7. ?
8. ?

## 4. Die nächsten Schritte

Gehe nun in den ["Wiki"-Tab](https://github.com/jonaheinke/programmieren-lernen/wiki) des Repositoriums und arbeite dort die Beispielaufgaben durch.

<details>
    <summary>Q1: What is the best programming language in the world?</summary>
    A1: Python
</details>

\
Q2: Ordne folgende Begriffe in die Kategorien Befehl, Verzweigung und Schleifen ein. Wenn mehrere Kategorien zutreffen, ist eine kurze Erklärung notwendig.

if, Zuweisung, return, for, do ... while, Funktionsaufruf, Variablendefinition, else, break, switch ... case, i++, goto

Test