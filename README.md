# AGTBlockchain


### Starting


1) Run and install ganache

2) Quickstart or start new workspace 

3) Go to settings and change port number to 7545 to run on localhost

4) type "truffle compile" followed by "truffle migrations --reset" on the ballot-contract directory

5) on the ballot-app directory type "npm start" 

6) retrieve the mnemonic from ganache and use it on metamask when creating a new account

7) go to your localhost:3000 to run your codeon the local web

### Precautions

1) make sure metamask runs on port 7545 NOT  on ropsten

2) every time you restart ganache you need to use truffle compile followed by truffle migrate --reset(to deploy your contracts) on ballot-contract directory

3) Make sure the name of the solidity file is the same all throughout the json files, app,js, and such

### Note

1) if there are issues with metamask, then uninstall and reinstall

2) changing the gas value might give you a lot of errors

### To Do

1) add buttons to the bindevents for your buttons to run

2) work on buttons on the front-end
