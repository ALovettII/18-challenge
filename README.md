# 18-challenge
 A blockchain-based ledger system, complete with a user-friendly web interface.

 This ledger should allow partner banks to conduct financial transactions (that is, to transfer money between senders and receivers) and to verify the integrity of the data in the ledger.


## Technology
* Streamlit
* Dataclasses: dataclass
* Typing: Any
* Datetime
* Hashlib


## Installation Guide
Using the Conda package manager: [My GitHub Project](https://github.com/ALovettII/18-challenge.git)

This project uses [Streamlit](https://docs.streamlit.io/en/stable/getting_started.html), to install this package using your terminal:
```shell
# Activate dev enviroment
conda activate dev

# Install Streamlit
pip install streamlit
```


## Usage
The steps for this project are divided into the following sections:
1. Create a Record Data Class
2. Modify the Existing Block Data Class to Store Record Data
3. Add Relevant User Inputs to the Streamlit Interface
4. Test the PyChain Ledger by Storing Records

After inputing the required information, click 'Add Block' to initiate the respective function and save a record inside a block in the chain.

**Sample Blockchain Ledger Inputs**
| Sender | Receiver | Amount |
| ------ | -------- | ------ |
| Arthur | Frodo | 10 | 
| Bilbo | Gandalf | 20 |
| Samwise | Sauron | 25 |
| Pippin | Aragorn | 50 |
| Legolas | Gollum | 60 | 

### Screenshots
Successful deployment of this repository will yield results such as:

**Verification: Streamlit Application Page & Block Inspector**
![App Page Verification](https://github.com/ALovettII/18-challenge/blob/main/images/verify_application.png)

**Verification: Block Details**
![Block Verification](https://github.com/ALovettII/18-challenge/blob/main/images/verify_blockchain.png)

**Validation: Blockchain Validation Test**
![Blockchain Validation](https://github.com/ALovettII/18-challenge/blob/main/images/validate_blockchain.png)


## Contributors
Created by Arthur Lovett

