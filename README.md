## Setup for Tailwid CSS    

### To setup tailwind css, run these commands

Step 1: This initializes the directory as a NodeJs project.
```
npm init -y
```
Step 2: Install the required packages.
```
npm install -D tailwindcss postcss autoprefix vite
```
Step 3: Use this command to generate the tailwind.config.js file in your code editor.
```
npx tailwind init -p
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
content: []
```
with this line 
```
content: ["*"]
```

Step 6: Add "start" : "vite" to your scripts in package.json.

Step 7: Run npm run start command to start a develpement server.

### Tailwind Css Setup. 
## This YouTube Link is the image of below given image:-
[YouTube Link: https://youtu.be/aUunolbb1xU?si=2Bv-J1Ankj4GbwA_&t=486]
![Tailwind Css Setup](https://github.com/Nitin1604/Tailwind-Css-Setup/assets/80270629/02713ce7-cfee-404e-a678-ba861182e7f4)

## How to setup Tailwind CSS
Step 1: Run the following commands
```
npm install -D tailwindcss
npx tailwindcss init
```
Step 2: Update tailwind.conf.js file to include this line:

```
content: ["*.html"],
```
Step 3: create src/input.css to include:
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```
Step 4: Include the src/output.css file to your html

Step 5: Run the following command:
```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```

## Commands that i used in tailwind css project are as follows:-
1st Command:-
```
npm install vite
```
After installing vite in the terminal or vs code terminal this message will be shown as given below:-

```
added 10 packages in 4s

3 packages are looking for funding
  run `npm fund` for details
```

2nd Command:-
```
npm init -y
```
This message will be shown as given below:-

=> Wrote to D:\Project Series\{Your Project Name}\package.json: 
```
Wrote to D:\Project Series\CodeWithHarry Webiste Clone\package.json:

{
  "dependencies": {
    "vite": "^5.0.12"
  },
  "name": "codewithharry-webiste-clone",
  "version": "1.0.0",
  "main": "index.js",
  "devDependencies": {},
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "description": ""
}
```

3rd Command:-
```
npm install -D tailwindcss postcss autoprefix vite
```
This message will be shown as given below:-

```
npm WARN idealTree Removing dependencies.vite in favor of devDependencies.vite
npm WARN deprecated browserslist@0.2.0: Browserslist 2 could fail on reading Browserslist >3.0 config used in other tools.

added 119 packages, and audited 130 packages in 10s

28 packages are looking for funding
  run `npm fund` for details

3 moderate severity vulnerabilities

Some issues need review, and may require choosing
a different dependency.

Run `npm audit` for details.
```

4th Command:-
```
npx tailwind init -p
```

This message will be shown as given below:-
```
Created Tailwind CSS config file: tailwind.config.js
Created PostCSS config file: postcss.config.js
```

5th Command:-
```
npm run start
```
This message will be shown as given below:-

```
> codewithharry-webiste-clone@1.0.0 start
> vite


  VITE v5.0.12  ready in 227 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h + enter to show help
```
