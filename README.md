# Windows
For Windows you can use the AddFriends.exe

# Linux
Install python
Arch = `pacman -S python`
Debian = `apt install python`
Download the Gecko Driver for Linux from `https://github.com/mozilla/geckodriver/releases`
Extract the geckodriver executable into the same directory as the main.py
run the script with `python "./main.py"`

# Additional Information
In the IgnoreList you can add ID's to be ignored in the script. Add each ID on a new line in the `IgnoreList.txt`
In the Phrases list you can add the phrases which are send when sending a friend request. The script will select a random line, using it's content as the message that's send as the reason why you want to add the other person.
