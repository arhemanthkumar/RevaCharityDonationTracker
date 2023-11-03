# RevaCharityDonationTracker
This is repository created for RevaHack 2024 Season

To create web3 side interface with solidity smartcontract
Use: npx thirdweb@latest create --contract

Give
Project Name ? - web3
Framework ? - Hardhat
Name of smart contract ? - Crowdfunding
Started from ? - Empty Contract

To create environment variable 
Use : npm install dotenv
Add private key of wallet to .env file and add .env file to .gitignore to stop it from pushing private key to GitHub repo

We have to deploy it in thirdweb using npm under hardhat (Automatically compiles and uplloads smart contracts to thirdweb)

Connect wallet and deploy

Writing smartcontract functionality:
createCampaign
donateToCampaign

Reading smartcontract functionality:
campaigns
getCampaigns
getDoantors
numberofCampaigns

To do this:
npm run deploy

To create client side for aceessing information, to edit (modify) using thirdweb

To do this:
Use: npx thirdweb create --app

To implement dynamic routing in web applications
Use : npm install react-router-dom

Intergrating tailwindCSS in client side using vite
Use : npm install -D tailwindcss postcss autoprifixer
    : npm tailwind init -p
