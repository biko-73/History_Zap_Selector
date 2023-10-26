# History_Zap_Selector

A small and useful plugin for switching channels from the viewing history.

<img src="https://i.ibb.co/QDftw7V/000.jpg" alt="000" border="0">

*** Use the "HELP" button on the RC on any of the skins to get help with available functions

- supported Python2/Python3
  
- Compatible with any architectures and images based on any version of Python, except VTi

- The plugin has been added to the main plugin menu of the image you are using

- added similar "selection" for DVB-S/S2/C/T/T2 serviceref in favorites bouquets
  
- improvement displaying the orbital position for srviceref OSCAM iCAM
  
- Added support for LCD skins. If your receiver has an LCD, then the information from the channel selection list will be duplicated on it
  
- On the "Info" page, an online translation of the event description into the GUI language of the Enigma2 image has been added
  
- Added translations for different locales

- The logic for deleting entries from the channel-switching history works by pressing the blue button:
"short press" - deletes the selected line from the channel-switching history
"long press" - clears channel-switching history

- Added a small pop-up log when searching for matching channel names.

-   Added functionality "default translation language for EPG event descriptions".
  If this setting is enabled, then the description of the EPG event on the channel will be translated automatically into the specified language when you click "EPG-Info".
At the same time, the translation functionality into any other language on the "EPG-Info" page remains available to you.
  
- Added custom skin "EPG-Info" to display information on the selected channel.
  In this skin, the channel name is formed as a “sequence” - Provider name (if found) - Bouquet name - Channel name
  On the "EPG-Info" page, the ability to "scroll through" program descriptions using the "Next"/"Previous" buttons on the "EPG-Info" page has been added.
  “Scrolling through” descriptions is available within those programs that are displayed as “Next” in the lower right corner of the skin ...
  The "yellow" button automatically returns to the description of the program at the current time
  Added the ability to change (set) the language for translating descriptions of EPG events...
  The setting is called up by long pressing the "green" button on the "EPG-Info" skin

- Added automatic saving/restoring of HistoryZap channel list during reboot, restart GUI, power on/off
p.s. automatic saving/restoring works even if you have never run the plugin...the history of channel switching from standard ChannelSelector will be saved

