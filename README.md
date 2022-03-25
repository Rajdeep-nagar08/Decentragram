# "Decentralized Photo Social Media."
## Project Diagram:
![image](https://user-images.githubusercontent.com/92351292/159774856-8f92c291-f98c-4de6-bc09-aeb16365afeb.png)

Follow the steps below to download, install, and run this project.

## Dependencies
Install these prerequisites :-
- NPM: https://nodejs.org
- Truffle: https://github.com/trufflesuite/truffle
- Ganache: http://truffleframework.com/ganache/
- Metamask: https://metamask.io/


## Step 1. Clone the project
`git clone https://github.com/Rajdeep-nagar08/Decentragram`

## Step 2. Install dependencies
```
$ cd decentragram
$ npm install
```
## Step 3. Start Ganache
Open the Ganache GUI client that you downloaded and installed. This will start your local blockchain instance.


## Step 4. Compile & Deploy Decentragram Smart Contract
`$ truffle migrate --reset`
You must migrate the decentragram smart contract each time your restart ganache.

## Step 5. Configure Metamask
See free video tutorial for full explanation of these steps:
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

## Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000

