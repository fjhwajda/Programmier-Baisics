# Programmier-Baisics

Beim Programmieren gibt es einige grundlegende Bausteine, die in fast jeder Programmiersprache vorkommen.
Diese Bausteine bleiben inhaltlich immer gleich, egal wie die Syntax der Sprache aussieht.
Dazu gehören Variablen, Bedingungen, Schleifen, Funktionen, Ein- und Ausgabe sowie Kommentare.
In diesem Dokument werden diese Kernkonzepte zusammengefasst, um den Einstieg ins Programmieren zu erleichtern.

## Varibalen

**int** - ganze zahlen  
```python
int alter = 22;
```
**float** - kommazahlen  
```python
float preis = 3.99;
```

**double** - kommazahlen genauer  
```python
double pi = 3.1415926535
```

**char** - einzelne Zeichen  
```python
char buchstabe 'A'
```
**string** - Wörter/Sätze  
```python
string name = "MAX";
```
**bool** - true or false  
```python
bool istFertig = true;
```
**long** - Grosse zahlen  
```python
long einwohner = 830000;
```

## Arithmetische Operatoren für ganze Zahlen
```java
int a = 34;
int b = 26;

int c = a + b; // = 60
int c = a - b; // = 8
int c = a * b; // = 884
int c = a / b; // = 1 weil / nur ganze zahlen rechnet
int c = a % b; // = 8

// Zuweisungen

c += 3; // entspricht c = c + 3;
c *= 3; // entspricht c = c - 3;
g %= 3; // entspricht c = c % 3;
```

## Bedingungen

`if /else` - wenn etwas ist `if`, sonst mach es `else`  
```python
zahl = 7

if zahl < 5:
    print("Die Zahl ist kleiner als 5")
elif zahl == 5:
    print("Die Zahl ist genau 5")
else:
    print("Die Zahl ist grösser als 5")
```
## Schleifen

`for /while` - der code wird **X** wiederholt `for` während `while` eine Bedinung wahr ist
```python
# for-Schleife: Wiederhole 3 Mal
for i in range(3):
    print(f"For-Schleife Durchlauf {i}")

# while-Schleife: Wiederhole solange Bedingung wahr ist
counter = 0
while counter < 3:
    print(f"While-Schleife Durchlauf {counter}")
    counter += 1
```

## Funktionen

Der Code wird verpackt und kann **wiederverwendet** werden
```python
def addiere(a, b):
    """Diese Funktion addiert zwei Zahlen"""
    return a + b

ergebnis = addiere(5, 10)
print(f"Ergebnis der Funktion: {ergebnis}")
```

## Ein- und Ausgabe
Damit das Programm mit uns redet
```python
name = input("Wie heisst du? ")  # Benutzer gibt Text ein
print(f"Hallo {name}, schön dich zu sehen!")
```

## Kommentare
Texte die der Coputer ignoriert, um bswp. etwas zu beschreiben
```python
# Einzeiliger Kommentar in Python
"""
Mehrzeiliger Kommentar
oder Docstring
"""
```
```cpp
// Einzeiliger Kommentar in C++
/*
   Mehrzeiliger Kommentar
*/
```
```java
// Einzeiliger Kommentar in Java
/*
   Mehrzeiliger Kommentar
*/
```





