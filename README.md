# How To Deploy A Express App To Now 2

A barebones Node.js app using [Express](http://expressjs.com/).

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) installed and also have yarn installed.

```sh
git clone https://github.com/bearcodeteeeps/node.git # or clone your own fork
cd node
yarn
yarn start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Zeit Now 2

```
echo "# node" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/bearcodeteeeps/node.git
git push -u origin master
```

## Documentation

For more information about using Node.js on Now 2, see these Dev articles:

- [Examples of how to deploy apps to now 2](https://zeit.co/examples/)

