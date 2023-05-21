FROM node:16.18.0-alpine

#Setzt das Arbeitsverzeichnis des Containers auf "app"
WORKDIR /app/

#Kopiert die Dateien package.json und package-lock.json in das Verzeichnis des Containers.
COPY ["package.json", "package-lock.json*", "./"]
#Führt npm install im Container aus
RUN npm install
#Kopiert app.js in das Verzeichnis des Containers
COPY app.js .

#Bindet den Container an den Port 5000
EXPOSE 5000

#Ausführung der Datei app.js
CMD ["node", "app.js"]