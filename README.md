# VoteChain
![Ethereum](https://img.shields.io/badge/Ethereum-A6A9AA?style=for-the-badge&logo=ethereum&logoColor=white)
![NodeJS](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white)

<br>A Decentralized e-Voting Portal based on Ethereum Blockchain. 

## About
This is a Blockchain-based project, made by me [[Anmol Singh Yadav](https://www.linkedin.com/in/anmolsinghyadav/)] as a semester project in Vellore Institute of Technology. This projet is entirely based on Ethereum Blockchain with Web3Js to link it with HTML. Blockchain Technology is yet very hard to be hacked [ Until You have committed mistakes in Protocols or Coding Part ] that is what allows implementation of Blockchain in the Voting System. Once Blockchain is introduced in the Voting System, no one can put question on it's integrity. Thus, an inititative, of switching our voting system on Blockchain must be done by Government.
In this project we have used Etherem Blockchain to demonstrate the voting procedure.

## How to Run the Project ?
This is how you can run the project in your machine. Here I have used a linux machine to run the project however if you've a Windows machine you can still read the instruction & try to run them in windows accordingly. Here is a [Youtube-Tutorial-Video](https://www.youtube.com/watch?v=BoH75TkjwHw&feature=youtu.be) for your reference.
### Prerequisite
* [Ganache](https://www.trufflesuite.com/ganache): For Personal Ethereum Blockchain
 <div align="cemter"><img src="/docs/ganache-home-empty.png" height=320 width=560/></div> <br/>

* [Web3Js](https://web3js.readthedocs.io/en/v1.3.0/): Ethereum Javascript Library
* [Metamask](https://metamask.io/): Extension for your Browser 
 <div align="cemter"><img src="/docs/meta.png" height=320 width=560/></div> <br/>

* [NodeJS](https://nodejs.org/en/download/package-manager/) : Allows JavaScript to run on the server

### Procedure
1. Start your Ganache and configure it to run on the same port as you've mentioned in the *"truffle-config.js"* file.
2. When you are done with Ganache, it's time to run the npm server. In order to run the NPM server, simply head to the project direcotry and type the following command in your terminal:
```Node 
npm run dev 
```
3. After execution of the above code, the server will be started on your machine and you can switch over to your browser now.
4. On your Browser, in the URL window, type localhost:[port number], where the port number is provided on your terminal when you run the server. You can now see the hosted web page.
5. Now, we will configure the Metamask. Synchronize the Metamask with your Ganache so that you can access the dummy Ethers for your testing purpose.
6. Now we are ready. You can choose one of the options available in the list whom you want to cast your vote and click on the final submit button. 
7. You will see a final pop-up button from the metamask where you will be asked to confirm the transaction. You have to click on Confirm and congratulations you have casted your vote.
--- 

For any queries, ping me here: [sanmol016@gmail.com](mailto:sanmol016@gmail.com)
