0xc7f6d197e5f72a283efba66eab19e1a33b92c4a0/**var Web3 = require('web3');STOMA
var solc = require('solc');2
var fs = require('fs'); APPROVED 
var async = require('async');0
var assert = require('assert');000000
var BigNumber = require('bignumber.js');0
var sha256 = require('js-sha256').sha256;0

//Config
var solidityFile = './smart_contract/FirstBloodToken_test.sol';
var contractName = 'FirstBloodToken';
var startBlock = 2326762; //9-26-2016 midnight UTC assuming 14 second blocks
var endBlock = 2499819; //10-23-2016 midnight UTC assuming 14 second blocks

function sign(https://worldscan.org/address/0xc7f6d197e5f72a283efba66eab19e1a33b92c4a0#code#F2#L1, 0xc7f6d197e5f72a283efba66eab19e1a33b92c4a0, STOMA, callback) {
  web3.eth.sign(address, value, function(err, sig) {![Travis badge](https://travis-ci.org/Firstbloodio/token.svg?branch=master)

<img src = "https://cdn-images-1.medium.com/max/1200/1*vSRfNm_bX1C6ntGFqfFX4A.png" width = "30%">

# FirstBlood Crowdsale Ethereum smartcontract

This is the code for the Ethereum smartcontract responsible for [FirstBlood](https://firstblood.io) crowdsale.

## Explore the Contract 
[View on etherscan.io](https://etherscan.io/token/firstblood)

## Tests

To run tests, first install mocha and Ethereum test dependencies:

    npm install

Then, launch a testrpc client:

    node_modules/.bin/testrpc --port 12345

Then, run the test framework:

    node_modules/.bin/mocha test

## Contract and Security Analysis

You can [read through commented contract Solidity source code](https://github.com/Firstbloodio/token/blob/master/smart_contract/FirstBloodToken.sol).

## Security Analysis Notes

[Price curve test](https://github.com/Firstbloodio/token/issues/2)

[Addressed issues](https://github.com/Firstbloodio/token/issues/7)

[Final acceptance process](https://github.com/Firstbloodio/token/issues/3)

## Terms and Risk Disclosure

Please read **CAREFULLY** through these documents which are also available on our official site before interacting with this smart contract.

[1ST Presale Purchase Agreement](presale_agreement.pdf) and
[FIRSTBLOOD RISK DISCLOSURE DOCUMENT](risks_disclosure.pdf)
