## Obtain a dedicated machine with at least:

- 4 core CPU
- 8 GB of RAM
- 200 GB of SSD memory
- Fast and reliable internet connection

# It is highly recommended follow the steps with video guide.
```https://www.youtube.com/watch?v=MB4K61-c9mk```

## To install all prerequisites and DappNode, execute the commands below in the terminal of the machine

```
sudo wget -O - https://prerequisites.dappnode.io | sudo bash
```
```
sudo wget -O - https://installer.dappnode.io | sudo bash
```

## In a command line of your host machine, run

```
source /usr/src/dappnode/DNCORE/.dappnode_profile
```
```
dappnode_status
```
```
dappnode_wireguard
```

## Set up Wireguard from this link on your local machine to access dappnode page.
```
https://www.wireguard.com/install/
```

## and go to this link from the browser. 

```
http://my.dappnode/#/
```
## After installing the packages, we need to create keyfiles for our worker wallet. We will do this using nodejs.
### Install nodejs on the server by following these commands.

```
sudo apt update
sudo apt install nodejs
sudo apt install npm
sudo apt install git
```

## Then run this command and install the keyfile generator

```
git clone https://github.com/powerpool-finance/powerpool-agent-v2-compose
cd powerpool-agent-v2-compose
```

## Install the required dependencies
```
npm i
```

## Create a keyfile. Run
```
node jsongen.js %worker_private_key% %password%
```

🟪 Prysm Sepolia DAppNode package:
/ipfs/QmT2vSKsKVTs7oFxYnnzb8cpWiKnMDvPLy1qnaLWfEfVkD

🟫 Geth Sepolia DAppNode package:
/ipfs/QmNy6zTZM9LfHomWJpNYFWX6kJqz9Jgm5eragJagMwc4jk

🟨 PowerAgent DAppNode package:
/ipfs/QmULaiokk8QZXdBNq4VbgsZnSEEeczG1qrLgZrbnDp6UHp

🌐 WebSockets RPC:
For sepolia geth, use ws://sepolia-geth.dappnode:8546

1. New tCVP contract: https://sepolia.etherscan.io/address/0x34221a0df3bada492d540ec2b362401195106e60

2. New tCVP faucet: https://sepolia.etherscan.io/address/0xDa2b8ca09080876e716ef5326107A68F603f95B2

3. New Agent: https://sepolia.etherscan.io/address/0xbde2aed54521000dc033b67fb522034e0f93a7e5

4. 🖥 PowerAgent UI: https://app.powerpool.finance/#/sepolia/ppv2/agents-contracts
      


## How to get keeperID
https://sepolia.etherscan.io/address/0xc8E864f12c337Bdf6294a3DCeE0E565D2B1B4d90#readContract#F27
![image](https://github.com/neuweltgeld/PowerAgent-testnet/assets/101174090/18eb8202-37a4-4066-9cda-564d5e610635)

## How to see actually stake amount and worker, admin addresses
https://sepolia.etherscan.io/address/0xc8E864f12c337Bdf6294a3DCeE0E565D2B1B4d90#readContract#F13
![image](https://github.com/neuweltgeld/PowerAgent-testnet/assets/101174090/19517b78-3be3-444e-9f06-ad10f40574f0)

