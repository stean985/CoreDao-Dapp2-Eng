To test this decentralized application follow the steps below:

1- git clone https://github.com/stean985/CoreDao-Dapp2-Eng.git
2- navigaye in Backend folder : cd .\Backend
3- create secret.json file, and add the dollowing line :
{"PrivateKey":"you private key, do not leak this file, do keep it absolutely safe"}


4- install hardhat and dependencies : npm install --save-dev hardhat
5- compile all 3 smart contracts : npx hardhat compile
6- deploy the smart contracts : npx hardhat run .\scripts\deploy.js
the output should look like 
Deploying contracts with the account: 0x5720ec329B00EAd34D2FBAf97c852231222efb0A
Contracts deployed:
Staking Token: 0x9373dd47cb1Dd094264279F6A912Da95e69a0e4F
Reward Token: 0xDfDf8a69042De6422E6B50A838DC26Bb57Ec7730
Staking Dapp: 0xBb9eD6A08C75a42354807Ab252CE28B812627CfE


7- avigate to Frontend folder : cd .\Frontend
8- install dependencies : npm install
9- test locally with : npw run start
