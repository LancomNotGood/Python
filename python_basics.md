# Python Basics


- also dieser ganze mist basiert ja quasi auf variablen, wie mache ich eine?
```
variable
variable_01
variable_02
```
Also ohne vorzeichen oder alles andere
---



Wie geben wir uns irgendwas in python aus?

```
print("das was geprintet werden soll")
```
Am besten **IMMER** mit Anführungszeichen

---

Wir können also etwas ausgeben und wissen wie wir eine Variable "erstellen"... Wie wird einer Variable etwas zugewiesen?
- Es gibt verschiedene Datentypen die verschieden "deklariert" werden, eine Zahl deklariere ich anders als ein Wort oder eine Liste...

## Datentypen

- **Integer (`int`)**
  - Ganzzahlen, z.B. `42` oder `-7`.
  - Verwendung: Was mann mit zahlen halt so macht....

- **Float (`float`)**
  - Gleitkommazahlen, z.B. `3.14` oder `-0.001`.
  - Verwendung: Dezimalzahlen.

- **String (`str`)**
  - Zeichenketten, z.B. `"Hallo Welt"` oder `"123"`.
  - Verwendung: ganz normaler Text halt

- **Boolean (`bool`)**
  - Wahrheitswerte, `True` oder `False`.
  - Verwendung: einfach nur ja oder nein

- **Liste (`list`)**
  - Sammlung von Elementen, z.B. `[1, 2, 3]` oder `["a", "b", "c"]`.
  - Verwendung: ähnlich wie der rest, muss ich ne Liste jetzt nicht erklären

Das wäre jetzt erstmal so der basic kram
---
Wie teilen wir jetzt einer Variable einen Wert zu?
```
Variable1 = 10
```
das wars eigentlich schon...

- Wie kann ich mir den Wert einer Variable jetzt aber printen lassen?
```
Variabl1e = 1000
print("Variable")
```
Also, wenn ich meiner variable eine Zahl zuweisen möchte mache ich einfach eine Zahl hinter das =
- und so funktioniert das mit dem ganzem anderem kram größtenteils auch
    - Kommazahl einfach als Kommazahl dahinter schreiben
    - Strings funktionieren nur mit Anführungszeichen "string" "oder auch mehrere wörter"
    - jetzt kann ich natürlich auch sowas wie a - b machen oder a + b:
 
```
one = 1
two = 2
three = one + two
print(three)

hello = "hello"
world = "world"
helloworld = hello + " " + world
print (helloworld)
```
das Ergebnis wäre folgendes:
```
lelsner@pythonfodummies:~$ python3 example.py
3
hello world
```

- Wenn man solche sachen macht, müssen die Datentypen aber natürlich immer gleich sein, also ich kann jetzt kein String + Number kram machen
- 

## Lists
- Lists sind quasi wie arrays, diese können jede Form und Anzahl von Variablen enthalten

- Eine Liste erstelle ich mit eckigen klammer `[]`
- in die Eckige Klammer kommen dann meine Werte rein: meine_einkaufsliste = ["äpfel", "birnen", "Brot"]
- ausgeben kann ich das ganze mit folgendem Befehl: print(meine_einkaufsliste[0])
- der wert in den Eckigen Klammern gibt an welcher Wert ausgegeben werden soll, `**WICHTIG:ES GEHT IN DER LISTE BEI 0 LOS**`

Hier einmal ein Beispiel:
```
meine_einkaufsliste = ["Eier","Schnaps","Schokolade"]
print(meine_einkaufsliste[2])
```
- Man kann natürlich auch sachen in dieser Liste hinzufügen, das mache ich mit dem "append" statement: meine_einkaufsliste.´append`("butter")
```
mylist = []
mylist.append(1)
mylist.append(2)
mylist.append(3)
print(mylist[1])
print(mylist[2])
print(mylist[3])

for x in mylist:
    print(x)
```
