# palmweboseclipseplugin
This repo contains the old plugins provided by HP/Palm for legacy webOS Development on Eclipse IDEs,
The correct Eclipse IDE for it is the Eclipse IDE for Javascript Web Developers

## Install Instructions
1. Download the older version of the Eclipse IDE [Here](https://www.eclipse.org/downloads/packages/release/indigo/sr2/eclipse-ide-javascript-web-developers), the correct one is the Eclipse IDE for Javascript Web Developers, you need the Eclipse version 3.5.2 or later but i selected the 3.7.2 version
2. After you unzip the Eclipse zip file that you downloaded, open Eclipse and put a workspace location when asked
3. To install the plugins, go to Help -> Install New Software, then go to the Location field, put this url https://raw.githubusercontent.com/DavidModPhone/palmweboseclipseplugin/main/site.xml, select the Palm webOS SDK Group, accept the Terms and Conditions, install the plugins and restart Eclipse when prompted
4. After the install, to get the webOS Eclipse Interface go to Window -> Open Perspective -> Other... -> webOS and you are ready to go



![installPlugin1](https://raw.githubusercontent.com/DavidModPhone/palmweboseclipseplugin/main/readmeimgs/installplugin.png)
![installPlugin2](https://raw.githubusercontent.com/DavidModPhone/palmweboseclipseplugin/main/readmeimgs/installplugin2.png)


![windowOption](https://raw.githubusercontent.com/DavidModPhone/palmweboseclipseplugin/main/readmeimgs/windowperspective1.png)
![windowOption2](https://raw.githubusercontent.com/DavidModPhone/palmweboseclipseplugin/main/readmeimgs/windowperspective2.png)


**Have fun playing with the plugins!**

## Small Changes to do after the installation
1. To see the Numbers on the left screen when you are editing go to Window -> Preferences -> General -> Editors -> Text Editors and tick the "Show line numbers" option, after that click Apply and close the preferences menu


![optionScreen1](https://raw.githubusercontent.com/DavidModPhone/palmweboseclipseplugin/main/readmeimgs/linenumberoptionscreen0.png)
![optionScreen](https://raw.githubusercontent.com/DavidModPhone/palmweboseclipseplugin/main/readmeimgs/linenumberoptionscreen.png)


---
2. If you want to import your existing palm webOS app projects, go on your app project folder, create a new file named ".project", then open any text or code editor and put this piece of code
```xml
<?xml version="1.0" encoding="UTF-8"?>
<projectDescription>
	<name>(Name of your project)</name>
	<comment></comment>
	<projects>
	</projects>
	<buildSpec>
	</buildSpec>
	<natures>
		<nature>com.palm.pdt.nature</nature>
	</natures>
</projectDescription>
```
Then open Eclipse, Go on File -> Import -> General -> Existing Projects into Workspace then select your palm webOS app projects folder by clicking the Browse Button and then finalize the import process and there you go

![optionScreen2](https://raw.githubusercontent.com/DavidModPhone/palmweboseclipseplugin/main/readmeimgs/importproject1.png)
![optionScreen3](https://raw.githubusercontent.com/DavidModPhone/palmweboseclipseplugin/main/readmeimgs/importproject2.png)
![optionScreen4](https://raw.githubusercontent.com/DavidModPhone/palmweboseclipseplugin/main/readmeimgs/importproject3.png)


## Purpose of this repo
All of the things this Repo does is to archive an old Eclipse Plugin that Palm/HP made for developing webOS Apps Much easier on Eclipse IDEs, no copyright infringement nor commercial purposes is intented, this is only meant to archive the plugins.
