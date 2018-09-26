# Bachelorarbeit
# Project setup:
### //install npm:
npm install -g npm
### //install truffle 
npm install -g truffle
### //install test environment 
*Ethereum TestRPC is a fast and customizable blockchain emulator. It allows making calls to the blockchain without the overheads of running an actual Ethereum node. [1]*
npm install -g ethereumjs-testrpc
### //create a folder for project and Initialize a Truffle project base
Cd desktop
mkdir project_blockchain
cd project_blockchain
truffle init // creates a project base
### //download and run ganache to get 10 accounts 
https://truffleframework.com/ganache


##//run the test environment and project parallel in two different cmd(windows) or terminal(mac):
test environment | run project 
------------ | -------------
Cd desktop/project_blockchain | Cd desktop/project_blockchain
Testrpc | •	Truffle compile // to compile the project
 ... |•	Truffle test // to test the project
 
Note* in windows: truffle.cmd test and truffle.cmd compile 

source: 
1.	https://nethereum.readthedocs.io/en/latest/ethereum-and-clients/test-rpc/
