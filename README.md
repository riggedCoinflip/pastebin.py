# pastebin.py
A script that transforms your clipboard into a pastebin link

requires:  
pip install pyperclip  
autohotkey

You need to set up your DEV-KEY by going on https://pastebin.com/api#1
If you would like to link the pastebins to your account, you need to get your USER_KEY as well. Execute generate_user_key(user_name, password) with your login details to do that.

The autohotkey script allows your code to automatically run whenever you press [CTRL] + [SHIFT] + C  
You can change it how you like, potentially add the script to your startup.  
The .ahk and .py have to be in the same folder.

If everything is set up, you can:  
1.[CTRL] + C - Copy your text to clipboard
2.[CTRL] + [SHIFT] + C - Transform your clipboard into the link  
3.[CTRL] + V - Paste the link to the person you want to share your text with
