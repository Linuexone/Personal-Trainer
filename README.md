Personal-Trainer
================

#Spezifikationen (Ideen)
- Erstellen/Anmelden von Benutzeraccounts
- Profil Anlegen (Name, Alter, Grösse, Trainingsort, etc.)
- Trainings Eintragen (Datum, Dauer)
- Statistiken auswerten (Diagramm/Tabelle vergleichen)
- Das Ergebnis ausdrucken können, evt auch teilen (Sozial Media)
- Erinnerungs Benachrichtigung (via E-Mail -> Kalender)


#Die Profilseite

- Eine einfache übersichtliche Startseite, wo man sich mit seinen Accountdaten einloggt oder direkt einen neuen Account erstellen kann.

- Sobald man eingeloggt ist, gelangt man auf seine Seite, wo man ein Profil einrichten kann mit verschiedenen Werten, wie Name/Alter/Grösse/Trainingsort etc. was man später natürlich auch noch anpassen kann. 

- Weiter kann man auf seiner Profilseite, die Trainingsdaten eintragen (Datum/Dauer)

- Durch Eintragen mehrerer Trainings, wird es dann die Möglichkeit geben diese auszuwerten/vergleichen über Wochen, Monate, Jahr. (via. Diagramm/Tabelle)

- Man soll die Statistik ausdrucken können.

- Damit man die Trainings nicht vergisst einzutragen, wird man benachrichtigt. Die Zeit der Erinnerung kann man auf seinem Profil einstellen. (via Kalender)


Installationsanleitung
======================

- Der Gebrauch von virtualenv ist zu empfehlen!

- Im erstellten Projekt Ordner müssen wir nun Klonen:
	(Achtung!: Verzeichnispfad mit dem Befehl "pwd" herausfinden und hinter die Klone URL setzen!)

	git clone git@github.com:Linuexone/Personal-Trainer.git /Users/luginbuhl/Developer/Projects/Personal-Trainer

- Nach dem Klonen, die Requirements installieren:
	pip install -r requirements.txt

- Jetzt brauchen wir noch eine Datenbank:
	python manage.py createdb

- Zum starten vom Webserver braucht es folgenden Befehl:
	python manage.py runserver
