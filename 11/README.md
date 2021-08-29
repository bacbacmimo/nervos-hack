# Gitcoin: 11) Use A Tron Wallet To Execute A Smart Contract Call

### A screenshot of the accounts you created (account list) in ckb-cli:

![b01](https://user-images.githubusercontent.com/89572507/131243760-4101b8fa-6275-4182-901c-3eaf1deaa6b0.png)

### A link to the Layer 1 address you funded on the Testnet Explorer:

https://explorer.nervos.org/aggron/address/ckt1qyqq52vtvwlahwspwzrtxmvazjw7dtu740es6y0k2h

### A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2:

![b05](https://user-images.githubusercontent.com/89572507/131244646-2b98f19a-2ed3-4084-ad77-4a75fbb90577.png)

### A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2:

![b06](https://user-images.githubusercontent.com/89572507/131245014-0c56fef9-95bf-40f0-9355-eeadefb6ecf6.png)

### The transaction hash of the "Contract call" from the console output:

0x40f9ef77f0457032633de4a35bf30577b4e76d3419fc3195779ff90af03b0398

### The contract address that you called:

0xA6BE704FC84222D8878Bb5cC7B90110c8827c150

### The ABI for contract you made a call on:

[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
]

### Your Tron address:

TDC8PSjx2MDkwnRgm78b87PgS8rbWHjPgQ
