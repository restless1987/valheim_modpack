# valheim_modpack
Valheim Modsammlung fuer die Jungs

## Automatische Updates

Ihr könnt wahlweise per Download des Zip-Archives (rechte Seite, Download -> `ZIP`).

Alternativ geht das per git-client ([download](https://git-scm.com/downloads)), anschließend ins Valheim-Directory gehen, rechtklick -> `open git here`.

Dann folgende Befehle in die Console eingeben:

```bash
# Hier richten wir das ganze EINMALIG ein:
git init && \
git remote add origin https://github.com/restless1987/valheim_modpack && \
git checkout main && \
git pull
```

Danach reicht ein Update einfach per `git pull` in dem Valheim-Verzeichnis.
