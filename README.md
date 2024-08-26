

![Logo pokemon](International_Pokémon_logo.svg.png)
# <p class="text-center">Readme Quel Pokémon es-tu ?</p>

## <p class="text-center">Informations générales</p>

> Une application révolutionnaire !
- Alexandre Bobbera
- 26-08-2024
- Micsi 2022-2


[Accédez à l'application ici !](http://127.0.0.1:8080/ "Acceder à l'application")


## <p class="text-center">Tuto pour l'installation locale</p>

1. Télécharger et dézipper le dossier de l'application : [Télécharger QuelPoke](https://storage.googleapis.com/quelpoke/quelpoke.zip)
2. [Télécharger et installer Google Lang (Win64)](https://go.dev/dl/go1.23.0.windows-amd64.msi)
3. Modifier la ligne 35 du fichier "main.go" :  <br>
        addr := env("ADDR", "0.0.0.0") <br>
    par addr := env("ADDR", "127.0.0.1")
4. Ouvrir Powershell, accéder au dossier quelpoke et taper la commande go build main.go
5. Executer le fichier "main.go" qui s'est crée dans le dossier "quelpoke"
6.  [Accéder à l'application QuelPoke Télécharger QuelPoke](http://127.0.0.1:8080/)


contact : alexandre.bobbera@viacesi.fr 
