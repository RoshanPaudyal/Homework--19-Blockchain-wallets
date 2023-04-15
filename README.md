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

Installation
To install this application on your local machine, complete the following steps:

Clone the GitHub repository to your local machine.
bash
Copy code
git clone https://github.com/<username>/<repository_name>.git
Navigate to the project directory.
bash
Copy code
cd <repository_name>
Install the dependencies.
bash
Copy code
pip install -r requirements.txt
Start the Streamlit application.
bash
Copy code
streamlit run krypto_jobs.py
Usage
Once you have started the Streamlit application, you can use the following functionality:

Display Wallet Balance
The application displays the current balance of your Ethereum wallet in Ether.

Send Transactions
You can send Ether transactions to other Ethereum addresses by entering the recipient's address and the amount of Ether to send.

Hire Candidates
You can hire freelancers by selecting a candidate from the drop-down menu, entering the number of hours to hire them for, and clicking the "Send Transaction" button.

Inspect Transactions
After sending a transaction, you can inspect the transaction hash by navigating to the Ganache accounts tab and locating your account (index 0). Take a screenshot of the address, balance, and transaction (TX) count, and save this screenshot to the README.md file of your GitHub repository.

Conclusion
This application demonstrates how to interact with Ethereum wallets using Python and Web3.py. By leveraging the Ethereum blockchain, KryptoJobs2Go provides a secure and transparent payment solution for freelancers and employers
