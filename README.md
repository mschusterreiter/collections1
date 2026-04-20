
# Übung 21 - Collections


## 1. Aufgabe

Setzen Sie folgendes Klassendiagramm um:

<p align="center">
  <img src="/assets/images/UML1.png" alt="Bildbeschreibung" />
</p>

**Beschreibung der `Person`-Klasse:**

- Eigenschaften: 
	- Im Konstruktor müssen die `set`-Methoden aufgerufen werden. 
	- Prüfen Sie alle Eigenschaften auf sinnvolle Werte. 

- Methoden: 
	- `getGeburtsjahr()`: Berechnet das Geburtsjahr anhand des Alters.
	- `toString()`: Überschreiben Sie die `toString()`-Methode. Geben Sie einen String zurück, welcher alle Eigenschaften beinhaltet. 

**Beschreibung der `Personenverwaltung`-Klasse:**
- Eigenschaften: 
	- Der Konstruktor soll `personenList` initialisieren.
- Methoden:
	- `addPerson(Person p)`: Fügt Person `p` der Liste hinzu.
	- `removePerson(Person p)`: Entfernt Person `p` aus der Liste.
	- `removePerson(int i)`: Entfernt die Person an der Stelle `i` aus der Liste und gibt sie zurück.
	- `findPersonsByNachname(String nachname)`: Gibt alle Personen der List mit dem gleichen Nachnamen in einer neuen Liste zurück. 
	- `findPersonsByGeburtsjahr(int geburtsjahr)`: Gibt alle Personen der Liste mit dem gleichen Geburtsjahr in einer neuen Liste zurück.
	- `printList()`: Gibt alle Personen der Liste aus. 

Um Ihr Programm zu testen, erstellen Sie eine `Main`-Klasse, welche die `main`-Methode beinhaltet:
- `main(String[] args)`: Testen Sie Ihr Programm, indem Sie die Methoden aufrufen. 

## 2. Aufgabe

Setzen Sie folgendes Klassendiagramm um:

<p align="center">
  <img src="/assets/images/UML1.png" alt="Bildbeschreibung" />
</p>

**Beschreibung der `ToDoItem`-Klasse:**

- Eigenschaften: 
	- Prüfen Sie alle Eigenschaften auf sinnvolle Werte. 

- Methoden: 
	- `toString()`: Überschreiben Sie die `toString()`-Methode. Geben Sie einen String zurück, welcher alle Eigenschaften beinhaltet. 

**Beschreibung der `ToDoList`-Klasse:**
- Eigenschaften: 
	- Der Konstruktor soll `items` initialisieren.
- Methoden:
	- `addtask(String beschreibung, DateTime bisDatum, int prioritaet)`: Fügt der Liste am Ende einen neuen Task hinzu.
	- `removeTask(int index)`: Löscht den Task mit dem angegebenen Index aus der Liste.
	- `removePerson(int i)`: Entfernt die Person an der Stelle `i` aus der Liste und gibt sie zurück.
	- `markiereAlsErledigt(int index)`: Kennzeichnet den Task mit dem angegebenen Index als erledigt.
	- `sortByPrioritaet()`: Sortiert die Liste nach der Priorität. 
	-  `sortByDate()`: Sortiert die Liste nach dem Datum. 
	- `sortByStatus()`: Sortiert die Liste nach dem Status eines Tasks (erledigt/nicht erledigt).
	- `printTasks()`: Gibt alle Tasks der Liste aus. 

Um Ihr Programm zu testen, erstellen Sie eine `Main`-Klasse, welche die `main`-Methode beinhaltet:
- `main(String[] args)`: Testen Sie Ihr Programm, indem Sie die Methoden aufrufen. 

## 3. Aufgabe

Schreiben Sie eine Methode, welche einen String als Parameter hat und diesen umdreht. Verwenden Sie dafür die Struktur eines Stacks. 
**Beispiel:** Aus BBRZ wird ZRBB

Um Ihr Programm zu testen, erstellen Sie eine `Main`-Klasse, welche die `main`-Methode beinhaltet:
- `main(String[] args)`: Testen Sie Ihr Programm, indem Sie die Methoden aufrufen. 
