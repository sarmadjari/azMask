This is a forked project from [clarkio/azure-mask](https://github.com/clarkio/azure-mask) to make it work with Microsoft Edge Browser

# azMask
This is a browser extension that will do its best to find and mask GUIDs (such as Subscription IDs), email addresses, keys, and connection strings with a blur. The intention of the extension is to make it easier to do screen recordings without revealing sensitive, personal, account information that may show up on screen. It will only run and apply against Azure portal URLs.

![screen shot](azure-mask-screen-shot.png)

## Features

* Blurs GUIDs (such as Subscription IDs)
* Blurs your account email
* Hides the "Report a Bug" button (if found)
* Toggle the mask on/off and store this state
* Apply the mask (if enabled) after Document Object Model (DOM) mutations
