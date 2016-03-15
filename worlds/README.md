###Minecraft worlds
Here are the Minecraft world files generated from postcodes submitted on the day. If you submitted a request and gave us your name then the world name will be your surname; if we didn't get your name, then the world is labelled using your postcode.

Each Minecraft world is made up of several folders and files, so they have been uploaded here in zip format. To get your world you need to download the zip file and unzip or uncompress it into your Minecraft <strong>saves</strong> folder.

####How to find the saves folder:

Launch Minecraft and select <strong>Play</strong>

Select <strong>Options</strong>

Select <strong>Resource Packs</strong>

Select <strong>Open Resource Packs Folder</strong>

This will open a File Manager or Finder window for a folder named <strong>resourcepacks</strong> - go up one level and you will see the <strong>saves</strong> folder in the containing folder (<strong>minecraft</strong>). This is where you want to put the unzipped world folder - move the whole thing over. Now relaunch Minecraft, select <strong>Single Player</strong> and you should see the name of your world appear in the list for you to choose.

####Contact
If you're not sure what to do with the files you get, or if you're not happy with them, let us know and we can try again with the same postcode (in case of glitches in the script) or with a different postcode if you want to try somewhere else.
Email lucy@datahatch.co.uk if you have any problems.


####Technical bits
All the code used to generate the worlds comes from the work of Chris Gutteridge at Southampton University; you can find it here: https://github.com/cgutteridge/geocraft if you want to know more about how it works. The worlds we've created for the Minecraft Discovery Day are all based on the standard script with a <strong>--hollow</strong> parameter added to make the strutcures hollow - so you can model your house inside and out if you want to! 

The script takes height data from Lidar and colour data from Open Street Maps, and assigns level + green = grass, level + blue = water, tall + grey = building, tall + green = tree. Buildings are rendered in red brick with light grey carpet tiles on the roof, and dark grey wool blocks are added wherever the script isn't totally sure which to choose.
