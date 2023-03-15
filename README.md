# FNS-introduction
I.Project Introduction 
The Filecoin Naming Service (FNS) is a decentralized name service based on the Filecoin EVM. It resolves metadata into easy-to-read xxx.fil names. Each FNS domain is treated as an NFT, and the FNS contract complies with the interfaces of the ERC-721 standard. The NFT can be transferred and traded on secondary markets.
Filecoin Name Service (FNS) is similar to Ethereum's ENS (Ethereum Name Service) and Handshake. FNS allows users to use easy-to-remember domain names to access their data stored on the Filecoin network. By mapping the CID (Content Identifier) of a file to an easy-to-remember domain name, FNS provides a convenient way to access data stored on Filecoin without needing to remember complex CIDs. FNS also provides an easy-to-integrate way for developers to use the Filecoin network.
FNS provides a secure and decentralized way to resolve on-chain and off-chain address resources on the Filecoin network into simple human-readable domain names. It is an important part of the Filecoin ecosystem. It can not only make the filecoin system more readable and user-friendly, but also become an important infrastructure for web3.
Users can use FNS as an identity to access the web3 world, and only need to integrate the DNS domain name into FNS, and their domain name can be used as a wallet, Web3 username and a decentralized website.

II. FNS Design Goals
The FNS design goals are to provide a decentralized domain name system for Filecoin network users and developers, and to address the difficulties and inconveniences of using CIDs to access data stored on the Filecoin network.
The primary design goals of FNS include:
Usability: FNS should provide an easy-to-use domain name system that enables users to conveniently access their data stored on the Filecoin network without having to remember complex CIDs.
Decentralization: FNS should be a decentralized system without a single centralized control point, avoiding single-point failures and tampering risks.
Security: FNS should provide a secure domain name system that ensures user data is not tampered with or stolen.
Ease of Integration: FNS should provide easy-to-integrate interfaces and tools, allowing developers to easily use FNS in their applications.
Scalability: FNS should be a scalable system capable of handling the growing demand for data storage on the Filecoin network.

III. FNS Architecture
The FNS architecture is based on Filecoin EVM smart contracts and the IPFS naming system (IPNS) to implement domain name registration, renewal, and transfer operations. The FNS architecture is illustrated in the following diagram:

FNS Domain: An FNS domain is an easy-to-remember domain name, similar to an ENS domain on Ethereum. FNS domains are registered by users themselves and can be associated with data stored on Filecoin.
CID: A CID is a Content Identifier for a file, similar to a hash value in IPFS. A CID uniquely identifies a file and can be used to access it on the network.
FNS Contract: The FNS contract is an ERC-721 compliant NFT contract that manages FNS domains. It provides functions for domain registration, renewal, transfer, and resolution.
Resolver: The resolver is a smart contract that maps FNS domains to CIDs. It is responsible for resolving an FNS domain name to the corresponding CID and retrieving data from Filecoin.

IV. FNS Features
FNS provides the following features:
Decentralized Domain Name System: FNS is a decentralized domain name system that resolves on-chain and off-chain addresses to easy-to-remember domain names.
Easy-to-Use: FNS provides an easy-to-use domain name system that enables users to conveniently access their data stored on the Filecoin network without having to remember complex CIDs.


Secure: FNS provides a secure domain name system that ensures user data is not tampered with or stolen.


NFT-Based: FNS domains are treated as NFTs, and can be transferred and traded on secondary markets.


Scal ability: FNS is designed to be a scalable system capable of handling the growing demand for data storage on the Filecoin network.
Interoperability: FNS can be easily integrated with other web3 protocols and applications, allowing users to use their FNS domains as a wallet, Web3 username, and a decentralized website.
Renewal and Transfer: FNS domains can be renewed and transferred by their owners, providing flexibility and control over domain ownership.


V. FNS Application Principles and Architecture
FNS Architecture
The FNS system is based on smart contracts and IPNS. The smart contract is responsible for registering and managing FNS domains, while IPNS is used to resolve the mapping between FNS domains and the corresponding content identifiers (CIDs) of the data stored on the Filecoin network.
FNS Domain
FNS domains are easy-to-read domain names that can be used to access data stored on the Filecoin network. Users can register FNS domains through the FNS contract, and associate them with the CID of their stored data. FNS domains can be used to represent various types of data, including personal data, files, and applications.
Content Identifier (CID)
The CID is a unique identifier for data stored on the Filecoin network, similar to the hash value used in IPFS. Each CID uniquely identifies a piece of data on the network and can be used to access that data. CIDs are used in FNS to map the FNS domains to the corresponding data stored on the Filecoin network.
FNS Application Principles
The design principles of FNS are as follows:

User-friendly: FNS should provide an easy-to-use naming system that allows users to access their data on the Filecoin network without needing to remember complex CIDs.


Decentralized: FNS should be a decentralized system with no single point of control, minimizing the risk of censorship or manipulation.


Secure: FNS should provide a secure naming system that ensures the integrity and confidentiality of user data.


Easy to Integrate: FNS should provide easy-to-use APIs and tools for developers to integrate FNS into their applications.


Scalable: FNS should be a scalable system that can accommodate the growing demand for data storage on the Filecoin network.

VI. Conclusion
The Filecoin Name Service (FNS) is a decentralized naming system that provides a user-friendly and secure way to access data stored on the Filecoin network. By mapping easy-to-remember domain names to content identifiers, FNS simplifies the process of accessing data on Filecoin, making it more accessible to users. FNS is an important infrastructure for the Web3 ecosystem and will continue to play a critical role in the development of decentralized applications.
