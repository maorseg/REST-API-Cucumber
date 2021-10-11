# REST-API-Cucumber
REST API Cucumber project

Automation info structure for API tests (NO UI)

Key features:

- Works with latest node version v14.15.3 and up and npm version 6.14.9 and up and also with older versions e.g. v8/10

Quick Start:

- Clone the project/download zip
- Extract on any folder on your PC the downloaded automation.zip
- Open Visual Studio Code. From the file menu, Click on File → Open Folder and browse to the extracted automation folder and choose it to open
  e.g. C:\Code\MyPlayGround\REST-API-Cucumber-main\automation
  at the left bar of Visual Studio Code you should see the entire project struture
- Run "npm install" in Visual Studio Code terminal (ctrl + Shift + ~).it will install all required dependencies from package.json
- features folder: Write your own features and scenarios under features folder. I created many api demo feature files and sample scenarios 
- step_definitionss folder: Add new step definitions to implement your scenarios under step_definitionss folder
- You can run your tests by typing "npm run debug" in the terminal or run script "debug" in package.json
- To debug: place a breakpoint than press 'F5' or from menu Run → Start debugging
- Test results reported to report portal as you set them in rpConfig.json (by your own project TOKEN)
- After connected to Report Portal you can run your tests by typing "npm run test" in the terminal or run script "test" in package.json and the test
- results will appear in Report Portal
