# Launch Sublime Text 2 from the Mac OS X Terminal

## Installation for Cool Nerds:
copy and paste the following command into Terminal:
`cp /Applications/Sublime\ Text\ 2.app/Contents/SharedSupport/bin/subl ~/usr/bin/` <br/>


## Installation for Newbies:
Sublime Text 2 ships with a CLI called **subl** (not "sublime", because "subl" is much easier to type 500 times per day). This utility is hidden in the following folder (assuming you installed Sublime in `Applications` like typical folk:

Go to **"Applications" folder** in the Finder;<br/>
*right-click* on **"Sublime Text 2"** app icon;<br/>
*click* **"Show Package Contents"**;<br/>
Once inside, go into **"Contents"**;<br/>
then into **"SharedSupport"**;<br/>
then into **"bin"**;<br/>
There you will see the file **subl**;<br/>
Select **"subl"**, then *right-click*, select **"copy"**. Or *press* **"Command+C"**<br/>

####Once you have copied the "subl", then you will need to paste it in a special location. Continue following instructions below:####

In the Finder, navigate to your user top-level directory, commonly referred to as `~` (tilde character).<br/>
If you feel confident: while in the Finder, *click* **"Go"** at the top of the screen in the Menu Bar, then *select*  **"Go to Folder..."**<br/>
You can get there more quickly, while in the *Finder*, by using the *keyboard shortcut*  **"Command+Shift+G"**<br/>
*Type*  in **"/usr/bin"** and *hit enter*. Your Finder should now be in the *"~/usr/bin/"* folder with many files.<br/>
**Paste** that `subl` file right here, by *right-clicking* and *selecting*  **"Paste"**  or by *pressing*  **"Command+V"**



## Installation for Power Users:
Sublime Text 2 ships with a CLI called **subl** (not "sublime", because "subl" is much easier to type 500 times per day). This utility is hidden in the following folder (assuming you installed Sublime in `Applications` like typical folk:

**Goto Sublime Text 2 app icon and right-click to select "Show Package Contents"**<br/>
**Find `subl` file in SharedSupport folder**<br/>
**Copy this file into your ~/usr/bin/ folder**<br/>


## Testing

Important! You *may* have to restart Terminal for changes to take effect.
Open a Terminal window and run:

`subl filename` (replace "filename" by an actual file name)

or

`subl foldername` (replace "foldername" by an actual folder name)

or even

`subl .` (to open the entire current directory)

## Conclusion

Now you don't need to get out of Terminal to simply open a file or a folder, you didn't have to add an "alias" or yet another bin directory to your `.bash_profile` which you would have needed with the official instructions given by the Sublime team.

Have fun, Sublime is a great editor showing a lot of promise. 

##Recommendation: [install Package Control](https://github.com/CoderJoes/sublime_package_control).

