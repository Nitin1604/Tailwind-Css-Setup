## Setup for Tailwid CSS

To setup tailwind css, run these commands

Step 1: This initializes the directory as a NodeJs project.
```
npm init -y
```
Step 2: Install the required packages.
```
npm install -D
```
Step 3: Use this command to set intiailize the tailwind css.
```
npmx tailwind init -p
```
Step 4: Create a css file "input.css", add it to your html and edit it with this content:-
```
@tailwind base;
@tailwind components;
@tailwind utilities;
``` 
Step 5: In your tailwind.config.js file replace content[], with content["*"],

Replace this line 
```
content[]
```
with this line 
```
content["*"]
```

Step 6: Add "start" : "vite" to your scripts in package.json.

Step 7: Run npm run start command to start a develpement server.

