### Playdate VSCode/XCode Template for c language (Mac)

## XCode Project setup

1. Open project build settings (not target)
2. Search for PLAYDATE_SDK_PATH
3. Replace its content with your PlaydateSDK path
4. Open Makefile
5. Find the ```PRODUCT = HelloWorld.pdx``` statement
6. Replace "HelloWorld" with your project name, leaving pdx extension
7. Edit the PlaydateCTemplateSimulator scheme
8. Switch to arguments tab
9. Locate argument "${PROJECT_DIR}/HelloWorld.pdx"
10. Replace "HelloWorld" with your project name

## VSCode Project setup
1. Open Makefile
2. Find the ```PRODUCT = HelloWorld.pdx``` statement
3. Replace "HelloWorld" with your project name, leaving pdx extension
4. Open the ```.vscode/launch.json``` file
5. Locate the ```"${workspaceFolder}/HelloWorld.pdx```
6. Replace "HelloWorld" with your project name
