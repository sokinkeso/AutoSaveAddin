# AutoSaveAddin
![image](https://github.com/sokinkeso/AutoSaveAddin/assets/113173954/c2d641ad-687a-46c7-be17-f2a153f94730)

AutoSave addin provides automatic saving, with the ability to choose a time interval, confirmation and Auto-load.
The button, that added on the toolbar, has two functions:
- Enable/Disable the Autosave functionality (with Click)
- Show addin settings (with Double-click)


*** INSTALLATION: ***
-----------------
To install this addin in TwinBasic, just unzip and copy each architecture dll in the corresponding folder
\twinBASIC_IDE_BETA_xxx\addins\win32\
\twinBASIC_IDE_BETA_xxx\addins\win64\ 


*** Release History ***
-----------------
2023-11-30
------------- BETA 1
Features:
- automatic saving
- choose a time interval
- choose interval type (seconds or minutes)
- Confirmation before save
- Auto-Load on project open/new
- Logging in the debug console
- toolbar button single click: Enable or Disable the addin
- toolbar button double click: Show Settings window



2023-12-2
------------- BETA 2
- Fixed: Addin checks if project has any changes before saving
- Enchancement: Addin checks if the project is new and shows notification for the First-time-save.
- Added: New setting, Keep Log in Debug Console 
- Enchancement: Start enebled, now has also the option to ask the user
- Change: option buttons replaced with comboboxes
- Change: checkbox for StartEnabled replaced with combobox
- Added: Tab control for General and Project settings
- Added: Project settings option


2024-3-24
------------- Version 2.1.23
*** Known issue: in x64 the settings window is not staying on top of the IDE
- Fixed: Project settings option is now working
- Fixed: Project settings only saved after first manually save
