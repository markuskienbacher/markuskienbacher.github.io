# markuskienbacher

# im terminal:
in das src verzeichnis wechseln
> cd src
dort dann ausfürhen:
> hugo server

browser öffnen
http://localhost:1313


# zum deploy dann

cd src
hugo -Fv

# git commit



# setup
choco ruterladen und installieren (admin-shell)
https://chocolatey.org/install

> Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

> choco install git.install -y

> choco install hugo-extended -y

