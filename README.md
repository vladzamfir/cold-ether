# Cold-Ether

Ethereum cold storage solution using nodejs


##Installation:

```
git clone https://github.com/vladzamfir/Cold-Ether.git
cd Cold-Ether
npm install
```


*packagetx* packages a raw unsigned ethereum transaction. A local ethereum node with rpc enabled is used to set the transaction nonce.

*newaccount* creates a new ethereum account

*sign* signs a raw unsigned transaction

*sendtransaction* publishes a raw signed transaction. A local ethereum node with rpc enabled is used to publish the transaction.