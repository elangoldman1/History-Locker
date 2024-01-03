# History-Locker
Google Chrome extension to block access to browser history

Your browser history is a private place. What you look up is no one's business but yours(and the government and all those sites that track you :) ). Have you ever wanted to let someone use your computer or Google account, but were worried about them looking at your internet history? Well, worry no more! Just follow these steps and you're good to go:
    
    1. Open Terminal(for Mac) or Command Prompt(for Windows)
    2. Input the command: git clone https://github.com/elangoldman1/History-Locker.git
    3. Go to chrome://extensions
    4. Click "Load Unpacked"
    5. Make sure the extension is turned on(if it says "Errors", ignore it. Those aren't relevant for our purposes)
    6. Bask in the comfort of privacy!

While the extension is on, if you check your Chrome history at chrome://history, it will redirect to a page with a button that says "Click me and many secrets you shall see". If you click the button, you will be redirected to a 10-hour-long YouTube video that constantly replays Rick Astley's "Never Gonna Give You Up". 

If you want to view your history, just turn off the extension. Now, you might say that anyone who uses your computer can just turn off the extension and look at your history. That's true, but the majority of people won't even think to do that! If you want to make it even more secure, just rename the file from "History-Locker" to something unrelated. This way, even if they think it's an extension, they won't know which one it is. 

If you want to change which website the button redirects to:

    1. Go to the file "temp.js"
    2. Replace the current link on line 6 with your link of choice
    3. Save the changes in the file
    4. Go to chrome://extensions
    5. Under the "History-Locker" extension, press the reload button
