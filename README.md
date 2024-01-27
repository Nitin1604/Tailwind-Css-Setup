## Setup for Tailwid CSS

To setup tailwind css, run these commands

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

### Tailwind Css Setup. 
[YouTube Link: https://youtu.be/aUunolbb1xU?si=2Bv-J1Ankj4GbwA_&t=486]
![Tailwind Css Setup](https://github.com/Nitin1604/Tailwind-Css-Setup/assets/80270629/02713ce7-cfee-404e-a678-ba861182e7f4)


