# 📚 Lernmappe

Ein übersichtliches Lernprogramm im Browser – organisiert wie ein Ordner mit Mappen pro Fach.

## Starten
- **Mit KI:** die Claude-Version öffnen: https://claude.ai/artifact/KpjuAw9rxfXrsMKE8KCybG. Deine Daten werden dort privat in deinem Claude-Konto gespeichert.
- **Ohne KI, offline:** `index.html` im Browser öffnen (Doppelklick).

## Aufbau
**Fach → Mappe → Lernzettel / Karteikarten**

Fächer: LK Geschichte, LK Politik, LK Englisch, P4 Mathe, P5 Deutsch, Biologie, Sport, Kunst

## Funktionen
- **Prüfungs-Countdown** auf der Startseite (Tage/Std/Min/Sek), Restzeit auch in der Seitenleiste und im Fach. Prüfungen unter „⏳ Prüfungen“ eintragen, ändern, löschen.
- **✨ KI** (in der Claude-Version):
  - in einer Mappe „Mit KI erstellen“: Lernzettel und/oder Karteikarten zu einem Thema, optional aus eingefügtem Unterrichtsmaterial
  - im Lernzettel: überarbeiten, aufs Wichtigste kürzen (mit Rückgängig), Karteikarten daraus erstellen, Fragen stellen
  - im Kartensatz: weitere Karten vorschlagen
- **📎 Dateien in Mappen:** PDF, Word (.docx), Fotos (JPG/PNG) und Textdateien hochladen – per Klick oder Drag & Drop. Text wird automatisch ausgelesen (durchsuchbar). Daraus mit ✨ einen Lernzettel **zusammenfassen** oder den Inhalt vollständig **übernehmen** lassen; Fotos und eingescannte PDFs liest die KI direkt („Text erkennen“ schreibt sie ab). Textdateien gehen auch ohne KI als Lernzettel.
- **🧩 Quiz-Generator:** aus Lernzetteln (und Dateien) automatisch Multiple-Choice-, Lückentext- und Wahr/Falsch-Fragen erzeugen. Sofortiges Feedback mit Erklärung, Lückentext tolerant bei Tippfehlern, Ergebnisverlauf, falsche Fragen wiederholen oder als Karteikarten speichern. Tasten: 1–4, W/F, Enter.
- **🧠 Erklär-Modus (Feynman-Methode):** Reiter „Erklären“ im Lernzettel. Thema (ganzer Zettel oder ein Abschnitt) in eigenen Worten erklären – tippen oder sprechen – und die KI zeigt: gut erklärt, Lücken, Fehler, zu ungenau, Rückfragen und einen Prozentwert.
- **⏱ Probeklausur:** KI erstellt eine Klausur im Stil echter Oberstufenklausuren (Operatoren, AFB I–III, Punkte, ggf. Material) mit Zeitlimit. Abgabe automatisch bei Zeitablauf, handschriftliche Lösungen per Foto möglich. Danach Bewertung nach Erwartungshorizont mit Punkten pro Aufgabe, Notenpunkten und Lerntipps.
- **Mappen** pro Fach anlegen, umbenennen, löschen (z. B. „Q1 – Weimarer Republik“)
- **📄 Ansicht** jedes Lernzettels als ganze Seite wie ein PDF (weißes A4-Blatt) und **⬇ Als PDF speichern** (echte A4-PDF-Datei)
- **Lernzettel** bearbeiten mit Live-Vorschau und einfacher Formatierung:
  - `# Überschrift`, `## Unterpunkt`
  - `**fett**`, `*kursiv*`, `==markiert==`, `__unterstrichen__`
  - `- Liste`, `1. Aufzählung`
  - `> Merksatz` (wird als 💡-Merkkasten dargestellt)
  - Tabellen: `| Jahr | Ereignis |`
- **Karteikarten** mit Lernmodus: umdrehen (Leertaste), „gewusst“ (2) / „nicht gewusst“ (1).
  Nicht gewusste Karten kommen in derselben Runde erneut dran; danach „Nur Ungewusste“ wiederholen.
- **Suche** über alle Fächer, Mappen und Inhalte
- **Zuletzt bearbeitet** auf der Startseite
- **Hell-/Dunkelmodus**, auch auf dem Handy nutzbar

## Daten & Sicherung
Alles wird automatisch im Browser gespeichert (localStorage) – nur auf diesem Gerät und in diesem Browser.
Über **⬇ Export** eine Sicherungsdatei (`.json`) speichern und mit **⬆ Import** wieder laden,
z. B. um auf ein anderes Gerät zu wechseln. Regelmäßig exportieren empfohlen!
