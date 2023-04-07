# UNO-UNkiOsk-ARChonis-Public-

PLEASE READ
YOU NEED TO BE ABLE TO ADD UNPACKED EXTENSIONS FOR THIS TO WORK
THAT OR YOU NEED TO HAVE A PRE-INSTALLED UNPACKED EXTENSION BEFORE UR SCHOOL DISABLED IT

Steps
Go to this link https://assesmentblocker.tedisc00l.repl.co/
Follow the instructions there

Manual Steps for people with the site blocked
Get the extensionID of the app you want to unkisok
paste it into the id box in https://robwu.nl/crxviewer/
Click "view extension source"
Click download in the top-right corner
Extract the zip file
Remove the kiosk only line from manifest.json
Replace all instances of .isKioskSession with .hasOwnProperty('isKioskSession')
Upload it in chrome://extensions

If it doesnt work please double check you did it right
If it still doesnt work, give me the extension id and ill try and do it manually and upload a prebuilt onto the site

Its great for running kiosk apps without enrolling after you shimmed, or just to not have to sign out to use kiosk apps in general(if extension uploading us unblocked)

Credits
PiKATchu (me, making it)
Sneej (testing)
Bypassi (.hasOwnProperty('isKioskSession') and testing)
