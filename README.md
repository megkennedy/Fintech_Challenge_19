# Fintech_Challenge_19
UW Fintech Bootcamp Challenge 19

In this challenge we are completing the code to allow customers to send cryptocurrency to fintech professionals.

## Libraries and dependencies needed

import streamlit as st

from dataclasses import dataclass

from typing import Any, List

from web3 import Web3

w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))

import os

import requests

from dotenv import load_dotenv

load_dotenv()

from bip44 import Wallet

from web3 import Account

from web3 import middleware

from web3.gas_strategies.time_based import medium_gas_price_strategy

## Required screenshots

<img width="1416" alt="Screen Shot 2022-01-02 at 8 02 20 PM" src="https://user-images.githubusercontent.com/88640228/147903780-154bdbf7-0873-4f89-b39d-4d5652de7b69.png">

<img width="1199" alt="Screen Shot 2022-01-02 at 7 58 26 PM" src="https://user-images.githubusercontent.com/88640228/147903796-bebaf848-f11b-4d78-aa77-530d7aa14e2f.png">

<img width="1197" alt="Screen Shot 2022-01-02 at 7 59 19 PM" src="https://user-images.githubusercontent.com/88640228/147903826-707d0d1f-1ca5-4758-b2ff-fc26cc1935e0.png">

<img width="1189" alt="Screen Shot 2022-01-02 at 8 01 39 PM" src="https://user-images.githubusercontent.com/88640228/147903856-ad381771-9477-4b7d-8b16-c83933123c3e.png">


## Contributors

As always a shout out to my professer, TAs, and classmates for all their help during this process
