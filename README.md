# WhatsAppWrapped
This repo can be used to generate a Spotify Wrapped - style analysis of WhatsApp messages.

## Quick Start Guide
* Export chat from WhatsApp.
* Launch notebook file in Jupyter Lab.
* Ensure required files are in directory.
* Change the 'nameOfChat' value  to match the chat file name including the file extension.
* Run code, output will be in the 'Wrapped' and 'Full Wrapped' sections - the content is the same but 'Wrapped' shows each analysis area separately.

## Notes on Use  
* This is configured to look at messages from 2021 only.
* It has been tested on multiple chats with different group sizes/ number of messages/ use cases/ use times etc. and doesn't appear to have any errors but this is no guarantee!
* Pull requests are welcome.
* Please ensure you have the consent of chat members before completing analysis.

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

### Exporting the WhatsApp chat
Additional instructions can be found online if needed.
#### For iOS
* Go to WhatsApp.
* Click on the chat you wish to analyse to enter the messaging screen.
* Enter the Group Info section by clicking on the group name again.
* Scroll to the bottom.
* Press the 'Export Chat' button.
* Select 'Without Media'.
* Transfer the chat to your chosen analysis device.

#### For Android
TO DO

#### Additional Platforms
* It is not possible to export the chat from the Mac desktop app.
* It is not possible to export the chat from the web app.

### Running the program
* Install the required libraries.
* Download the required files (see above) and place them in the same directory as [the notebook](https://github.com/CorValBan/WhatsAppWrapped/blob/initial-implementation/WhatsAppWrapped_Notebook.ipynb) and the WhatsApp chat file.
* Launch Jupyter Lab. This can be installed [here](https://jupyter.org/install) if not already.
* Navigate to the directory.
* Open the notebook file.
* Replace the nameOfChat variable with the file name for the WhatsApp chat file.
* Navigate to the Run menu in Jupyter Lab and click "Run All Cells".
* Scroll to the bottom of the file to see the wrapped results. This may take some time to appear depending on the chat size.

### Trouble Shooting/ FAQ
#### The results haven't appeared
* Check whether the cells are still running. This is shown by a '[*]' being displayed to the left of the cell. When it has completed, it is replaced with '[n]' where n is a number.
* Check whether the graphs have saved to the directory.
* Check for any errors. This will be shown by a red error below the cell detailing the problem. Common errors include expected files not being present, the name of the chat file not matching and libraries not being imported correctly. Please feel free to create an issue for any programming errors/bugs.

#### It doesn't work on my machine?
* Due to lack of equipment, this has only been tested on one machine (2020 MacBook Pro with M1 chip). There *shouldn't* be any issues with other machines but please raise a pull request or an issue if there are. 
