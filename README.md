# RevaCharityDonationTracker
This is repository created for RevaHack 2024 Season



Requirements:
npm
yarn
node
vite
This step is compulsory.


1.    To create web3 side interface with solidity smartcontract
    Use: npx thirdweb@latest create --contract

    Give
    Project Name ? - web3
    Framework ? - Hardhat
    Name of smart contract ? - Crowdfunding
    Started from ? - Empty Contract

    

2.    To create environment variable
  
    npm install dotenv
    Add private key of wallet to .env file and add .env file to .gitignore to stop it from pushing private key to GitHub repo

    

3.    We have to deploy it in thirdweb using npm under hardhat (Automatically compiles and uplloads smart contracts to thirdweb)

    Connect wallet and deploy

    Writing smartcontract functionality:
    createCampaign
    donateToCampaign

    Reading smartcontract functionality:
    campaigns
    getCampaigns
    getDoantors
    numberofCampaigns



    
    npm run deploy

    

4.    To create client side for aceessing information, to edit (modify) using thirdweb

    npx thirdweb create --app

    

5.    To implement dynamic routing in web applications

    npm install react-router-dom



6.    Intergrating tailwindCSS in client side using vite

    npm install -D tailwindcss postcss autoprifixer
    npm tailwind init -p
