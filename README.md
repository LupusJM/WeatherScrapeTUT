# WeatherScrape
> Tutorial project

## I'll try to briefly explain how the script works:

 - At the beginning of the script, necessary libraries are imported. _**"BeautifulSoup"**_ is used for parsing the HTML code of web pages, _**"requests"**_ for fetching the content of a page, _**"schedule"**_ for scheduling regular tasks (repetitions), and _**"time"**_ functions for working with time.
    - The script's name is printed in ASCII.
    - Function _**"get_weather"**_: This function retrieves the current weather for the chosen location, České Budějovice.
        - _**Temperature**_: Retrieves temperature data.
        - _**Wind Speed**_: Retrieves wind speed data.
        - _**Precipitation**_: Retrieves precipitation data.
        - _**Bio Load**_: Retrieves bio load data.
        - _**Air Pressure**_: Retrieves air pressure data.
    - Upon running the script, the user will see the current weather by executing _**"get_weather"**_.
    - Running every _**5 minutes**_ (modifiable): Follows the scheduling of regular weather updates every 5 minutes.
    - Finally, an infinite loop is initiated to execute the scheduled tasks.
    - The program can be stopped using _**Ctrl + C**_.


## If that doesn't work, install:
 First step
```
python.exe -m pip install --upgrade pip
```
 Second step
```
pip install beautifulsoup4
```
 Third step
```
pip install requests
```
 Fourth step
```
pip install schedule
```
 Fifth step
```
pip install time
```
## Linux
```
$ sudo apt-get update & upgrade -y
```
```
$ sudo apt-get install python3-pip
```
