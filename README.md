# nodejs trial

# How to set up

```
git init
npm init
touch README.md
curl 'https://raw.githubusercontent.com/github/gitignore/master/Node.gitignore' > .gitignore
npm install
git add .
git commit -m 'initial commit.'
```

```
npm install --save backpack-core
npm install --save-dev babel-cli
mkdir src
touch src/index.js
echo '\nbuild/' >> .gitignore
npm start
npm run build
git add .
git commit -m 'added backpack and babel.'
```

## How to run 
```npm start```

## How to build
```npm run build```
