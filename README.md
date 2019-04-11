# Photopea-Windows 

This is a simple Windows Applcation for [Photopea](https://www.photopea.com/). It was made in [nativefier](https://www.npmjs.com/package/nativefier) and then tweaked by hand.

It works exactly like the browser version does. You need to be online to load the application, but once the application is loaded, you can disconnect from the Internet. The app can function without an active internet connection if it has been cached. 

Download '[Photopea-Win](https://github.com/spooknik/Photopea-Windows/releases/download/1.0/Photopea-Win.zip)', and run the 'Photopea.exe'. For a more permanent  install, consider moving the whole folder to program files.  

If somethings goes wrong or doesn't look right inside the app, delete %AppData%/Roaming/Photopea. This is the cache folder location for the app. 

Also see: [Photopea-Appimage](https://github.com/spooknik/Photopea-Appimage) for Linux.

**Known Issues**
- Closing the window when an unsaved document is open does not do anything. All documents must be closed or saved to exit the program. (Possibility a problem with Electron, will check when 5.0 is released.)

![Screenshot](https://raw.githubusercontent.com/spooknik/Photopea-Windows/master/Screenshot.JPG)
