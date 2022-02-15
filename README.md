# Non Transferrable NFT Minting Dapp

## What it does

- **NFT minter dapp allows anyone to mint an NFT.**
- **The minter brings their own file and pays the minting fee.**
- **The transfer function of the NFT is intentionally broken so that the NFT cannot be transferred.**

## Inspiration

- **This project's inspiration is to make use of NFTs as a way to replace physical/digital certificates issued by institutions.**
- **Using the Non-Transferrable-NFTs minted using this Dapp, we can prove the validity of the credentials using NFTs as it could only be obtained when minting.**
- **Example - University can issue their degree certificates using this minting dapp. Since this NFT is Non-Transferrable, we can ensure that this NFT was obtained by completing the study from the university, and thus had their NFT minted by the university. A graduate can own their education and prove validity to any other peer/institution.**


![Front End of Dapp ](./nft_minter_dapp.jpg)
![Certificate Minted in OpenSea](./certificate_opensea.jpg)


## Instructions To Run This Project
Requires python3, if you don't have it there are multiple resources online on how to install it according to your platform.
1. Set a virtual environment using 
    ```
    Python3 -m venv venv
    ```
2. Initialize your virtual environment (For Mac and Linux)
    ``` 
    source venv/bin/activate 
    ``` 
3. Intall the dependencies using 
    ```
    pip install -r requirements.txt
    ```
4. Enter Application ID and SOURCE_URL of Moralis Server in the `/app/static/js/logic.js` file
5. RUN `python run.py` to run the Flask Application
6. You can replace the Contract address in `logic.js` to your contract address


