## Setup for Tailwind CSS                                       

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
npm install -D tailwindcss postcss autoprefixer
```
After installing vite in the terminal or vs code terminal this message will be shown as given below:-

```
added 121 packages in 5s

32 packages are looking for funding
  run `npm fund` for details
```

2nd Command:-
```
npx tailwindcss init
```
This message will be shown as given below:-
```
Created Tailwind CSS config file: tailwind.config.js
```

3rd Command:-
```
npm init -y
```
This message will be shown as given below:-

Wrote to D:\Project Series\{Your project name}\package.json:
```
Wrote to D:\Project Series\CodeWithHarry Website Clone\package.json:
{
  "devDependencies": {
    "autoprefixer": "^10.4.17",
    "postcss": "^8.4.34",
    "tailwindcss": "^3.4.1"
  },
  "name": "codewithharry-website-clone",
  "version": "1.0.0",
  "main": "tailwind.config.js",
  "dependencies": {
    "ansi-regex": "^6.0.1",
    "ansi-styles": "^6.2.1",
    "any-promise": "^1.3.0",
    "anymatch": "^3.1.3",
    "arg": "^5.0.2",
    "balanced-match": "^1.0.2",
    "binary-extensions": "^2.2.0",
    "brace-expansion": "^2.0.1",
    "braces": "^3.0.2",
    "browserslist": "^4.22.3",
    "camelcase-css": "^2.0.1",
    "caniuse-lite": "^1.0.30001585",
    "chokidar": "^3.6.0",
    "color-convert": "^2.0.1",
    "color-name": "^1.1.4",
    "commander": "^4.1.1",
    "cross-spawn": "^7.0.3",
    "cssesc": "^3.0.0",
    "didyoumean": "^1.2.2",
    "dlv": "^1.1.3",
    "eastasianwidth": "^0.2.0",
    "electron-to-chromium": "^1.4.659",
    "emoji-regex": "^9.2.2",
    "escalade": "^3.1.2",
    "fast-glob": "^3.3.2",
    "fastq": "^1.17.1",
    "fill-range": "^7.0.1",
    "foreground-child": "^3.1.1",
    "fraction.js": "^4.3.7",
    "function-bind": "^1.1.2",
    "glob": "^10.3.10",
    "glob-parent": "^6.0.2",
    "hasown": "^2.0.0",
    "is-binary-path": "^2.1.0",
    "is-core-module": "^2.13.1",
    "is-extglob": "^2.1.1",
    "is-fullwidth-code-point": "^3.0.0",
    "is-glob": "^4.0.3",
    "is-number": "^7.0.0",
    "isexe": "^2.0.0",
    "jackspeak": "^2.3.6",
    "jiti": "^1.21.0",
    "lilconfig": "^2.1.0",
    "lines-and-columns": "^1.2.4",
    "lru-cache": "^10.2.0",
    "merge2": "^1.4.1",
    "micromatch": "^4.0.5",
    "minimatch": "^9.0.3",
    "minipass": "^7.0.4",
    "mz": "^2.7.0",
    "nanoid": "^3.3.7",
    "node-releases": "^2.0.14",
    "normalize-path": "^3.0.0",
    "normalize-range": "^0.1.2",
    "object-assign": "^4.1.1",
    "object-hash": "^3.0.0",
    "path-key": "^3.1.1",
    "path-parse": "^1.0.7",
    "path-scurry": "^1.10.1",
    "picocolors": "^1.0.0",
    "picomatch": "^2.3.1",
    "pify": "^2.3.0",
    "pirates": "^4.0.6",
    "postcss-import": "^15.1.0",
    "postcss-js": "^4.0.1",
    "postcss-load-config": "^4.0.2",
    "postcss-nested": "^6.0.1",
    "postcss-selector-parser": "^6.0.15",
    "postcss-value-parser": "^4.2.0",
    "queue-microtask": "^1.2.3",
    "read-cache": "^1.0.0",
    "readdirp": "^3.6.0",
    "resolve": "^1.22.8",
    "reusify": "^1.0.4",
    "run-parallel": "^1.2.0",
    "shebang-command": "^2.0.0",
    "shebang-regex": "^3.0.0",
    "signal-exit": "^4.1.0",
    "source-map-js": "^1.0.2",
    "string-width": "^5.1.2",
    "string-width-cjs": "^4.2.3",
    "strip-ansi": "^7.1.0",
    "strip-ansi-cjs": "^6.0.1",
    "sucrase": "^3.35.0",
    "supports-preserve-symlinks-flag": "^1.0.0",
    "thenify": "^3.3.1",
    "thenify-all": "^1.6.0",
    "to-regex-range": "^5.0.1",
    "ts-interface-checker": "^0.1.13",
    "update-browserslist-db": "^1.0.13",
    "util-deprecate": "^1.0.2",
    "vite": "^5.0.12",
    "which": "^2.0.2",
    "wrap-ansi": "^8.1.0",
    "wrap-ansi-cjs": "^7.0.0",
    "yaml": "^2.3.4"
  },
  "scripts": {
    "start": "vite"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "description": ""
}


```

4th Command:-
```
npx tailwind init -p
```

This message will be shown as given below:-
```
tailwind.config.js already exists.
Created PostCSS config file: postcss.config.js
```

5th Command:-
```
npm install vite
```
This message will be shown as given below:-

```
added 6 packages, and audited 128 packages in 2s

33 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
```
6th Command:-
```
npm run start   
```
This message will be shown as given below:-
```
> codewithharry-website-clone@1.0.0 start
> vite


  VITE v5.0.12  ready in 206 ms

  ➜  Local:   http://localhost:5173/
  ➜  Network: use --host to expose
  ➜  press h + enter to show help
```
