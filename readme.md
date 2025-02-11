Two contracts are being used: `FundMe`, the main crowdfunding contract, and `PriceConverter`. 

They function much like "Kickstarter", allowing users to **send** any native blockchain cryptocurrency. 
They also enable the owner of the contract to **withdraw** all the funds collected. We will then deploy these contracts on **Unichain testnet**.

Once `FundMe` is deployed on Remix, the function is "payable". A payable function allows you to send native blockchain currency (e.g., Ethereum, Polygon, Avalanche) to the contract.

A **minimum USD amount** is indicated to send to the contract when the function `fund` is called. 
To transfer funds to the `FundMe` contract, you can navigate to the _value section_ of the Remix deployment tab, enter a value (e.g. 0.1 ether) then hit `fund`. A MetaMask transaction confirmation will appear, and the contract balance will remain zero until the transaction is finalized. Once completed, the contract balance will be updated to reflect the transferred amount.

The contract owner can then `withdraw` the funds. In this case, since we own the contract, the balance will be removed from the contract's balance and transferred to our wallet.


The FundMe. Sol contract has been deployed on Unichain testnet here:

https://unichain-sepolia.blockscout.com/address/0xC0f787939e4920189650c81306c7987A11181026


