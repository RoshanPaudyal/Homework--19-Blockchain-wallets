# Homework--19-Blockchain-wallets

### KryptoJobs2Go - Blockchain Wallets
KryptoJobs2Go is a decentralized job board that leverages the Ethereum blockchain to facilitate secure and transparent payment transactions between employers and freelancers. This project implements the backend functionality for managing Ethereum wallets, displaying the current balance of Ether, sending transactions to other Ethereum addresses, and interacting with smart contracts.

#### Prerequisites
Before running this application, ensure that you have the following dependencies installed:
- Python 3.7 or higher
- Ganache
- Truffle
- Metamask
- Web3.py
- Streamlit

#### Usage
- From the Streamlit application, select a candidate from the drop-down menu and enter the number of hours you want to hire them for.
- Click the "Send Transaction" button to sign and send the transaction with your Ethereum account information.
- Wait for the transaction to be validated and added to a block.
- View your updated account balance and transaction details in Ganache.

#### Troubleshooting
- If you encounter any issues while running the application, try restarting Ganache and/or the Streamlit application.
- Make sure your Ethereum account has enough Ether to complete the transaction.
- Double-check that your environment variables are set correctly in the .env file.


#### Display Wallet Balance
The application displays the current balance of your Ethereum wallet in Ether.

![image](https://user-images.githubusercontent.com/116679505/232502913-ded77ef5-7eee-4e9d-ae1c-484128fa3fe7.png)


#### Send Transactions
You can send Ether transactions to other Ethereum addresses by entering the recipient's address and the amount of Ether to send.

![Validated Hash](https://user-images.githubusercontent.com/116679505/232503225-aaf349f7-83d7-4cfd-972f-34ddd6f8fc40.png)


#### Hire Candidates
You can hire freelancers by selecting a candidate from the drop-down menu, entering the number of hours to hire them for, and clicking the "Send Transaction" button.

#### Inspect Transactions
After sending a transaction, you can inspect the transaction hash by navigating to the Ganache accounts tab and locating your account (index 0). Take a screenshot of the address, balance, and transaction (TX) count, and save this screenshot to the README.md file of your GitHub repository.
![Transfer](https://user-images.githubusercontent.com/116679505/232503280-30c89719-3880-44d6-986e-690be686e2fc.png)

![Sender and Receiver](https://user-images.githubusercontent.com/116679505/232503335-50564600-4fd7-41fd-b689-d0a888e6882d.png)

#### Conclusion
This application demonstrates how to interact with Ethereum wallets using Python and Web3.py. By leveraging the Ethereum blockchain, KryptoJobs2Go provides a secure and transparent payment solution for freelancers and employers
