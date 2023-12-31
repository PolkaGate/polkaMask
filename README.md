# PolkaMask: Polkadot with Metamask

 A MetaMask Snap for seamless interaction with the Polkadot ecosystem, a prominent platform for cross-chain communication and scalability. Now you can use your MetaMask wallet to access Polkadot dApps and tokens effortlessly.

To integrate this Snap into your dApp, you can easily upgrade your existing @polkadot/extension-dapp by replacing it with [@polkagate/extension-dapp](https://www.npmjs.com/package/@polkagate/extension-dapp). It's important to note that once our changes are merged into the official extension-dapp, this manual update will no longer be necessary.

PolkaMask is currently operational within the Metamask Flask and is in the process of being published on the Metamask repository, making it readily available to all Metamask users.

<p align="center">
  <img src="https://raw.githubusercontent.com/Nick-1979/PolkadotJsPlusPictures/main/polkagate/polkamask%20small.bmp" alt="Image" width="600" />
</p>

## Running the Repository

The repository contains a  dApp located in the `./packages/dapp` directory and the snap code, which can be found in `./packages/snap`. To try out the snap, follow these steps in your terminal:

```bash
git clone https://github.com/PolkaGate/polkaMask.git
cd polkaMask
yarn
yarn run start
```

After executing these commands, you can access a basic decentralized application (dApp) page for testing polkamask snap at http://localhost:8000/. For more advanced dApp visit [apps.polkagate.xyz](apps.polkagate.xyz). Note, Metamask Flask (Metamask) needs to be installed to interact with the snap and dApp.

## Test
To test the snap run:

```
yarn test
```

## Docker

To build and run docker container(s) run:

```
yarn compose
```
Afterward, you can access user interfaces as follows:

- http://localhost:8000: This displays a dapp designed for testing the Polkamask snap.

- http://localhost:80: This presents a modified version of the Polkadot Cloud in the staking dashboard.



<p align="center">
  <img src="https://raw.githubusercontent.com/PolkaGate/polkaMask/main/docs/images/simpleTransfer.png" alt="Image" width="1000" />
</p>


Note: This Metamask snap operates autonomously and does not rely on other extensions within the Polkadot ecosystem for its functionality.