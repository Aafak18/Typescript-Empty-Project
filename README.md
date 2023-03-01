# Typescript-Empty-Project
I have developed a TypeScript project which includes essential files such as tsconfig.json, package.json, and packagelock.json. The project comprises a source folder that contains an index.ts file that enables writing of TypeScript code. Once compiled, the resulting code will be located in the dist folder as an index.js file.

The purpose of this project is to assist individuals in downloading the project from GitHub and start working on it promptly, eliminating the need to spend time creating a project. To get started, simply download the project from GitHub and navigate to the project directory in your terminal, then run the following command: "npm install".

Upon executing this command, the package.json file in your project will be read and will install all necessary Node modules defined in the dependencies section.



## How this has done:
For TypeScript Environment:

Create a new folder and open it in VS Code.

Run "npm init -y" to create the package.json and package-lock.json files. Then add the following lines to the package.json file:

'''"type": "module",'''
after this line
'''"main": "index.js",'''

In the package.json file, add the following line to the scripts section:

'''"build": "tsc"'''

Install TypeScript and its dependencies by running "npm install typescript --save-dev".

Create a new folder named "src" and add a new file named "index.ts" to it.

If there is an error of "cannot find corresponding type declaration," type "npm i -D @types/nodes" in the terminal.

Create a new file named "tsconfig.json" in the root folder and add the following lines to it:

'''{
"compilerOptions": {
"module": "commonjs",
"moduleResolution": "node",
"target": "es2016",
"sourceMap": true,
"outDir": "dist",
"strict": true,
},
"include": ["src/**/*"]
}'''


git remote add origin https://github.com/Aafak18/empty_typescript_project.git
