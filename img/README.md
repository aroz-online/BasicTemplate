# WebApp Icons

WebApp icons in ArozOS system is classified into 3 types

1. Desktop Icon  (desktop_icon.png)
2. Small Icon (small_icon.png)
3. Function Icon (function_icon.png, legacy)

**ALL ICONS must be in .png format**

### Desktop Icon

Desktop icon is an optional icon that you can include in the same directory as the small icon. The desktop shortcut created for this module will first check if you have a desktop icon. If no, it will use the small icon as shortcut icon instead.

### Small Icon

Small icon is a mandatory image icon for your webapp module. The path for the icon file is descripted in the init.agi script at your WebApp root folder. 

The small icon will be shown on everyplace including the start menu, float windows title bar and desktop (if no desktop icon is provided for your module)

### Functional Icon (Legacy)

Functional icon is the module title icon for ArOZ Online Beta grid menu. If you are not deciding to support the ArOZ Online Beta (which has been deprecated), you can safely ignore this icon file.



## PWA Icons

For PWA icons, see manifest.json for more information

