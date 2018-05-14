# EdenChain

## Overview
EdenChain is built for the enterprises of tomorrow - scalable, flexible, reliable and secured. Most importantly, Eden focuses on optimal resource management and security - a pragmatic approach to how businesses use blockchain.
Through hardware integration, EdenChain strives towards a balancing act between leveraging the strengths of public blockchains with transaction volume and security demands of enterprise companies. EdenChain supports two ways of building blockchain service on top of its platform. 
Solidity could be used for developing blockchain services. It is the most well-known smart contract language and already has many applications and related documents.
API is allowed to develop a blockchain service. Indeed API is the most common practice to create an application. Unlike solidity, API does not have special restrictions nor requirements in terms of language as long as the language supports RESTful API.
Edenchain aims to be positioned as an enterprise blockchain platform with ease of development and quick development, which alleviate the complexity of blockchain development for developers and eventually reduces the burden of finding blockchain developers to the enterprises.

## Cloud Native
Edenchain is designed to run on cloud platform from the beginning. So architecture and tech stacks used in Edenchain is also cloud-native. As a permissioned blockchain, using cloud platform is a natural choice because of its high availability. In that sense, cloud has obvious values compare to non-cloud platform. Cloud platform encourages to us to apply cloud-native architecture and software stacks. 

## E-Explorer
E-Explorer is a web-based block browser that allows you to browse EdenChain’s block information. With E-Explorer, anyone can easily retrieve and view information about EdenChain blocks, history and transactions.
The most important features of E-Explorer development are summarized into two points. First is ease of use. The primary users of E-Explorer is the general public rather than developers, therefore the UI / UX must be approachable in that anyone, even those without in-depth knowledge on blockchain, can easily browse an account or specific transaction.
Second is connectivity of related data. Developers often find needs to check the transactions along with the contents of the block in the corresponding transaction. In existing Block Explorers, this job was not handy. However, in the E-Explore, we implemented functions to obtain detailed information by clicking on related data such as block, batch and transactions.

Features
* •	Get block information
* •	Get batch information
* •	Get transaction information
* •	Get block detail
* •	Get batch detail
* •	Get transaction detail
* •	Search transaction using transaction id

## E-Edge
Edge is a web service that allows developers who want to develop blockchain services using the EdenChain Platform to register their applications and test APIs.
Most platform-oriented technology, including Google, Facebook, and Amazon, provides a platform to make it easier for developers to use the platform. This is because using a platform for a developer means using the API provided by the platform.
EdenChain provides API calls for the various functions needed to develop block-chain services with the Enterprise Blockchain Platform, so developers need something that can handle a series of tasks related to API usage.

Features
* •	User registration
* •	Application, namespace registration
* •	API key issuance
* •	API usage stat data
* •	Control API Quota
* •	Application team member management

## ERest API Server
EAS(ERest API Server) is an API server in EdenChain platform. EAS provides all available functions to Edenchain platform user through RESTful API. Such as block, batch and transaction information. Edenchain platform user cannot access to Edenchain platform itself, instead the user is supposed to access through API server. So In that sense, EAS is a sort of interface connecting user request to Edenchain platform. On the other hands, EAS acts as a buffer to Edenchain platform because it is located in the middle of application and the platform. EAS exploits co-routine for maximum performance as well as efficient resource usage. Unlike multi-threading, co-routine does not need to have its own context, therefore, no need to do context-switching. The function of EAS is likely to be expanded as Edenchain platform is matured. So adding new function to EAS should be easy and no side-effects. 

Features
* •	API gateway
* •	Access to Edenchain platform
* •	Handle block API request
* •	Handle batch API request
* •	Handle transaction API request
* •	Search block, batch and transaction using ID
* •	Authentification

## Notice
These 3 application are the key requisites to access Edenchain platform. Edenchain platform is currently running on google cloud, and it is undergoing various tests and modifications to enhance the performance. Once our target performance is reached, Edenchain testnet codes will be uploaded on the GitHub and open to the public. Edenchain team is working hard to make progress. Please be patient and wait for the testnet!!

## For further enquiries
For further enquiries, please feel free to join our community and ask questions. You can also submit your issue at our Github repository

