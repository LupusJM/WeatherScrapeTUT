# WeatherScrape

Stručně se pokusím vysvětlit jak funguje script:

 - Na začátku skriptu jsou importovány potřebné knihovny. BeautifulSoup se používá pro parsování HTML kódu webových stránek, "requests" pro získání obsahu stránky a "schedule" pro plánování pravidelných úkolů (opakování).
    - Vypíše se název Scriptu v podobě ASCII.
    - Funkce "get_weather": Tato funkce získává aktuální počasí pro zvolenou lokalitu České Budějovice. 
        - Teplota: Získá teplotu ze stránky.
        - Rychlost větru: Získá informace o rychlosti větru.
        - Srážky: Získá informace o srážkách.
        - Bio zátěž: Získá informace o bio zátěži.
        - Tlak vzduchu: Získá informace o tlaku vzduchu.
    - Při spuštění skriptu, aby uživatel viděl aktuální počasí se spustí "get_weather".¨
    - Spuštění každých 5 minut: Následuje plánování pravidelné aktualizace počasí každých 5 minut.
    - Nakonec je spuštěn nekonečný cyklus, který provádí plánované úlohy.
    - Program lze přerušit pomocí Ctrl + C.


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
#Linux#
    $ sudo apt-get update & upgrade -y
    $ sudo apt-get install python3-pip
