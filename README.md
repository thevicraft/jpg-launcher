# Java-Pixel-Game Launcher

+ This is a universial Launcher for the **[Java-Pixel-Game](https://github.com/thevicraft/java-pixel-game)**
+ Please consider (as with the original game too) that due to danger of plagiarism **I will not upload the source code**.
![launcher_start](https://user-images.githubusercontent.com/80700279/232238373-c98c3f91-0ce3-4d99-9626-7310c8df1253.png)

### Download
+ If you wish to download the Launcher, you can do this in the [Releases](https://github.com/thevicraft/jpg-launcher/releases).

## Information

+ The **Java-Pixel-Game Launcher** is coded in **Java** and requires Java on your machine.
+ Therefore you must install the Java Runtime Environment (JRE).
+ A version higher or equal to Java 8 is recommended.
+ To report issues go [here](https://github.com/thevicraft/jpg-launcher/issues).

### Directories
- The Launcher manages a directory control.
- All game files are located in the user folder according to the operating system
- For example:

> - Windows: *C:\Users\yourname\java-pixel-game*
> - Linux: */home/yourname/java-pixel-game*

- In the game folder a certain architecture is built:

**launcher**
- In this folder configurations and the profiles' data are stored. Both configurations are written in *JSON-format*.
 - Additionally you will find a file called *launcher-last.log*. It stores the last log of the launcher. Each launcher restart resets the file.

**profiles**
- In this folder you will find all relevant game files according to the selected version.
- Each profile has its own folder titled with its own name.

**versions**
- Here all versions can be found. They are stored as executable *JAR-files* that you can download from [GitHub](https://github.com/thevicraft/java-pixel-game/releases).


### Launcher profiles
- You can create Launcher profiles for different versions. Every profile is stored in another directory, in order to avoid a mix-up.
- In the *Profiles* section of the Launcher, you can create new profiles, or edit existing profiles.

![launcher_profiles](https://user-images.githubusercontent.com/80700279/232238371-ba152e53-4039-4f26-b8df-2e1ffc5c669c.png)

- For a better look and feel *icons* can be added to each profile; you can select one of the 17 template icons.
- To fulfill that purpose, a *user-friendly* profile maker has been made.

![profile_maker](https://user-images.githubusercontent.com/80700279/232238368-6c7376a8-1b9a-4560-a1d6-974c33358df7.png)

> - The default profile **Latest.Version** can neither be edited nor deleted. 

#### Unofficial versions
- If for any reason an unofficial version exists, that you downloaded and now want to play, you can put the version into the *versions* folder in the game directory.
- After a launcher restart, you will be able to select this version in the versions list.

> - It is not guaranteed that the version will work and the launch of it is **always** at your **own risk**!
> - The version **must be** an *executable JAR-file*!

- In the profile creator or profile editor you can select between a default path or a custom path.
- The default path will **always** be in a folder titled with the same name as the profile itself. This folder will be in the *profiles* folder.
- A custom path can be *wherever* you want it to be. In order to work it must have the default **read & write** permissions.

### Other
- When you have no valid internet connection, or the launcher is offline in general (when you have a valid internet connection but the launcher is still offline; in such a case, please contact the author!), your launcher is marked as *offline*.
- In such a case you are not able to launch new versions, that are not located in the *versions* folder.
- In fact the launcher will only recognize the versions that are located in the the *versions* folder.


## Author
+ [Java-Pixel-Game](https://github.com/thevicraft/java-pixel-game) and its Launcher have been coded by [thevicraft](https://github.com/thevicraft).
+ **Discord**: [here](https://discord.com/invite/pXDxjKB7q3)
+ **Youtube**: [here](https://www.youtube.com/channel/UCjiP-NZ-BqZiH9IlEW-shLw)

## Credits

+ Credits for the Game or the Launcher can be viewed in the *About-Page* of the Launcher program.

## License
+ It is **forbidden** to **spread** this Launcher under another name than the original author!
+ If you wish to share the Launcher, **credit the author** or link to this [github respository](https://github.com/thevicraft/java-pixel-game)!

[![Creative Commons License](https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-nd/4.0/) 

> This work is licensed under a [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](http://creativecommons.org/licenses/by-nc-nd/4.0/).
