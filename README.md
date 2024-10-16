# Longfox115
userchrome theme for Firefox ESR 115 to make it look more like Longhorn Plex demo Internet Explorer. Intended to be used with ![Windows Longhorn Plex theme](https://github.com/valkalyne/demoplex).

![alt text](https://github.com/notzetkin/Longfox-Plexplorer/blob/master/image.png?raw=true)

![alt text](https://github.com/notzetkin/Longfox-Plexplorer/blob/master/image2.png?raw=true)

## Setup

Add contents of the /firefox folder to the directory your browser executable is installed in and the /chrome folder to your Firefox profile folder respectively. You can find your profile folder location in Help > More troubleshooting information > Profile folder.

## WHAT YOU NEED FOR THE THEME TO WORK:
1. ![Firefox 115.ESR natice controls patch](https://github.com/kawapure/firefox-native-controls) - CRUCIAL for the extended frames to work. AFTER patching xul.dll you need to change ``widget.ev-native-controls-patch.override-win-version`` parameter in ``about:config`` to ``7`` or ``8`` to spoof os version and enable extended frames.
2. Change ``browser.uiCustomization.state`` in ``about:config`` to ``{"placements":{"widget-overflow-fixed-list":[],"unified-extensions-area":["_3c078156-979c-498b-8990-85f7987dd929_-browser-action","_7a7a4a92-a2a0-41d1-9fd7-1e92480d612d_-browser-action","browsec_browsec_com-browser-action","firefox_tampermonkey_net-browser-action","_d10d0bf8-f5b5-c8b4-a8b2-2b9879e08c5d_-browser-action","jid1-niffy2ca8fy1tg_jetpack-browser-action","_1220100b-db8f-419f-9cd4-ed7a51cee7f3_-browser-action"],"additional_top_toolbar1":["urlbar-container","go-button","stop-reload-button"],"additional_top_toolbar2":["library-button","new-tab-button","customizableui-special-spring62","downloads-button","history-panelmenu","extensions-button","new-window-button","customizableui-special-spring67","customizableui-special-spring71","customizableui-special-spring69","customizableui-special-spring73","customizableui-special-spring75","customizableui-special-spring77","customizableui-special-spring79"],"configuration_toolbar":[],"nav-bar":["back-button","forward-button","home-button","find-button","email-link-button","customizableui-special-separator15","personal-bookmarks","customizableui-special-separator13","bookmarks-menu-button","unified-extensions-button"],"toolbar-menubar":["menubar-items"],"TabsToolbar":["tabbrowser-tabs","alltabs-button"],"PersonalToolbar":[]},"seen":["save-to-pocket-button","developer-button","activity_throbber","go-button","_7a7a4a92-a2a0-41d1-9fd7-1e92480d612d_-browser-action","browsec_browsec_com-browser-action","firefox_tampermonkey_net-browser-action","_d10d0bf8-f5b5-c8b4-a8b2-2b9879e08c5d_-browser-action","jid1-niffy2ca8fy1tg_jetpack-browser-action","_1220100b-db8f-419f-9cd4-ed7a51cee7f3_-browser-action","_3c078156-979c-498b-8990-85f7987dd929_-browser-action","extensions-button"],"dirtyAreaCache":["nav-bar","PersonalToolbar","toolbar-menubar","TabsToolbar","additional_top_toolbar1","configuration_toolbar","unified-extensions-area","additional_top_toolbar2"],"currentVersion":19,"newElementCount":86}`` to get the intended window layout.

## THEME IS CURRENTLY WORK IN PROGRESS, MORE IMPROVEMENTS COMING

big thanks to ![Valkalyne](https://github.com/valkalyne) and ![ThePhantom6314](https://ThePhantom6314) for help and longhorn plex ui resources
