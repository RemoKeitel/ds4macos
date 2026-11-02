# CLAUDE.md – ds4macos (Fork von Remo Keitel)

Projektnotizen für Claude. Mit Remo auf Deutsch; Datumsangaben absolut,
Entscheidungen mit „(Remo, TT.MM.JJJJ)“.

## Abhängigkeiten

- **JoyConSwift** (Fork `RemoKeitel/JoyConSwift`, Branch `master`) als
  Rückfall-Implementierung für den Switch Pro Controller; Weiterentwicklung im
  Branch `joyconswift` dieses Repos.
- SwiftAsyncSocket (Fork `RemoKeitel/SwiftAsyncSocket`, `master`).

## Offene Punkte

- **Switch Pro Controller wird nicht überall erkannt** (Remo, 02.11.2026):
  Auf dem MacBook Air M4 funktioniert er in ds4macos, auf dem Mac mini M2
  nicht – obwohl er auf beiden erfolgreich gekoppelt ist. Über JoyConSwift
  geht er immer. Ursache noch unbekannt, muss herausgefunden werden.
  Bis dahin nutzt Remo joy4macos (arbeitet nur über JoyConSwift), um die
  Bewegungsdaten zu bekommen.
