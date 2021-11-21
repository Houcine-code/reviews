# reviews with ReactJs

I have NodeJs, npm, npx, yarn, git and Vscode installed

In Terminal:

```
node -v
```

: v14.17.6

```
npm -v
```

: 8.1.3

```
yarn -v
```

: 1.22.17

I create a local react project with npm

In Terminal:

```
npx create-react-app reviews
```

I Create a public repository with the same name "reviews" on github.com

I Create Readme.md file

in the local project folder

In Terminal:

```
cd ../reviews
```

initiating an empty repo

In Terminal:

```
git init
```

Adding this repository as a remote to our project

git remote add "name-of-remote" "url-of-repository"

In Terminal:

```
git remote add origin https://github.com/Houcine-code/reviews
```

configuring an upstream branch and setting the remote as origin

In Terminal:

```
git push --set-upstream origin master
```

installing gh-pages

In Terminal:

```
yarn add gh-pages
```

I added two keys to the scripts value in the package.json

In Terminal:

```
 "scripts": {
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build",
  },
```

I added the homepage field in the package.json

https://username.github.io/repository-name/

In Terminal:

```
"homepage": "https://Houcine-code.github.io/reviews/",
```

Finnaly deploying my application:

In Terminal:

```
npm run deploy
```

If Git Autentiqation needed

```
Username for 'https://github.com': username
Password for 'https://Houcine-code@github.com': password
```
