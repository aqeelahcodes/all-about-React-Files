# All-About-React-Files

The folder and file structure of your React project
README.md: .md indicates the file is a markdown file. This means it’s designed to be easy to write using any generic text editor and easy to read in its raw form. A lot of source code projects come with a README.md file that gives instructions and useful information about the project. Pushing your projects to GitHub will enable a README file to be display information on the repositories. 
 
node_modules/:  This folder displays all the node packages installed via npm automatically when you create a project. Don’t touch this folder.

package.json: : This file shows you a list of node package dependencies and other project configurations.

package-lock.json: This file indicates npm how to break down all node package versions. Don’t not touch this file.

.gitignore: This file displays all files and folders that shouldn’t be added to your git repository when using git, as such files and folders should be located only in your local project. The node_modules/ folder is one example. It is enough to share the package.json file with others, so they can install dependencies on their end with npm install without your entire dependency folder.

public/: This folder holds development files, such as public/index.html. The index file is displayed on localhost:3000 when the app is in development or on a domain that is hosted elsewhere. The default setup handles relating this index.html with all the JavaScript from src/.

In the beginning, everything you need is located in the src/ folder. The main focus lies on the src/App.js file which is used to implement React components. It will be used to implement your application, but later you might want to split up your components into multiple files, where each file maintains one or more components on its own.

Additionally, you will find a src/App.test.js file for your tests, and a src/index.js as an entry point to the React world.
There is also a src/index.css and a src/App.css file to style your general application and components, which comes with the default style when you open them.
