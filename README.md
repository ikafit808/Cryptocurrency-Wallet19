# Cryptocurrency Wallet19

![image](https://github.com/ikafit808/Cryptocurrency-Wallet19/assets/142754993/b50012f3-d8aa-4453-8726-75085bfe7f77)

### Background

You work at a startup that is building a new and disruptive platform called KryptoJobs2Go. KryptoJobs2Go is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As KryptoJobs2Go’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

In this Challenge, you will complete the code that enables your customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, you will assume the perspective of a KryptoJobs2Go customer who is using the application to find a fintech professional and pay them for their work.

### What You're Creating

To complete this Challenge, you will use two Python files, both of which are contained in the starter folder.

The first file that you will use is called `krypto_jobs.py`. It contains the code associated with the web interface of your application. The code included in this file is compatible with the Streamlit library. You will write all of your code for this Challenge in this file.

The second file that you will use is called `crypto_wallet.py`. This file contains the Ethereum transaction functions that you have created throughout this module’s lessons. By using import statements, you will integrate the `crypto_wallet.py` Python script into the KryptoJobs2Go interface program that is found in the `krypto_jobs.py` file.

Integrating these two files will allow you to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.

Specifically, you will assume the perspective of a KryptoJobs2Go customer in order to do the following:

* Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

* Fetch and display the account balance associated with your Ethereum account address.

* Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a KryptoJobs2Go candidate for their work.


* Digitally sign a transaction that pays a KryptoJobs2Go candidate, and send this transaction to the Ganache blockchain.

* Review the transaction hash code associated with the validated blockchain transaction.

Once you receive the transaction’s hash code, you will navigate to the Transactions section of Ganache to review the blockchain transaction details. To confirm that you have successfully created the transaction, you will save screenshots to the README.md file of your GitHub repository for this Challenge assignment.

### Libraries
- import streamlit as st
- from dataclasses import dataclass
- from typing import Any, List
- from web3 import Web3
- import os
- import requests
- from dotenv import load_dotenv

- load_dotenv()
- from bip44 import Wallet
- from web3 import Account
- from web3 import middleware
- from web3.gas_strategies.time_based import medium_gas_price_strategy

### Transaction Outcome
<img width="267" alt="Screenshot 2024-03-11 at 6 47 17 PM" src="https://github.com/ikafit808/Cryptocurrency-Wallet19/assets/142754993/fdb8636a-0f82-4ba6-a67e-a6c2dd8e728e">

![Screenshot 2024-03-11 at 6 48 59 PM](https://github.com/ikafit808/Cryptocurrency-Wallet19/assets/142754993/ec91a3b1-f609-4d94-adbd-0054027faa10)

![Screenshot 2024-03-11 at 6 48 07 PM](https://github.com/ikafit808/Cryptocurrency-Wallet19/assets/142754993/97407763-6960-4ab1-80c6-c70fd78ffb8e)

![Screenshot 2024-03-11 at 6 51 37 PM](https://github.com/ikafit808/Cryptocurrency-Wallet19/assets/142754993/28f0ad43-a9dd-4881-9180-7ece2697b4bf)





