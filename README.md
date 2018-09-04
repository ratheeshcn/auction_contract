# auction_contract
My Ethereum experiments
Write a sample auction contract and made a local test with truffle network

step 1:
install truffle

`npm install -g truffle`

step 2:
truffle init

`truffle init`

 it creates the truffle project in your directory

step 3 
write your smart contact on truffle project `contracts` directory 

step 4
truffle compile

`truffle compile`

step 5
To test the contract with blockchain network, we need a sample network truffle has its on sample blockchain , you can get it
by writting 

`truffle develop`

it shows 10 accounts and its keyhaskes, you can use any of the account to test with.

step 6
Install Web3 

`npm install web3`

This java script tool help you to connect with the blockchain network, it has some method to connect your bloackchain.
the `web3` tool need your compiled code of your contact, its called `abi` or ` Application binary interface`  you can get 
that from build folder for the app.

step 7

create your own test file in apps `test` folder using `web3`.

please look more about `web3` methods


