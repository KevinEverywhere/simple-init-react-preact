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

```
yarn run startReact
```

### preact


Running the startPreact script will first test to see if it has ever been run before (testPreact). After the directory has been recognized or created, the startPreact script changes to the my-preact-app directory and runs yarn start. When you run yarn start, it will install or check for updates in the repo's dependencies. From the root directory (simple-init-react-preact), run the following script and once it creates the application, you can find it at http://localhost:8080.

```
yarn run startPreact
```

## summary

This truly is meant as nothing more than a way to quickly see the state of react and preact development the first day of autumn, 2017. This should save some time for those wanting to have a quick view of how the two look under the hood.
