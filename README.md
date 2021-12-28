# WhatsAppWrapped
This repo can be used to generate a Spotify Wrapped - style analysis of WhatsApp messages.

## Quick Start Guide
* Export chat from WhatsApp
* Launch notebook file in Jupyter Lab
* Ensure required files are in directory
* Change 'nameOfChat' value (first box!) to match the chat file name including the file extension.
* Run code, output will be in the 'Wrapped' and 'Full Wrapped' sections - the content is the same but 'Wrapped' shows each analysis area separately.

## Notes on Use  
* This is configured to look at messages from 2021 only.
* It has been tested on multiple chats with different group sizes/ number of messages/ use cases/ use times etc and doesn't appear to have any errors but this is no guarantee!
* Pull requests are welcome.
* Please ensure you have the consent of chat members before using. 

## Instructions for Use
### Dependancies
#### Libraries
Ensure that the following libraries are installed:
* pandas
* csv
* matplotlib
* seaborn
* datetime
* wordcloud
* collections
* emojis
* math
* operator
* nltk

#### Files
These should be in the same directory as the program file.
* 1-1000.txt [deekayen/1-1000.txt](https://gist.github.com/deekayen/4148741)
* EmojiOneColor.otf [emojione-color/EmojiOneColor.otf](https://github.com/adobe-fonts/emojione-color/blob/master/EmojiOneColor.otf)
* WhatsApp chat file. This should be as a .txt and exported without media.
