FROM python:3.9-alpine3.17

#Fügt die app.py Datei unter dem Verzeichnis "provider" hinzu
ADD app.py /provider/ 

#Setzt das Arbeitsverzeichnis des Container auf "provider"
WORKDIR /provider/

#Ausführung der Datei app.py
CMD [ "python", "app.py" ]

