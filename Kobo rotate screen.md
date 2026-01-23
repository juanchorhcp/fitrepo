Enable Landscape mode in Clara HD, Clara 2E, and Nia.

A. Modify the Kobo eReader configuration file. You may need to use a PC to set it up.

1. Connect your Kobo eReader to your computer
    
2. Navigate to KoboeReader/.kobo/Kobo (activate view the hidden item on Windows Explorer)
    
3. Open the file "Kobo eReader.conf" (use text application software like Notepad or Notepad++)
    
4. Find [DeveloperSettings] and set the texts as the following code. If it does not exist, then create it.
    

[DeveloperSettings]
ForceAllowLandscape=true

5. Disconnect your kobo from your PC and reboot it.

[![Comment Image](https://preview.redd.it/increasing-font-size-of-footnote-preview-v0-qd143kul96id1.jpeg?width=993&format=pjpg&auto=webp&s=24b16b8302ee777d7d477bf9fdc35fc36f01fb19)](https://preview.redd.it/increasing-font-size-of-footnote-preview-v0-qd143kul96id1.jpeg?width=993&format=pjpg&auto=webp&s=24b16b8302ee777d7d477bf9fdc35fc36f01fb19)

You may need to install [NickelMenu](https://www.mobileread.com/forums/showthread.php?t=329525&highlight=nickel+menu) to have a command to orientate mode from portrait to landscape mode.

The code for Nickelmenu is as follows:

menu_item :main     :LANDSCAPE - handle above   :nickel_orientation :landscape
menu_item :main     :LANDSCAPE - handle below   :nickel_orientation :inverted_landscape
menu_item :main     :PORTRAIT - handle on left  :nickel_orientation :inverted_portrait
menu_item :main     :PORTRAIT - handle on right :nickel_orientation :portrait