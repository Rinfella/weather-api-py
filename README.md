# Python CLI Weather Tool.
- This Python CLI tool uses OpenWeather API.
- You need OpenWeather account if you don't have one.
- Copy the API key from your OpenWeather account.
- Store the API key in the root directory of your project in a file called `secrets.ini`.
- The file must be structured like this:

```
; secrets.ini file
[openweather]
api_key=<YOUR_API_KEY_HERE>

```
- The rest you can modify on your own.
- To test, you can run `python weather.py`.
- This tool is created using Python 3.12.
- You may use `python3` instead of `python` like so:


```
python3 weather.py London -i 

```
- The script can accept two arguments: city name and imperial flag.
- You can pass the city name as an argument, followed by `-i` or `--imperial` to show the temperature in in imperial units.
- If you don't pass the imperial flag, metric units will be used to display the temperature.
