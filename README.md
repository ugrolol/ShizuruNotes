# ShizuruNotes
An unofficial Android tool application of the game "Princess Connect Re:Dive".  

# Forked for myself just to add english and russian
(was about to add ru first but it would take time to translate while english is somehow usable just with pasting keys and some editing) В основном ориентирован на перевод на англ потому что русские не качают приложения с гитхабов и смысл пропадает

# Part for those as me who dont know anything about coding but want to make changes or make app work
How to make your own apk
just if you somehow find out this fork and want to make apk with en( if original still dont have it) open android studio open File> new > project from version control > git url https://github.com/ugrolol/ShizuruNotes/ clone

then build your apk if you dont need to make any changes build > build bundle/apk > build apk

then there would be popup click locate or you can manually open it your project path\ ShizuruNotes\app\build\outputs\apk\debug so its basically working debug version

# If you want to add another language
folders with languages basically looks like ShizuruNotes\app\src\main\res\values\strings.xml or ShizuruNotes\app\src\main\res\values-en\strings.xml

open default values\strings there should be default pop up on top in adnroid studio that you can use translate editor open it then press add locale add w/e locale you need it would generate xml of that locale and folder

in default strings.xml under key string-array name="setting_language_options" add your languages

also if you want to chill together you may add me on discord UgroPnz#4246

## Requirement
* Android 8+  
> If you are locating in Chinese mainland, it is highly recommend you to set ShizuruNotes and system download manager to go through your proxy software since there are some **INTERESTING** reasons that you may get holy terrible connection speed to Github while ShizuruNotes try to connect Github to fetch update information every time it is launched.

## Build
Require Android Studio 4.0 or later.
Dependents could be found in `./app/build.gradle` and it might be changed time to time.

## Features
* Chara 
* Chara Derivative Status
* Clan Battle Boss
* Dungeon 
* Equipment 
* Drop Search
* Event Boss
* Event Calendar
* Event Notification 
* Rank Comparison  

## Localization
Japanese, Chinese, Korean, English supported.  
Korean strings are provided by [applemintia](https://twitter.com/_applemintia).  
English strings are provided by [southrop](https://github.com/southrop).  

## References
ShizuruNotes is highly inspired by the following repos:
* [PrincessGuide](https://github.com/superk589/PrincessGuide)
* [redive_master_db_diff](https://github.com/esterTion/redive_master_db_diff)
* [DereHelper](https://github.com/Lazyeraser/DereHelper)

## Related projects
* https://github.com/ugrolol/ShizuruNotes The EN and RU version of this application, developed by [ugrolol](https://github.com/ugrolol). 
* [KasumiNotes](https://github.com/HerDataSam/KasumiNotes) The KR server version of ShizuruNotes, developed by [HerDataSam](https://github.com/HerDataSam).  

## Contact
If you have any suggestions or find some bugs, feel it easy to contact me on Twitter Vibbit[@L8102259](https://twitter.com/L8102259). 

## License 
ShizuruNotes is licensed under the Apache License 2.0. 
