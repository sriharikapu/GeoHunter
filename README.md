# ETHdenver Project: GeoHunter
_This app was developed for the ETHdenver hackathon, February 2019._

_Authors: Bryce Doganer, Andy Watt, Gareth Oates, Colin McCrae, Lucas Henning_


## Project Specs
### Repo Location
[The final project is stored here on GitHub](https://github.com/edgefund/GeoHunter "GitHub - ETHdenver Project: GeoHunter")



## How to Set Up for Evaluation
### Pre-requisites
 It is presumed that the evaluator has the following applications already installed:

+ Git
+ Node Package Manager (Node v11.9.0, Npm v6.5.0)
+ Truffle v5.0.4 (core: 5.0.4)
+ Solidity v0.5.0 (solc-js)
+ Ganache or Ganache-CLI (v6.3.0 (ganache-core: 2.4.0)
+ Google Chrome with Metamask Plug-in installed
+ A code editor (e.g. VS Code or Atom)

### Steps
The following steps will allow the project to be evaluated. The terminal commands are based on using Ubuntu Linux.

1. Navigate your development folder and clone the project repo from Github. The command below will create a folder 'project' in your chosen development folder. 

   $ `git clone https://github.com/edgefund/GeoHunter`
   
2. Go into the new folder 

   $ `cd project`

3. Install the npm modules

   $ `npm install`

4. To view in a code editor 

   $ `code .` for VS Code or `atom .` for Atom

5. To compile the app code

   $ `truffle compile`

6. Ensure that you are running Ganache (or Ganache-CLI) on Port 8545 (HTTP://127.0.0.1:8545)

7. To migrate the contacts to the Ganache local blockchain

   $ `truffle migrate` (if you need to migrate the contract again, you will  need to use `truffle migrate --reset`)

8. To run the app code tests

   $ `truffle test`

9. Run the app's JavaScript React development server locally to bring up the app UI. These commands should automoatically open your default browser

   $ `cd app`

   $ `npm install`
   
   $ `npm run start`

11. You should now be able to use the app's UI. 

Contract actions will appear in the developer console log in Google Chrome. Press Ctrl + Shift + I to view these. Ctrl+C to exit the development server in Terminal.


Project Name
GeoHunter

Project Tagline/Description (140 Characters Max. Will be used on table card for judging)
A tracking Dapp where users race to complete a treasure hunt to be the fastest to scan all the QR codes in sequence. A leaderboard tracks all users progress. The Dapp is hosted on a Quorum node on AWS.

Team Members. First and Last Names
Bryce Doganer, Andy Watt, Gareth Oates, Colin McCrae, Lucas Henning

Status.im ID for Each Team Member (we will use this to contact you and your team)
Bryce Doganer: https://get.status.im/user/0x04703e7fa07e09bb4c8d573f21b9e0c0a1001e1a721bc6563edd2864d665e6b19331d873a3d40040b15d1e6af6a31b54c324445dde034808fdb5e5b519b9698157

Andy Watt: https://get.status.im/user/0x0438f2ee778e162126e3e943a132710dc8344b87af7d8b8b3b04cbc8f6c1f199057035c74e65e60af3bf42344ac6396185291728e5cfb2ff5ed1cd595b745ecbae

Gareth Oates: https://get.status.im/user/0x049f192a3de993182a335528ea67394fc831216ac09b451974bb4a89abcf11c5038b0951a02d3847eda05461c8716e2f71a0a686588d57d8321801abcb375b1f70

Colin McCrae: https://get.status.im/user/0x04982eedca00bf0df3b303c6ae8acbb300bab5619ab0b6418424a6246285473c45919973c3b9751a2361c0bb8955cc81a93816f2985f1d1b3522523c614c49f86c

Lucas Henning: https://get.status.im/user/0x04f6c346bb0d6bc3af69ba904d1dc86b58f99d48154bd36a92446cd57afc173f06cca725bf01b1f9b9210816b4fd0fb7c94fdcc1eae5b0aa4771ca582696ff6353

Detailed Project Description (no more than 3-4 sentences)
A treasure hunt is set up which consists of a series of QR codes which must be scanned by users in the correct order. Each QR code has an associated picture stored on IPFS which shows its location, with the IPFS hash (and all user and tag data) stored on the blockchain. The fastest user to scan all the QR codes in the correct order wins. A leaderboard can be viewed showing the fastest times, and the status of players currently on the treasure hunt. The Dapp is hosted on a Quorum node on AWS. This project is the basis for a supply chain item tracking Dapp which is in line with UN Sustainable Development Goal 8: Decent Work and Economic Growth.

Describe your tech stack (e.g., protocols, languages, API’s, etc.)
Truffle v5.0.4 (core: 5.0.4)
Solidity v0.5.0 (solc-js)
Javascript
Ganache CLI v6.3.0 (ganache-core: 2.4.0)
IPFS (go-ipfs version: 0.4.18)
Quorum (an enterprise version of Go Ethereum that addresses transaction privacy trough a permissioned group of known participants, high speed, network-wide transparency, and high throughput)
OpenZeppelin-solidity
React
uPort
QR Codes
Track for which you’re submitting (Open or Impact)
Impact

All Bounties Completed/Incorporated
Quorum 2019 Bounty 1 (High Performance)
Quorum 2019 Bounty 3 (Overview: Public/Private Chain)
Zeppelin Bounty 2 (Best usage of Zeppelin tools (OpenZeppelin & ZeppelinOS))
Truffle
IPFS
uPort
