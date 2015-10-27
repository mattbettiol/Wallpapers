# Wallpapers
A neat method of keeping your wallpaper updated on a daily basis. This method uses a script created by [macearl](https://github.com/macearl/) that downloads images from [Wallhaven](http://alpha.wallhaven.cc/). It is required that you create an account on [Wallhaven](http://alpha.wallhaven.cc/) for this method to work.

__Downloading the Wallpapers__

1. Open    '[downloadWallpapers.sh](https://raw.githubusercontent.com/mattbettiol/Wallpapers/master/downloadWallpapers.sh)'    in your favorite [text editor](https://atom.io/).
2. Place your login credentials in the **USER** and **_PASS_** section for your account on [Wallhaven](http://alpha.wallhaven.cc/)
3. Change the **LOCATION=** paramater to where you would like to store the wallpapers each day
4. Change any other configuration option you'd like
5. Save your changes!
6. Open the [Terminal](https://en.wikipedia.org/wiki/Terminal_%28OS_X%29) app and type
`chmod +x /path/to/downloadWallpapers.sh`
 
__Creating the Application__

1. Open [application.txt](https://raw.githubusercontent.com/mattbettiol/Wallpapers/master/application.txt) in your favourite [text editor](https://atom.io/)
2. Change the _first_ **set currentTab** to match the path of your wallpaper directory
3. Change the _second_ **set currentTab** to match the path of the [downloadWallpapers.sh](https://raw.githubusercontent.com/mattbettiol/Wallpapers/master/downloadWallpapers.sh) file
4. Copy **all** of the code in this file
 
__Script Editor__

1. Open [AppleScript Editor](https://en.wikipedia.org/wiki/AppleScript_Editor)
2. Click ![New Document](https://raw.githubusercontent.com/mattbettiol/Wallpapers/master/newdocument.png) on the bottom left of the window
3. Paste the code that you have copied from before
4. Click on the ![wrench](https://raw.githubusercontent.com/mattbettiol/Wallpapers/master/wrench.png) button to compile your script
5. Go to the **File** menu and click **Save**
6. Copy these settings (or change them to meet your specifications):
	![AppleScript Editor](https://raw.githubusercontent.com/mattbettiol/Wallpapers/master/ase.png)

__Changing the Background__

1. Open **System Preferences**
2. Select **Desktop & Screen Saver**
3. Click the **+** button to add a new folder
4. Choose your Wallpapers directory
5. Tick the box that says **Change Picture** and select an interval that is suitable for you. I also ticked the **Random Order** box

__Running Automatically__

1. Open **System Preferences**
2. Click **User & Groups**
3. Click the **Login Items** tab
4. Click the **+** button to add a new application


