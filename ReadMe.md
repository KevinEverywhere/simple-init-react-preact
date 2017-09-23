# simple-init-react-preact

This project is an example of how current react and preact cli-build processes work and appear side by side. Once the initial files are created, you can experiment in each of the apps to see how interchangeable they actually are.

## instructions

Each framework has its own installation and launch scripts. To begin, download this repo and run yarn or npm install. Once the repo is installed, yarn is used in the script files.

```
git clone git@github.com:KevinEverywhere/simple-init-react-preact.git
cd simple-init-react-preact
npm install
```

### react

Running the startReact script will first test to see if it has ever been run before (testReact). After the directory has been recognized or created, the startReact script changes to the my-react-app directory and runs yarn start. When you run yarn start, it will install or check for updates in the repo's dependencies. From the root directory (simple-init-react-preact), run the following script and the application will launch in the browser.

If you have not previously installed yarn:
```
npm run startReact
```

If you have previously installed yarn:
```
yarn run startReact
```

To use the yarn package bundled with this repo:
```
node_modules/.bin/yarn run startReact
```
You can use npm or yarn in for installation and running of package.json dependency and script content. Yarn is recommended for performance and dependency management reasons.

### preact

Running the startPreact script will first test to see if it has ever been run before (testPreact). After the directory has been recognized or created, the startPreact script changes to the my-preact-app directory and runs yarn start. When you run yarn start, it will install or check for updates in the repo's dependencies. From the root directory (simple-init-react-preact), run the following script and once it creates the application, you can find it at http://localhost:8080.


If you have not previously installed yarn:
```
npm run startPreact
```

If you have previously installed yarn:
```
yarn run startPreact
```

To use the yarn package bundled with this repo:
```
node_modules/.bin/yarn run startPreact
```
You can use npm or yarn in for installation and running of package.json dependency and script content. Yarn is recommended for performance and dependency management reasons.


## summary

This truly is meant as nothing more than a way to quickly see the state of react and preact development the first day of autumn, 2017. This should save some time for those wanting to have a quick view of how the two look under the hood.

## reference

This repo uses the initialization scripts described in the [preact-cli][preact-cli] for preact and [create-react-app][create-react-app] for react repos to create a base application. For more information, please use the links below to discover best practices and state of the moment examples and documentation.

[preact][preact]

[What's new in Create React App][whatsnew]

-------------

[preact]: https://preactjs.com/
[preact-cli]: https://github.com/developit/preact-cli

[whatsnew]: https://facebook.github.io/react/blog/2017/05/18/whats-new-in-create-react-app.html
[create-react-app]: https://github.com/facebookincubator/create-react-app
