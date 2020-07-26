#Ender 3 Config's

##Cura
##### cura profiles
​Cura 4.5 https://www.chepclub.com/cura-profiles.html


##Marlin 2.0
My settings for Marlin 2.0 for Ender 3 with bltouch and dragon /v6 hotend

##### redit ender 3 Marlin guide
https://www.reddit.com/r/ender3/comments/e894j7/marlin_20x_guide_for_ender_3_using_skr_mini_e3_v12/


##### explane build Chris's Basement
https://www.youtube.com/watch?v=ACkxT2uvYO4&lc=UgyKKHEjRZVjHNwHA6t4AaABAg.98Hgr3blmfT98L2lQKKURT


##### Build
open Vscode Marlin2.0 folder as root folder
platformio.ini has all the settings ready.
Go to project tasks and hit <u>Build</u>
When build succesfull next step


#####copy firmware to board
Copy "marlin2.0\.pio\build\STM32F103RC_btt_512K\firmware.bin" to sdcard


####power up printer 
Printer will load firmware and you ready to go



