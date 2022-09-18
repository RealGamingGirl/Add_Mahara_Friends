# Windows
Install Python from `https://www.python.org/downloads/`
install selenium `pip install selenium`
Install Firefox Browser
move the `geckodriver.exe` to `C:\Geckodriver\`
run the script with `python "./main.py"` in your terminal

# Linux
Install python
Arch = `pacman -S python`
Debian = `apt install python`
Download the Gecko Driver for Linux from `https://github.com/mozilla/geckodriver/releases`
install selenium `pip install selenium`
change the `path` variable in the `./main.py` script to the path of your geckodriver
Install Firefox Browser
run the script with `python "./main.py"`

# Additional Information
In the IgnoreList you can add ID's to be ignored in the script. Add each ID on a new line in the `IgnoreList.txt`
In the Phrases list you can add the phrases which are send when sending a friend request. The script will select a random line, using it's content as the message that's send as the reason why you want to add the other person. Add each Phrase on a new line in the `Phrases.txt` file.
