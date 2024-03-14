# WeatherScrape
> Tutorial project

## I'll try to briefly explain how the script works:

 - At the beginning of the script, necessary libraries are imported. "BeautifulSoup" is used for parsing the HTML code of web pages, "requests" for fetching the content of a page, "schedule" for scheduling regular tasks (repetitions), and "time" functions for working with time.
    - The script's name is printed in ASCII.
    - Function "get_weather": This function retrieves the current weather for the chosen location, České Budějovice.
        - **Temperature**: Retrieves temperature data.
	- **Wind Speed**: Retrieves wind speed data.
	- **Precipitation**: Retrieves precipitation data.
	- **Bio Load**: Retrieves bio load data.
	- **Air Pressure**: Retrieves air pressure data.
    - Upon running the script, the user will see the current weather by executing "get_weather".
    - Running every **5 minutes** (modifiable): Follows the scheduling of regular weather updates every 5 minutes.
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
