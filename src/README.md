# website anleitung

## website ändern

code öffnen
immer bei oeffnen code !!!

kreissymbol anklicken ganz unten links neben master damit es synchronisiert ist falls josy/valentino was geändert hat

### config der ganzen seite (zb menü)

nur den src aendern!!
mit den md dateien arbeiten die im ordner content sind
config.toml (wenn ich was grundlegendes an der Menüführung ändern will)



## zum ausprobieren von änderungen ohne dass es auf website ist

falls terminal nicht offen oben auf reiter terminal


in das src verzeichnis wechseln (check ob nicht bereits dort)

```
cd src
hugo server
```

browser öffnen
http://localhost:1313


## zum onlineschalte auf der website

```

cd "C:/Users/kieni/OneDrive - Schule für Sozialbetreuungsberufe/website2020/markuskienbacher.github.io/src" (falls noch nicht drinnen)

hugo -Fv

```
(hugo -Fv: ist der website generator)

damit es auf website ist

wieder vs code aufrufen

source control (baum klicken) 
änderungen benennen


checkbox (hackerl klicken) bei markuskienbacher- 
save all and comitt bestätigen
änderungen abwarten 

dann "sync changes" klicken 

jetzt müsste es auf website sein



## git einrichten neuer arbeitsplatz /neuer PC

```
cd ~
md repos
cd repos


git clone https://github.com/markuskienbacher/markuskienbacher.github.io.git --recurse-submodules
git config user.name "NAME"
git config user.email "email"

oder:
git clone --recursive https://github.com/markuskienbacher/markuskienbacher.github.io.git
git submodule update --init --recursive
git submodule update --recursive --remote

 choco install hugo-extended --version=0.101.0 -y

```

## für bilder

* bilder kopieren
* in src static images
* open containing folder
* reinkopieren
