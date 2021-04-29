## Welcome to VoteChain 👋
VoteChain is a Decentralized Web Application, to fulfil the purpose of Secure Voting. It is an Ethereum-Based Web Application, which allows its user to cast their vote for selected candidates without revealing their identity. The most important feature of this Web App is it's security. Blockchain is very secure as of now. Thus building a e-Voting machine based on blockchain is very helpful, to maintain the integrity of the elections. 


### How to Run the Project locally ?

This is how you can run the project in your machine. Here I have used a linux machine to run the project however if you've a Windows machine you can still read the instruction & try to run them in windows accordingly. Here is a [Youtube-Tutorial-Video](https://www.youtube.com/watch?v=BoH75TkjwHw&feature=youtu.be) for your reference.
### Prerequisite
* [Ganache](https://www.trufflesuite.com/ganache): For Personal Ethereum Blockchain
* [Web3Js](https://web3js.readthedocs.io/en/v1.3.0/): Ethereum Javascript Library
* [Metamask](https://metamask.io/): Extension for your Browser 
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

## Support or Contact

For any queries, ping me here: [sanmol016@gmail.com](mailto:sanmol016@gmail.com)

