# WeatherScrape
> Tutorial project

## Stručně se pokusím vysvětlit jak funguje script:

 - Na začátku skriptu jsou importovány potřebné knihovny. _**"BeautifulSoup"**_ se používá pro parsování HTML kódu webových stránek, _**"requests"**_ pro získání obsahu stránky a _**"schedule"**_ pro plánování pravidelných úkolů (opakování) a _**"time"**_ funkce pro práci s časem.
    - Vypíše se název Scriptu v podobě ASCII.
    - Funkce "get_weather": Tato funkce získává aktuální počasí pro zvolenou lokalitu České Budějovice. 
        - _**Teplota**_: Získá data o teplotě.
        - _**Rychlost větru**_: Získá data o rychlosti větru.
        - _**Srážky**_: Získá data o srážkách.
        - _**Bio zátěž**_: Získá data o bio zátěži.
        - _**Tlak vzduchu**_: Získá data o tlaku vzduchu.
    - Při spuštění skriptu, aby uživatel viděl aktuální počasí se spustí _**"get_weather"**_.
    - Spuštění každých 5 minut: Následuje plánování pravidelné aktualizace počasí každých 5 minut.
    - Nakonec je spuštěn nekonečný cyklus, který provádí plánované úlohy.
    - Program lze přerušit pomocí _**Ctrl + C**_.


## Pokud to nejde instalujte:
### První krok
```
1. python.exe -m pip install --upgrade pip
```
### Druhý krok
```
2. pip install beautifulsoup4
```
### Třetí krok
```
3. pip install requests
```
### Čtvrtý krok
```
4. pip install schedule
```
### Pátý krok
```
5. pip install time
```
## Linux
```
$ sudo apt-get update & upgrade -y
```
```
$ sudo apt-get install python3-pip
```
