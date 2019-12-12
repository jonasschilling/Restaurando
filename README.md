##restaurando
Web Programmierung DHBW Ravensburg WWI118

##Dokumentation
Die Web-Applikation ermöglicht dem Nutzer einen Tisch in einem der Partner-Restaurants in 
verschiedenen Städten zu reservieren.

####Technologies
Die Web-Applikation verwendet folgende Technologien:
The web-application uses the following technology stack:

- HTML, CSS, Javascript
- Frameworks (client-side): Bootstrap
- PHP 
- MySQL Database
#####Vorbedingungen und Installation
Die folgenden Vorbedingungen werden ben�tigt um die Website erfolgreich zum Laufen zu bringen:

1. 	xampp installieren
2. 	Apache und MySQL-Server �ber xampp Control Panel starten
3.	Backend vorbereiten
		1.	Apache Document-Root und Directory auf Projektpfad umstellen:
		2.	Bei xampp >> Apache >> Konfig >> Document-Root (Zeile 252) auf Projektpfad (z.B. "C:/users/*username*/git/restaurando") und Directory (Zeile 253) auf Projektpfad �ndern.
		3.	Apache Server stoppen und neu starten
		4.	Bei xampp >> MySQL >> Admin
			(Browser mit phpmyadmin �ffnet sich)
			Datenbank erzeugen: phpmyadmin >> SQL >> *SQL-Datei database_restaurando.sql aus dem github repository einf�gen*
		5.	phpmyadmin neu laden
		6.	restaurando Datenbank wurde angelegt
		7.	Datens�tze einf�gen: phpmyadmin >> SQL >> *SQL-Datei values.sql aus dem github repository einf�gen* (evtl. m�ssen die Datens�tze pro Tabelle separat eingef�gt werden)
3.	Im Browser *localhost* eingeben --> man sollte jetzt auf die Startseite (index.html) geleitet werden (alternativ auch xampp >> Apache >> Admin)
