# MySQL DB zum Experimentieren

Einfaches Projekt um eine MySQL Datenbank zum Ausprobieren zu haben, ohne MySQL auf dem eigenen Rechner installieren zu müssen.

Starten kann man die Datenbank mit `docker-compose up`

Alle *.sql Dateien, die im db Unterverzeichnis liegen werden automatisch ausgeführt.
Die Datenbank wird in data auf dem Host angelegt um persistent zu sein. Wenn man alles frisch haben will, kann man das Unterverzeichnis leeren.

Die Datenbank startet auf Port 4306 (statt 3306), das Passwor des Root Benutzers ist `gtp3eAE4CzMcxnYNXTRh`, beides ist im docker compose File konfiguriert.

Als Werkzeug um mit der Datenbank zu interagieren kann man [MySql Workbench](https://www.mysql.com/de/products/workbench/) verwenden.
