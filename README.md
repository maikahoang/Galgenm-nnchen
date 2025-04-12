# Galgenm-nnchen
01 Projektbeschreibung
Bei Galgenmännchen denkt sich ein Spieler ein Wort mit mind. fünf Buchstaben aus und gibt der Mitspielerin nur an, aus wie vielen Buchstaben das Wort besteht. Die Mitspielerin soll das Wort erraten. Dazu kann sie entweder einen Lösungsversuch machen oder einen Buchstaben nennen.
Nennt sie einen Buchstaben, trägt der Spieler an allen Stellen des Lösungsworts diesen Buchstaben ein. Ist der Buchstabe nicht enthalten, so wird dies als Fehlversuch gezählt. Auch ein falscher Lösungsversuch wird als Fehlversuch gezählt. Das Spiel endet, sobald die Mitspielerin das Lösungswort erraten hat oder die maximale Anzahl von Fehlversuchen erreicht wurde.
Implementiere das Spiel so, dass du gegen den Computer sowohl als Spieler als auch als Mitspielerin spielen kannst. Dabei soll der Computer als Spieler auf eine Wörterbuchdatei zugreifen und daraus ein Wort auswählen. Als Mitspielerin soll der Computer Wörter basierend auf einer geeigneten Strategie und seinem Wörterbuch erraten.

02 Funktionalitäten
2 Spielmodi: Spieler vs. Computer oder Computer vs. Spieler
maximal 8 Fehlversuche
Zugriff auf Wörterbuchdatei

03 Projektplanung
Startseite: Auswahl zwischen Spieler vs. Computer oder Computer vs. Spieler
Spiellogik: Spieler denkt sich ein Wort aus/Computer wählt ein Wort aus der Wörterbuchdatei aus --> Anzahl der Buchstaben wird vorgegeben --> Raten verschiedener Buchstaben --> bei nicht vorhandenem Buchstaben/Wort wird dies als Fehlversuch gewertet (max. 8 Fehlversuche), bei erfolgreichem Erraten wird Buchstabe/Wort an richtigen Stellen aufgedeckt

Spieler vs. Computer: Spieler errät ein Wort, welches vom Computer ausgewählt wurde
Computer vs. Spieler: Computer errät ein Wort, welches vom Spieler ausgewählt wurde

benötigt eine Wörterbuchdatei, in der alle Wörter angezeigt werden die vorher schon erstellt wurden und neue hinzugefügt werden können

Programm kann beendet werden

04 Ausführliche Beschreibung der Spiellogik
- unterschiedliche Buchstaben haben unterschiedliche Wahrscheinlichkeiten in einem Wort aufzutauchen --> Buchstaben mit höherer Wahrscheinlichkeit (z. B. Vokale) werden zuerst geraten
- Implementation von deutschen Grammatikregeln (z. B. nach dem Buchstaben Q folgt ein U)

