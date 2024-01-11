# Containers
Dit is de code voor het runnen van de API server op een container waardoor de database uitgelezen kan worden.
De backend zorgt ervoor dat de database wordt gevuld met data en haalt ook data op uit de database door de Get request en dit dan om te zetten in SQL queries.
De Database container runt de database in mysql.
Proxy container zorgt ervoor dat van buiten of deze service bereikbaar is vanaf port 8081.
