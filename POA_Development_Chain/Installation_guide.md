Instructions to launch the chain

Remember to include any environment setup instructions and dependencies.

Be sure to include all of the geth flags required to get both nodes to mine and explain what they mean.

Explain the configuration of the network, such as it's blocktime, chain ID, account passwords, ports, etc.


## Dependencies 

### Go Ethereum

1. Download and install Go Ethereum Tools. Navigate to the link below, download version "Geth & Tools 1.9.7" based on your operating system
    https://geth.ethereum.org/downloads/
    
2. Rename the donwloaded file and save in a location that is easily accessible.


### My Crypto

1. Open your browser and navigate to the downloads page at https://download.mycrypto.com/; download the appropriate version to your operating system.


## Launching the Chain

Open the DevChain folder to locate the nodes. 

This blockchains' genesis block and nodes have already been created, follow the instructions to commence the nodes to be able to send transactions.

# DevChain

Chain ID 111

## Node 1

### Address

    0x485f02BF68F3900DD5Ef71EfF6C719c2e4d40dfe

### Start Command

    ./geth --datadir node1 --unlock 485f02BF68F3900DD5Ef71EfF6C719c2e4d40dfe --mine --rpc --allow-insecure-unlock

## Node 2

### Address

    0x2B0F5f1ad7BBCF30436BfbBDd8fDfff305C600A0

### Start Command

    ./geth --datadir node2 --unlock 2B0F5f1ad7BBCF30436BfbBDd8fDfff305C600A0 --mine --port 30304 --bootnodes enode://f33dfb8532061530b1b5b0049d1d2d85bbb9192786de18018e36083af01c8cfe5498b01d4621a8dafeeca9e453ab5137a178ae9f6fff5e6312920baebcd32d0d@127.0.0.1:30303 --ipcdisable --allow-insecure-unlock
 
 
 # Connecting MyCrypto 
 
 Open MyCrypto app and click on Change Network at the bottom left
 
 ![Alt text](Screenshots/change-network.png)
 
 Click on "Add Custom Node" and input the network information. Input the information listed above, your Custom Node window should look like the following screenshot. 
 
 ![Alt text](Screenshots/custom_network.png) 
 
 
# Sending a Transactions on MyCrypto

On the left side of the menu select the View & Send option then slect Keystore file.

![Alt text](Screenshots/select_keystore_file.png)

From there, select Wallet File and then navigate to the Keystore directory inside your Node1 directory and select the file that is located there. This file will unlock your wallet inside MyCrypto.

In the To Address box, type the account address of Node2 and how much ETH you would like to transfer. 

![Alt text](Screenshots/transaction-send.png)

Confirm the transaction by clicking "Send Transaction". A green message will give you the option to check the transaction status; your transaction will state it is Pending until it has been sent with a Successful status change.

![Alt text](Screenshots/TX_status.png)

![Alt text](Screenshots/TX_status.png)