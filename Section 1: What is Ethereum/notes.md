# What is Ethereum?

* BTC, Ethereum History

* Ethereum: a network of nodes
    * Has main different networks: main network, test network (for testing purposes).etc

* Setup Metamask (Chrome extension for non-dev purposes)
    * Account Address: id (like email)
    * Public/Private Key: hexadecimal numbers (very large number)

* Transaction
    * nonce: how many times the sender has sent a transaction (short for: non-sense...not sure why named this way though)
    * to: address of account money is going to
    * value: amount ether to send to target address
    * gas price: amount of ether the sender is willing to pay per unit gas to get this transaction started
    * startGas/gasLimit: unit of gas this transaction can consume
    * v, s, r: cryptographics pieces of data that can be used to generate the senders account address. Generated from the sender's private key
        * if you have private key, you can generate v,s,r. But not the other way around (v,s,r --> private key is NOT possible)

    