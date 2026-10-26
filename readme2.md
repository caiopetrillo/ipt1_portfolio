## 1 · Git und GitHub verstehen

1. Was ist Git?
Ein Versionsverwaltungssystem, das Änderungen an Dateien lokal speichert und nachvollziehbar macht.

2. Was ist GitHub?
Eine Online-Plattform, die Git-Repositories hostet und Zusammenarbeit ermöglicht (z. B. Pull Requests, Issues).

3. Was ist der wichtigste Unterschied zwischen Git und GitHub?
Git ist das Werkzeug, GitHub ist der Online-Dienst, der darauf aufbaut.

4. Funktioniert Git auch ohne GitHub?
Ja, Git läuft komplett lokal. GitHub ist nur eine Möglichkeit zum Hosten.

5. Was ist ein Repository (Repo)?
Ein Projektordner inklusive der gesamten Versionsgeschichte.

6. Was ist der main-Branch?
Der Hauptzweig eines Repos, der die stabile, aktuelle Version enthält.

7. Was ist Markdown?
Eine einfache Textauszeichnungssprache zum Formatieren, z. B. mit # für Überschriften und **fett**.

8. Was bedeutet GitHub-Flavoured Markdown (GFM)?
GitHubs Erweiterung von Markdown, u. a. mit Tabellen, Aufgabenlisten und Code-Blöcken.

## 2. Github Flow

9. Bringe die Schritte in die richtige Reihenfolge
Issue → Branch → Commit → Pull Request

10. Was ist ein Issue?
Eine Aufgabe, ein Fehler oder eine Idee, die im Repo dokumentiert und besprochen wird.

11. Was ist ein Branch?
Ein separater Entwicklungszweig, in dem man Änderungen unabhängig vom main-Branch machen kann.

12. Warum arbeitet man für eine Änderung häufig auf einem eigenen Branch?
Damit main stabil bleibt und Änderungen getrennt entwickelt und geprüft werden können.

13. Was ist ein Commit?
Ein gespeicherter Stand der Änderungen im Repo, der in der Historie festgehalten wird.

14. Wozu dient eine Commit-Nachricht?
Sie beschreibt kurz, was geändert wurde und warum, damit andere es nachvollziehen können.

15. Was ist ein Pull Request?
Eine Anfrage, die Änderungen aus einem Branch in einen anderen (meist main) zu übernehmen.

16. Was bedeutet Review?
Andere prüfen die Änderungen im Pull Request und geben Feedback oder Freigabe.

17. Was bedeutet Merge?
Das Zusammenführen der Änderungen eines Branches in einen anderen Branch.

18. Wann sollte ein Pull Request gemergt werden?
Wenn die Änderungen geprüft und freigegeben sind und keine Konflikte oder fehlgeschlagenen Tests mehr bestehen.

## 3. Wichtige Git-Begriffe und Befehle

19. Was bedeutet Push?
Lokale Commits werden ins Online-Repository (z. B. GitHub) hochgeladen.

20. Was bedeutet Pull?
Neue Änderungen aus dem Online-Repository werden geholt und ins lokale Repo übernommen.

21. Was ist der Unterschied zwischen Commit und Push?
Commit speichert Änderungen lokal, Push lädt diese Commits ins Online-Repo hoch.

22. Was ist der Unterschied zwischen Pull und Pull Request?
Pull holt Änderungen auf deinen Rechner. Ein Pull Request ist eine Anfrage auf GitHub, Änderungen in einen anderen Branch zu übernehmen.

23. Was bedeutet Clone?
Eine komplette Kopie eines Online-Repositories auf den eigenen Rechner herunterladen.

24. Was macht git status?
Zeigt, welche Dateien geändert, hinzugefügt oder noch nicht committet sind.

25. Was macht git add?
Fügt Änderungen zur Staging Area hinzu, damit sie committet werden können.

26. Was ist die Staging Area?
Ein Zwischenbereich, in dem man Änderungen sammelt, die im nächsten Commit enthalten sein sollen.

27. Was macht git log?
Zeigt den Verlauf aller Commits an.

28. Was bedeutet Branch wechseln?
Zu einem anderen Branch umschalten, um dort zu arbeiten (z. B. mit git switch oder git checkout).

29. Speichert git add bereits eine neue Version?
Nein, es merkt Änderungen nur für den nächsten Commit vor. Erst git commit speichert die Version.

30. Speichert git push deine noch nicht committeten Dateiänderungen?
Nein, Push lädt nur bereits committete Änderungen hoch.

