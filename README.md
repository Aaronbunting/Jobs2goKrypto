# KryptoJobs2Go
KryptoJobs2Go offers a platform tailored for the hiring of Fintech specialists, accepting Ether as the primary mode of payment. The core feature of this project is its seamless integration with Ethereum wallets and transactions. This integration leans on Python, coupled with the web3 Python toolkit and Streamlit for a rudimentary user interface.

## Framework Overview

This project is structured around two pivotal Python scripts:

* crypto_wallet.py: This module houses the essential functionalities such as generating an Ethereum profile, inquiring about an account's funds, and orchestrating transactions between accounts.

* krypto_jobs.py: This is the primary script that shapes the application, leveraging Streamlit to manifest a user-friendly web interface. Here, users can cherry-pick a candidate, input the service duration, and proceed with an Ether transaction as payment.

## Initialization and Operation

Steps to get started:

1. Ascertain that Python is set up on your device - ideally, Python 3.7 or a later version.

2. Make a clone of the given repository.

3. Lay down the necessary tools using the command: pip install -r requirements.txt.

4. Fashion a .env file, inserting essential environment variables, notably your mnemonic seed phrase.

5. Launch the Streamlit tool via: streamlit run krypto_jobs.py.

6. Use the URL supplied by Streamlit, be it local or network-based, to access the application.

## Visual Overview

Ganache Snapshot: A visual capture presents the Ganache account, spotlighting specifics like the address, existing funds, and the tally of transactions (TX).
