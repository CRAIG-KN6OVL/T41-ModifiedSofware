# T41-ModifiedSofware
Added a Menu item to the T41EEE.6 code to set the Teensy's System Clock and RTC.
Three (3) files were updated to make this change: SDT.h, MenuProc.cpp, and T41EEE.ino
The changes are: 1) updated SDT.h to allow 14 memu items ===>  #define TOP_MENU_COUNT 14   2) updated T41EEEino to add "Time" to the main menu 3) updated MenuProc.cpp to process the menu item "Time" and submenus, then setting the system clock and RTC in lines 299 thru 359 .
