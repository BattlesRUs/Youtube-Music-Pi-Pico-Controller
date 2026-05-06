# Youtube-Music-Pi-Pico-Controller

This project makes use of a Raspberry Pi Pico, an OLED screen and buttons in order to control and display data from a youtube music website. The screen is constantly updated with song name, artist, and a moving playbar showing the time into a song, and duration of a song. It also includes a skip/rewind symbol and pause/unpause for vanity. The buttons were coded to match keyboard strokes in order to rewind/pause/skip through songs in youtube music. This allows for a mini, off computer controller of music. 


This python script is used as a bridge between the Raspberry Pi Pico and Youtube Music in a chrome browser. For this code to work, you need to install the most recent chromedriver.exe and place it in a folder you know the folder path to. In addition, you have to check Device Manager in order to find the port used on your computer and replace the PICO_PORT variable with the specified port. Lastly, chrome needs to be launched in "debugger mode” allowing for these remote scripts to access data inside websites. This is done through cmd prompt and entering the following: 

"[C:\Program Files\Google\Chrome\Application\chrome.exe]" --remote-debugging-port=9222 --user-data-dir="C:\ChromeDebug"

(replacing the highlighted [] portion with a specific folder path to your chrome.exe file)


