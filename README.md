## Changelog
21.05.2020  
- edited the example mod to show all initialization phases  
- added a try-catch structure in the logger, so that it would throw an error in case `Managed/Mods` folder was missing  
- included `Vanilla` and `Output/Mods` folders for less hassle on the users' part  
- other minor changes to folder structure  
  
## RFD's notes  
- currently checking how to use the in-game console for the log  
- SetEnvVar troubles - mention it in the notes  
  
## parts of original readme:  
  
Building the API is fairly straightforward.  
  
1. Clone this!  
2. Go to `%BlasphemousGameInstallPath%/Blasphemous_Data/Managed/` and copy it's contents to the `Vanilla` folder in this repository.  
3. Open the solution in Visual Studio 2017 or Rider (You can also just use msbuild/xbuild) --RFD's note: check out the other options  
4. Set the build configuration to Debug and build. --RFD: that is the default configuration  
5. The patched assembly should be in `%RepoPath%/Output/`  
6. Copy the files in this folder to `%BlasphemousGameInstallPath%/Blasphemous_Data/Managed/`  
