# website anleitung

## website ändern

code öffnen
immer bei oeffnen code !!!

kreissymbol anklicken damit es synchronisiert ist falls josy was geändert hat

### config der ganzen seite (zb menü)

nur den src aendern!!
config.toml

die "seiten:
im "content" = der Inhalt

## zum ausprobieren von änderungen ohne dass es auf website ist

im terminal: terminal starten von desktop leiste unten
in das src verzeichnis wechseln

```sh
cd src
hugo server
```

browser öffnen
http://localhost:1313


## zum onlineschalte auf der website

```sh

cd ~/Dokumente/website2020/markuskienbacher.github.io/src

hugo -Fv
das ist der website generator
```

damit es auf website ist

wieder vs code aufrufen

source control (baum klicken) 
änderungen benennen

checkbox (hackerl klicken) bei markuskienbacher- 
save all and comitt bestätigen
änderungen abwarten 

und dann links unten neben master auf Kreissymbol

jetzt müsste es auf website sein



## git einrichten neuer arbeitsplatz /neuer PC

```
git clone https://github.com/markuskienbacher/markuskienbacher.github.io.git --recurse-submodules
git config user.name "NAME"
```

## für bilder

* bilder kopieren
* in src static images
* open containing folder
* reinkopieren