## 4. Github-Flow praktisch erklären
31. Erkläre den GitHub-Flow in einem kurzen Satz.
Man legt für eine Aufgabe einen Branch an, committet dort die Änderungen, öffnet einen Pull Request und mergt ihn nach dem Review in main.

32. Ordne die Begriffe zu

Bedeutung	Git-/GitHub-Begriff
Aufgabe	Issue
Arbeitszweig	Branch
Speicherpunkt	Commit
Änderungsantrag	Pull Request
Zusammenführen	Merge

33. Welche Richtung beschreibt Push?
Vom lokalen Repository zum Online-Repository (GitHub).

34. Welche Richtung beschreibt Pull?
Vom Online-Repository (GitHub) zum lokalen Repository.

35. Warum sind mehrere sinnvolle Commits oft besser als ein einziger riesiger Commit?
Sie sind übersichtlicher, leichter zu prüfen und man kann einzelne Änderungen gezielt nachvollziehen oder rückgängig machen.

36. Nenne ein Beispiel für eine gute Commit-Nachricht.

Füge Login-Formular zur Startseite hinzu

37. Warum ist die Commit-Nachricht update wenig hilfreich?
Sie sagt nicht, was geändert wurde oder warum, daher ist die Historie schwer nachvollziehbar.


## 5. Markdown und Readme

38. Überschrift Ebene 1

# Git und GitHub Lernsession
39. Ungeordnete Liste

- Repository
- Branch
- Commit
- Pull Request
40. Link
[GitHub](https://github.com)

41. Bild
![Git-Logo](https://git-scm.com/images/logos/downloads/Git-Logo-2Color.png)

42. Inline-Code

Mit `git status` sieht man, welche Dateien geändert wurden.
43. Codeblock

```bash
git status
git add .
git commit -m "Füge Login-Formular hinzu"
git push
```
44. Was sollte ein gutes Portfolio-README mindestens leisten?
Es erklärt kurz, worum es im Projekt geht, was man damit machen kann und wie man es startet oder nutzt. Dazu gehören ein klarer Titel, eine kurze Beschreibung und eine Anleitung zur Installation oder Nutzung.

## 6. Lerhnachweis

Was habe ich heute über Git und GitHub gelernt?
Ich habe gelernt, was Git und GitHub sind und worin sie sich unterscheiden. Außerdem kenne ich jetzt den GitHub-Flow (Issue, Branch, Commit, Pull Request, Review, Merge) und die wichtigsten Befehle wie git status, git add, git commit, git push und git pull.

Was habe ich heute praktisch umgesetzt?
Ich habe Markdown-Syntax angewendet (Überschriften, Listen, Links, Bilder, Inline-Code und Codeblöcke) und Commit-Nachrichten formuliert.

Meine konkrete Verbesserung aus dem Selbst- oder Peer-Check
Ich schreibe meine Commit-Nachrichten jetzt klarer und aussagekräftiger, statt nur “update” zu verwenden.

Mein nächster Portfolio-Schritt
Ich lege ein Repository für mein Portfolio an und schreibe eine README mit Titel, Kurzbeschreibung und Anleitung.

## 7. Abschlusskontrolle

- [x] **Einführung in GitHub**: Übung, Modulbewertung und Zusammenfassung abgeschlossen
- [x] **Effektive Kommunikation auf GitHub mithilfe von Markdown** abgeschlossen
- [x] Ich habe meinen Lernfortschritt / meine Modulbewertung kontrolliert.

## 8. deutsche merkhilfe begriffe

Issue:	Aufgabe / Problemmeldung
Branch:	Arbeitszweig
Commit:	Speicherpunkt
Push:	Hochladen
Pull:	Herunterladen / Aktualisieren
Pull Request:	Änderungsantrag
Review:	Prüfung
Merge:	Zusammenführen
Clone:	Kopie herunterladen
Repository:	Projektordner mit Verlauf

## 9. Selbstcheck
Meine checkliste:
- [x] Ich kann **Git** und **GitHub** unterscheiden.
- [x] Ich kann **Issue** → **Branch** → **Commit** → **Pull Request** → **Merge** erklären.
- [x] Ich kenne den Unterschied zwischen **Commit** und **Push**.
- [x] Ich kenne den Unterschied zwischen **Pull** und **Pull Request**.
- [x] Ich kann Überschriften, Listen, Links, Bilder und Codeblöcke in Markdown verwenden.
- [x] Mein README wird auf GitHub korrekt gerendert.
- [x] Ich habe mindestens eine konkrete Verbesserung umgesetzt.
- [x] Ich habe meine Änderung mit einer aussagekräftigen Commit-Nachricht dokumentiert.
