# node-setup

Mit diesem Projekt können Sie testen, ob Node bei Ihnen installiert ist und funktioniert.
Machen Sie das unbedingt rechtzeitig vor der ersten Übungseinheit, damit Sie eventuelle
Probleme beheben und wir in der Übung gleich starten können.

## Node installieren

Installieren Sie eine aktuelle Version von [Node.js](https://nodejs.org/en/download/) auf
Ihrem Computer. Die Versionen `12.x` und `14.x` sind in Ordnung.

Führen Sie die folgenden Kommandos aus um zu prüfen ob sowohl `node` als auch `npm`
installiert sind. Die Versionsnummern können bei Ihnen variieren:

```
markus@fh:~$ node -v
v12.21.0
```

```
markus@fh:~$ npm -v
7.6.0
```

## Projekt klonen

Sie können entweder dieses Projekt klonen oder herunterladen und auf Ihrem Gerät entpacken.

Im Projektverzeichnis (in dem auch `index.js` liegt) starten Sie den Server: 

```
node index
```

Wenn alles funktioniert erhalten Sie eine ähnliche Ausgabe:

```
markus@fh:~/swd/node-setup$ node index
Server running at http://127.0.0.1:3000/

```

Rufen Sie [http://127.0.0.1:3000/](http://127.0.0.1:3000/) im Browser auf. Wenn Sie eine
Erfolgsmeldung sehen hat alles funktioniert und Sie sind bereit für die erste Übungseinheit!

## IDE installieren

Damit Sie Ihren Code nicht im Texteditor tippen müssen empfiehlt es sich auch eine IDE wie zum Beispiel 
[vscode](https://code.visualstudio.com/) oder [Webstorm](https://www.jetbrains.com/webstorm/) zu installieren.
