# Photopea-Windows 

This is a simple Windows Applcation for [Photopea](https://www.photopea.com/). It was made in [nativefier](https://www.npmjs.com/package/nativefier) and then tweaked by hand.

It works exactly like the browser version does. You need to be online to load the application, but once the application is loaded, you can disconnect from the Internet. The app can function without an active internet connection if it has been cached. 

Download '[Photopea-Win](https://github.com/spooknik/Photopea-Appimage/releases/download/1.2.0/Photopea_1.2.0.AppImage)', and run the exe. You can run 'install.bat' as admin to install everything to your programs files. 

If somethings goes wrong or doesn't look right inside the app, delete %AppData%/Roaming/photopea-nativefier-*. This is the cache folder location for the app. 

**Known Issues**
- Closing the window when an unsaved document is open does not do anything. All documents must be closed or saved to exit the program. (Possibility a problem with Electron, will check when 5.0 is released.)

![App Image](https://raw.githubusercontent.com/spooknik/Photopea-Appimage/master/app.png)
