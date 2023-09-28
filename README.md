# SafeDocu

 A decentralized system to store all your personal data and access them with just one click!

## Inspiration

We all know how annoying it is to find that important document you need right away for FAFSA, government forms, and many more. How about having all your important documents all in the click of a button. With SafeDocu, you can have all your important documents secured and accessed with ease.

## What it does

By signing up, you can add documents, such as birth certificates, insurance, and many more. Whenever you want to access them, just log in and be able to look at all your documents at once.

## How we built it

- On the backend, we used Solidity, python, Ethereum blockchain, and flask.  
- We used Infura api to connect to the Ethereum blockchain, where our smart contract was hosted. We decided to use blockchain for our backend as it provides greater security for the document.  
- The job of the smart contract was to take files as input from the user and generate a unique key. The generated key then can be used to access all the documents uploaded by the user.  
- As it is not possible to store pdf files directly into the blockchain, we decided to use IPFS (InterPlanetary File System), a P2P network for storing files. The web app takes the file as input and generates a unique hash for each file, which also serves as their address, and using the hash we can view the files on the browser, thus making the whole process more secure.  
- We used python to build the bridge between the web app and the decentralized network.  
- Flask was used to connect the html to the backend and send information back and forth and to run the live server.  

## How it works

- Registration: Sign up with an account. The secure id and password will be able to help you sign into your account with ease.  
- Uploading: Upload your documents and name your documents so it is easier to search for the right document.  
- Accessing: Access the documents you uploaded with your unique ID  

# 

## What's next for SafeDocu

- Combining the figma design with the working project
- Adding a passcode to each file for more added security
- Support for different file types such as jpg, png and many more.
