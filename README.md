# Kata: Leap Year Checker

Diese Aufgabe dient dazu, die Regeln für Schaltjahre im Gregorianischen Kalender zu verstehen und anzuwenden.

## Aufgabe

Erstelle eine Datei `leap_year_checker.py` im Root-Verzeichnis deines Repositories.

Schreibe eine Funktion `is_leap`, die eine Ganzzahl `year` akzeptiert. Die Funktion soll bestimmen, ob das gegebene Jahr ein Schaltjahr ist oder nicht. Ein Jahr ist ein Schaltjahr, wenn es die folgenden Bedingungen erfüllt:

- Das Jahr ist durch 4 teilbar, es ist ein Schaltjahr, es sei denn:
  - Das Jahr ist durch 100 teilbar, es ist KEIN Schaltjahr, es sei denn:
    - Das Jahr ist auch durch 400 teilbar. Dann ist es ein Schaltjahr.

### Beispiele

- `is_leap(2000)` sollte `True` zurückgeben.
- `is_leap(1900)` sollte `False` zurückgeben.
- `is_leap(2016)` sollte `True` zurückgeben.
- `is_leap(2019)` sollte `False` zurückgeben.

Punkte: 20
