# Simple contract with 2-3 functions integrating with front-end

This straightforward front-end application communicates with a smart contract that has been set up on the blockchain. You can access the most recent value and increase a coin value in the contract using the programme..

## Description

The Front-End of a Simple Contract A smart contract that has been deployed on the blockchain can be interacted with using application, a simple web application. To facilitate smooth communication with the contract, the programme establishes a connection with the well-known Ethereum wallet MetaMask.

The application's primary features are as follows:

1. Increase Cryptocurrency: By clicking a button, users can add 1 to the cryptocurrency value that is kept in the smart contract.

2. Value of Cryptocurrency: Users can access the most recent price of the cryptocurrency that is stored in the contract and have it displayed on a website.

## Getting started
### Installing

1.Clone the repository:
git clone https://github.com/your-username/your-repo.git

2.Install the dependencies:
npm install

#if Using Hardhat Then:-

Run npm i

### Executing program
Implement your smart contract:

To deploy the smart contract to a blockchain network use Remix.
Record the address on the contract.

*Refresh the contract's address:

Open a text editor and the app.js file.
Put the actual contract address you got from the deployment in place of the placeholder "CONTRACT_ADDRESS."
File saving.

*Launch the programme:

To host the HTML, JavaScriptstart a web server or use a development server like Live Server.
Use the correct URL to visit the programme, such as http://127.0.0.1:5500/index.html.

*Link MetaMask:

Check to see if MetaMask is active in your browser and logged into the preferred network.
Give the programme access to connect to your MetaMask account if asked to do so.
```
MYcontract.sol
// SPDX-License-Identifier: MIT
// MyContract.sol
pragma solidity ^0.8.0;

contract MyContract {
  uint public cryptocurrency;

  function incrementCryptocurrency() public {
    cryptocurrency += 1;
  }

  function getCryptocurrency() public view returns (uint) {
    return cryptocurrency;
  }
}
```
## Help

```
npm i (please must install node js for running this command)
your Files Should be update
Address must be same as deplyed contracts
```
## Result
![result](https://github.com/Satya-1107/smart-contract/assets/136918622/0afbd299-0fd9-4330-a894-0c66e4c4de7f)

## Author
Satya Prakash




   
