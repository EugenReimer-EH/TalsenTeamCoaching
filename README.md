# Installation
## Notepad ++
Search in google for Notepad++
- Open https://notepad-plus-plus.org/downloads/v7.9.5/
- Click on download
- Install Notepad++

## Git
- Search for Git for windows
- Open https://git-scm.com/download/win
- Download version 2.31.1
- install
- Next
- Next
- Next
- Next
- in setup wizart page "Choosing the default editor used by git?"
- select 'Notepad++'
- Next
- Next
- Next
- Next
- Next
- in setup wizart page "Choose default behavoir of 'git pull'?"
- select 'Rebase'
- Next
- Next
- Next
- Install
  Wait ...
  Finish

## Tortoise Git
- search for Tortoise Git
- open https://tortoisegit.org/docs/tortoisegit/tgit-dug-showlog.html
- click on 'Download'
- select 'Download TortoiseGit 2.12.0 - 64-bit (~19.6 MiB)'
- download
- install
- Next
- Next
- Next
- Next
- Install
- Finish (with selection 'Run first start wozard'
  
- First start wizart started
- Next
- Next
- Next
- in configuration wizard page "Configure user information'
- enter Name and Email
- !!!!!! *.rs (email that has access to Azure) !!!!!
- Next
- Finish

## Check out
- create foder C:\TalsenTeamCoachingSession_2  
- right click in folder, select 'Git clone...'
- enter URL 'https://github.com/EugenReimer-EH/TalsenTeamCoaching.git'
- click OK
- folder 'TalsenTeamCoaching' shoul be created
 
## React Js
- search for React js
- open https://reactjs.org/
- click 'Get started'
- in React.js open search and enter 'installation
- select 'Create a New React App'
- url 'https://reactjs.org/docs/create-a-new-react-app.html' will be opened
- read instruction, such as :
-  'You’ll need to have Node >= 10.16 and npm >= 5.6 on your machine. To create a project, run:'
- click on 'Node >= 10.16 and npm >= 5.6'

## Node js
- node js will be opened
-  https://nodejs.org/en/
- download LTS verstion by clicking on ' 14.16.1 LTS'
- download node
- istall NodeJs
- Next
- Accept EULA
- Next
- Next
- Next
- Next
- Install
  
- return to React.Js page
- open CommandPromt
- swicht directory to C:\TalsenTeamCoachingSession_2\TalsenTeamCoaching
- (cd /d C:\TalsenTeamCoachingSession_2\TalsenTeamCoaching)
- perform setup according to ReactJs web site
- as name of application select fdi-web-ui
- npx create-react-app fdi-web-ui
- Wait ~2-5 min (during installation serch for VS code)
- cd fdi-web-ui
- npm start
  
## Visual Studio Code 
- search for Visual Studio Code
- open https://code.visualstudio.com/
- start installation
- Accept EULA
- Next
- Next
- in configuration wizard page "Select Additional Tasks'
-    select:
-   Add "Open With Code ...
-   Add "Open With Code ...
-   enter Name and Email
- Next
- Install
- Finish
- On last page unselect "Launch Vidual Studio Code"
- Finich
## Strat React App  
- Return to Create-React-App script
- copy content of 'fdi-web-ui' to one level highter (!!! except file README.md and folder .git !!!)
- cd fdi-web-ui

- npm start
- For 'Windows Security Alert' allow "Public networks"
-  Allow Access
   
- in default browser opened ReactApp
- usually http://localhost:3000/
- select in WindowsExplorer folder 'fdi-web-ui'
- right click, select open with Code
- change color shema
- File -> Preferences -> Setting
- In search settings type "schemc"
- Set setting "Window: Auto detectColor Scheme"
- Move Side Bar right
- View -> Appearence -> Move Side Bar right
- Close settings
- Close Getting started
 
## Add header
- Open file XXXXX
- add textXXXXX
- Open file XXXX
- add text XXXXX
- !!! open README.md !!!
- write steps that others should make to get your changes

- in windows explorer open folder
- C:\TalsenTeamCoachingSession_2\TalsenTeamCoaching
- rights click selecte changed files
- write comment
- click Commit
- select 'Push'
 
- open Tortose Git
 
# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
