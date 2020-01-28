Download this file;
Answer all questions;
Create new repository, push this file with answers and send me a like;

### 1. How to init NPM to new project?
	a. Instal node.js;
	b. In Command Line navigate to the root folder of project and enter $ npm init;
	c. Afterwards you will have package.json file in projects root folder;

### 2. How to install and save npm packages?
	a. npm install <package_name>

### 3. How to install webpack to your project and where to wright configurations?
	a. In Command Line navigate to the root folder of project and enter $ npm install --save-dev webpack;
	b. Write configurations - in webpack.config.js file;

### 4. How and where need to add webpack build and watch command?
	a. In Command Line navigate to the root folder of project and enter $ npm watch or $ npm build; 

### 5. How to specify entry point in webpack configuration?
	module.exports = {
  	entry: string,

	pvz: module.exports = {
	        entry: './src/index.js',

### 6. How to specify entry file output in webpack configuration?
	module.exports = {
          output: {
            filename: 'main.js',

### 7. How to specify entry file output path in webpack configuration?
	module.exports = {
	  output: {
            path: path.resolve(__dirname, 'public'),

### 8. How to create new repository in Github?
	In your Github account main window click Start a project -> in Create a new repository window fill up new repository name;

### 9. How to init GIT in project?
	a. In Command Line navigate to the folder where file is located.
	b. Type git init; 
	
### 10. How to add all changes/files to git index?
	Type git add . to add all files/changes to git index; 

### 11. How to commit message for new changes?
	Type git commit -m "Comment";

### 12. How to add remote URL to GIT project?
	git remote add name URL;

### 13. How to push changes to master?
	Type git push;