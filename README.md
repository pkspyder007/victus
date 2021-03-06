
# Victus

This project is based on blockchain application for keeping track of a person’s medical history. It’s a dapp built on ethereum that aims at helping out clients for maintaining their records and safeguards them against any frauds. Clients can freely store their prescriptions,bills and reports in this dapp 
without the fear of them getting misplaced.

### 📹 [Video](https://youtu.be/-ZSbkhzr0Ns)

![ezgif com-gif-maker (6)](https://user-images.githubusercontent.com/75828535/132113790-ba2927a2-26cb-4d87-9b96-adaeec4dc520.gif)

## Objectives

* Victus will ensure that the users will not be fooled or cheated from the hospital’s side. In case if they try to manipulate the bill, victus dapp will not let that happen. Moreover clients ,who maintain their medical records on victus ,even after displacing their phone or mobile number can access their records through their Id.

* Victus will employ good data practices to make sure sensitive data recorded in it via the users aren’t open to exploitation.

*	Victus can be used to make intelligent record tracing dapp for even maintaining old records among the wide population.

## Features
1. Client auth using metamask
2. Admin has two step auth - SAWO and metamask
3. data stored on blockchain using IPFS
4. data link generated which makes the file easily shareable
5. all file type upload supported
6. files uploaded are time stamped
7. hospitals can updated patients account with new reports/bills
8. tampering data is impossible

## Contributors
1. [Rishita Shaw](https://github.com/theseregrets)
2. [Moinak Banerjee](https://github.com/moinak878)
3. [Aditi Jaiswal](https://github.com/aditijais)

### Dependency Checklist 
```bash
$ node --version
$ npm --version
$ truffle --version
```
### Configuration
1. Ganache server set to `localhost:7545`
2. React webapp running at `localhost:3000`
3. Sawo user auth set to `localhost`

## Must have
1. Node
2. Truffle ` npm install -g truffle `
3. Ganache 
4. MetaMask extension (MUST HAVE!!!!!!!)

## get started 

```bash
truffle migrate
truffle deploy
npm start
```

## Set up
``` bash
# Install dependencies (only the first time)
npm install

# starting at the local host u choose in ganache
npm start

# Compiling using truffle
truffle compile

# Deploying to local ganache network
truffle deploy

# Build for production in the dist/ directory
npm run build

# Testing smart contracts
truffle test
```



# screenshots

![Screenshot 2021-09-04 at 11 22 16 PM](https://user-images.githubusercontent.com/32922277/132104473-65915cac-10db-41b2-a093-1193810d7529.png)

<img width="1384" alt="Screenshot 2021-09-04 at 11 22 41 PM" src="https://user-images.githubusercontent.com/32922277/132104479-7b07040f-6994-4823-84ab-ad166fc85de2.png">
<img width="1402" alt="Screenshot 2021-09-04 at 11 23 40 PM" src="https://user-images.githubusercontent.com/32922277/132104481-ad2cb506-8ea7-4a30-aa54-51941b712baf.png">

![Screenshot 2021-09-04 at 11 23 15 PM](https://user-images.githubusercontent.com/32922277/132104483-68cc8975-8551-4948-b403-be4e55605953.png)

<img width="1386" alt="Screenshot 2021-09-04 at 11 23 52 PM" src="https://user-images.githubusercontent.com/32922277/132104485-2d1d6823-99b9-406a-bb00-3eb89a5ca9e0.png">




# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

