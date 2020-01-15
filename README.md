# csgo-scripts
Location for My CS:GO Scripts

### Feel free to use/modify any of my code. 
## Table of Contents
* How to use .cfg  files in CS:GO
* Sample Autoexec File
* My Autoexec.cfg
* Practice.cfg
* Crosshair Files



## How to use .cfg files in CS:GO
Starting to use .cfg files in CS:GO can be confusing at first. Either follow the written instructions down below or watch [this video](https://example.com) to get started.
### 1: Finding your .cfg folder
Open **Steam > Library**, navigate to your **Library**, then find **CS:GO**.
Then right-click on CS:GO and click **"Properties"**.
Go to the **"Local Files"** tab and click **"Browse Local Files"**
Open the folder named **"csgo"** and then the folder named **"cfg"**.
Take any of the files you download from this repository, and stick them in this folder.
### 2: Running a .cfg script in-game
To run a .cfg file, you first need to enable the console.
To do that, open CS:GO, go to **Settings** > **General** >** >
Once you have the console enabled, press the **tilde ("~")** key, located below **Escape** and above **Tab**, to open the console.
Then type: 
```
exec 'cfg filename' 
```
You don't need to include the .cfg when typing in the filename.
Then press **Enter**, and your script will run.

### 3: Telling Steam how to automatically execute your autoexec
If you are lazy like men and don't want to do the above step every time you load up CS:GO, there is a way to automatically have your .cfg file execute.

Open **Steam > Library**, navigate to your **Library**, then find **CS:GO**.
Then right-click on CS:GO and click **"Properties"**.
Then, under the **General** tab, click **Set Launch Options**.
In the box, type
```
+exec 'cfg filename' 
```
Then click **"OK"**, and your autoexec file will run everytime CS:GO starts up.
