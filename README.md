# codenames-pictures
Online codenames picture game

Make sure to install node.js<br/>
Download PuTTY as well (not necessary, but it is what I use to start the game)

Modify codenames_start.bat file<br/>
Provide the appropriate SSH credentials to talk to this server. Point the path to the txt appropriately.

Modify codenames_start.txt file<br/>
Provide the proper "cd" to the location of the served game. Point to the server folder of this repo.

You can replace any image files you would like, remove existing images, or add your own images by placing them inside client/img/ folder and making sure the file names are continuous from 1 to whatever the total number of images is. Any missing file numbers will show up as blanks in the game. All image files are 300px * 300px. After changing the image folder, you will need to tell the server how many images there are. Modify server/server.js line 27: var num_images = 281; to whatever number you have.
