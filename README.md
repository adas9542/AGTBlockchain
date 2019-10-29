# AGTBlockchain


### Precautions Development


1) Run and install ganache

2) Quickstart or start new workspace 

3) Go to settings and change port number to 8545 to run on localhost

4) Go to index and check your first tested balance


### Precautions

1) make sure metamask runs on port 7545 NOT  on ropsten

2) retrieve the mnemonic from ganache and use it on metamask when creating a new account

3) every time you restart ganache you need to use truffle compile followed by truffle migrate --reset(to deploy your contracts) on ballot-    contract directory

4) then go to the ballot-app directory and do npm install if you don't have it already and then run npm start to have your localhost:3000    run your codeon the local web

5) Make sure the name of the solidity file is the same all throughout the json files, app,js, and such

### Note

1) if there are issues with metamask, then uninstall and reinstall

2) changing the gas value might give you a lot of errors

### To Do

1) add buttons to the bindevents for your buttons to run

2) work on buttons on the front-end
