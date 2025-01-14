# Aufgabe: Erstellung eines Mitarbeiterverwaltungssystems
## Problemstellung:
Erstellen Sie ein Python-Programm, das ein einfaches Mitarbeiterverwaltungssystem simuliert. Dabei sollen folgende Funktionen implementiert werden:

1. Module: Organisieren Sie den Code in mehreren Dateien:

    * `employee.py` für die Definition der Klasse Employee und ihrer Unterklassen.
    * `utilities.py` für Hilfsfunktionen wie Validierung und Dekoratoren.
    * `main.py` für das Hauptskript.
2. Klassen & Vererbung:

    * Erstellen Sie eine Basisklasse `Employee` mit den Attributen `name`, `employee_id` und `salary`.
    * Erstellen Sie zwei Unterklassen:
        * `Manager`: Zusätzlich ein Attribut `department`.
        * `Developer`: Zusätzlich ein Attribut `programming_language`.
3. Lambdas:

    * Verwenden Sie eine Lambda-Funktion, um Mitarbeiter anhand ihres Gehalts zu sortieren.
4. Dekoratoren:

    * Erstellen Sie einen Dekorator, der protokolliert, wann eine Methode aufgerufen wird und welcher Mitarbeiter betroffen ist.
5. Iteratoren:

    * Erstellen Sie eine Klasse, die es ermöglicht, durch eine Liste von Mitarbeitern zu iterieren.
6. Reguläre Ausdrücke:

    * Validieren Sie die Eingaben für den `employee_id` (z. B. muss `EMP12345` entsprechen).