# Mastering Blockchain - Second Edition
This is the code repository for [Mastering Blockchain - Second Edition](https://www.packtpub.com/big-data-and-business-intelligence/mastering-blockchain-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781788839044), published by [Packt](www.packtpub.com). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
A blockchain is a distributed ledger that is replicated across multiple nodes and enables immutable, transparent and cryptographically secure record-keeping of transactions. The blockchain technology is the backbone of cryptocurrencies, and it has applications in finance, government, media and almost all other industries. Mastering Blockchain, Second Edition has been thoroughly updated and revised to provide a detailed description of this leading technology and its implementation in the real world.

This book begins with the technical foundations of blockchain technology, teaching you the fundamentals of distributed systems, cryptography and how it keeps data secure. You will learn about the mechanisms behind cryptocurrencies and how to develop applications using Ethereum, a decentralized virtual machine. You will also explore different other blockchain solutions and get an introduction to business blockchain frameworks under Hyperledger, a collaborative effort for the advancement of blockchain technologies hosted by the Linux Foundation. You will also be shown how to implement blockchain solutions beyond currencies, Internet of Things with blockchain, blockchain scalability, and the future scope of this fascinating and powerful technology.
## Instructions and Navigations
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

The code will look like the following:
```
pragma solidity ^0.4.0; 
contract TestStruct { 
  struct Trade 
  { 
    uint tradeid; 
    uint quantity; 
    uint price;  
    string trader; 
  } 
 
  //This struct can be initialized and used as below 
 
  Trade tStruct = Trade({tradeid:123, quantity:1, price:1, trader:"equinox"}); 
 
} 
```

* All examples in this book have been developed on Ubuntu 16.04.1 LTS (Xenial) and macOS version 10.13.2. As such, it is recommended to use Ubuntu or any other Unix like system. However, any appropriate operating system, either Windows or Linux, can be used, but examples, especially those related to installation, may need to be changed accordingly.
* Examples related to cryptography have been developed using the OpenSSL 1.0.2g 1 Mar 2016 command-line tool.
* Ethereum Solidity examples have been developed using Remix IDE, available online at https://remix.ethereum.org
* Ethereum Byzantine release is used to develop Ethereum-related examples. At the time of writing, this is the latest version available and can be downloaded from https://www.ethereum.org/.
* Examples related to IoT have been developed using a Raspberry Pi kit by Vilros, but any aapropriate latest model or kit can be used. Specifically, Raspberry Pi 3 Model B V 1.2 has been used to build the hardware example of IoT. Node.js V8.9.3 and npm V5.5.1 have been used to download related packages and run Node js server for IoT examples.
* The Truffle framework has been used in some examples of smart contract deployment, and is available at http://truffleframework.com/. Any latest version available via npm should be appropriate.

## Related Products
* [Mastering Blockchain](https://www.packtpub.com/big-data-and-business-intelligence/mastering-blockchain?utm_source=github&utm_medium=repository&utm_campaign=9781787125445)

* [Building Blockchain Projects](https://www.packtpub.com/big-data-and-business-intelligence/building-blockchain-projects?utm_source=github&utm_medium=repository&utm_campaign=9781787122147)

* [Blockchain and Cryptocurrency (Bitcoin, Ethereum) Essentials [Video]](https://www.packtpub.com/application-development/blockchain-and-cryptocurrency-bitcoin-ethereum-essentials-video?utm_source=github&utm_medium=repository&utm_campaign=9781788990837)
### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
