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

🟢 PowerAgent Contract address: 0xc8E864f12c337Bdf6294a3DCeE0E565D2B1B4d90

🔴 Test CVP Contract address: 0xD5134EcD90EB63276aF2Fca897cC04D845AfD74f

🟪 Prysm Sepolia DAppNode package:
http://my.dappnode/#/installer/%2Fipfs%2FQmT2vSKsKVTs7oFxYnnzb8cpWiKnMDvPLy1qnaLWfEfVkD

🟫 Geth Sepolia DAppNode package:
http://my.dappnode/#/installer/%2Fipfs%2FQmNy6zTZM9LfHomWJpNYFWX6kJqz9Jgm5eragJagMwc4jk

🟨 PowerAgent DAppNode package:
[http://my.dappnode/#/installer/%2Fipfs%2FQmP55bcEhtWtrbiueisuoZx4XN5AeLsuvtKU6CFoTG52GF](http://my.dappnode/installer/dnp/%2Fipfs%2FQmSdpLXzCdfekJWn7e4VJCsBVxMUZgdKLVJkzYDkP9VbC6)

🌐 WebSockets RPC:
For sepolia geth, use ws://sepolia-geth.dappnode:8546


## How to get keeperID
https://sepolia.etherscan.io/address/0xc8E864f12c337Bdf6294a3DCeE0E565D2B1B4d90#readContract#F27
![image](https://github.com/neuweltgeld/PowerAgent-testnet/assets/101174090/18eb8202-37a4-4066-9cda-564d5e610635)

## How to see actually stake amount and worker, admin addresses
https://sepolia.etherscan.io/address/0xc8E864f12c337Bdf6294a3DCeE0E565D2B1B4d90#readContract#F13
![image](https://github.com/neuweltgeld/PowerAgent-testnet/assets/101174090/19517b78-3be3-444e-9f06-ad10f40574f0)

