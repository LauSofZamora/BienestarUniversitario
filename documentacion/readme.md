# Visualizar diagramas UML

## Opcion 1

Para visualizar los diagramas puede ingresar en el [servidor online](https://www.plantuml.com/plantuml/duml/SyfFKj2rKt3CoKnELR1Io4ZDoSa70000) Esto le proporciona un servidor en tiempo real donde debe copiar el código del archivo que desee visualizar.

## Opcion 2

Puede ser visualizado también en visual studio code.
ve al partado de extensiones, luego en el buscador de extensiones se puede buscar directamente por `plantuml` o si necesitas ayuda puedes ver [PlantUML](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml).

### Instalacion de dependecias

#### En Windows

Abre el cmd.exe como administrador y ejecuta el comando

```Powershell
@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
```

Luego te permitirá usar un gestor de aplicaciones llamado choco, este es necesario para poder ejecutar el comando

```Powershell
choco install plantuml
```

#### En Mac

```Mac
brew install --cask temurin
```

```Mac
brew install graphviz
```
