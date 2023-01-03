# Working mcreator for 1.8.9
A working version of mcreator for 1.8.9

## How to use
**It's a little confusing and alot of work to get your actual .jar file or to run as a client but here are the steps.**

1. Download the .zip file and extract it.
2. Extract the mcreator 1.8.9.zip but DO NOT delete it. If you do you must re-download
3. Go into it and start mcreator. I have manualy added forge so you don't have to worry about adding it. And I know, can't connect pylo servers. Also don't worry about all the console errors.
4. Next what you want to do it start to make you mod. Make sure you only use ONE workspace
5. When your mod is done press on export your mod to ZIP or JAR.
6. Save it in the saves folder that came with the zip file and make sure to name your mod and chose export as jar.
7. When you have exported it expect to see an error that's what we want. That was just to name the mod and generate files.
8. Next, press MC in the top left and press EXPORT CURRENT WORKSPACE TO ECLIPSE. Don't worry we are not using eclipse.
9. What you want to do now is press EXPORT CURRENT WORKSPACE TO MCR FILE and put it in the Saves file that came with the .zip file. You shoudld name it modNameV{version} e.g testModV1.9.mcr.
10. Ok so this is the confusing bit. Go into the forge folder within the mcreator 1.8.9 folder and either run xx buildClient.bat or xx runclient.bat. The xx is just so alphabetically it's at the bottom. 
11. Build client will build to  build/libs/yourJarFile.jar. The build folder will not generate untill you run the build client so don't worry that it is not there.
12. The Run Client, will, you guessed, run the client. It's as easy as that.
13. Note if you run both errors WILL occour.
14. Now, don't go and start, read on more. It's important.
15. When you have finished testing and want to make more changes you will noice a build error or other issues. That's cause building and running the client breaks the forge folder.
16. So delete the mcreator 1.8.9 folder. Yep. ALl of what you just made. Good job you saved. Right. I did say too.
17. So what you want to do now is extract the mcreator 1.8.9 folder again. And open it.
18. Press on IMPORT MCR FILE and use the .mcr file in the Saves folder. Btw you can now delete the .jar file in that folder (If it generated it might not of.)
19. Now follow steps 4 to 10 again.

**It seams like alot of steps only to have to do them all again every mod update. But when you get the hang of it it only takes about 30 seconds. Which I know is more work than just pressing one button, but it's better than learning all the code for something that does not even have offical forge documentation anymore. For multiple mods just copy the whole .zip folder over into another folder.**

## Some Info

**When you delete the mcreator 1.8.9 file you also are deleting all the minecraft data that you made if you ran the runClient.**

**If you want to change your minecraft settings in the runCient then it will revert to almost default(forge is not the default minecraft settings cause they suck). To prevent this manually set your settings in the mcreator 1.8.9 zip file so when you unachive it, it will set you what you want. I you don't know how to do that, get your options.txt from your .minecraft folder and put it in your mcreator 1.8.9/forge/run folder. It MUST be a 1.8.9 version settings tho otherwhise they will probably just reset.**

**You can manually edit the code by going to the src folder in the forge folder, but mod builders like this do things in weird ways because that's they way they work, so it will be hard to de-code or understand.**


**Im happy try to help anyone if they needs it but if it's just struggle folowing this then mabe consider not trying to program mods, because the older mcrator interfaces, this, is hard to understand for complete beginners.**

**Please tell me what I spelt wrong in here I rushed this, so, yeah.**
