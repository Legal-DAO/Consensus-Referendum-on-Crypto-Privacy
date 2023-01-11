# Draft of Voting Question


## 1.Crypto privacy: objects, scenarios and types

> Suggested topics for consideration/discussion
> - the scope and coverage of personal data
> - privacy and identity information in the blockchain context etc.

### 1.1 Do we need privacy protection rules for the crypto world?

A. Yes 

B. No

**Background infomation**

> Suggested topics for consideration/discussion
> - There are still few legislations tailored for blockchain. Most existing legislations relevant to blockchains are general and pricipled. Hence, it is necessary to have industry self-regulation in order to accommodate the rapid development of the blockchain industry.

There are many reasons to establish privacy protection rules for the crypto world. Firstly, there is still rare privacy-related legislation for blockchain in various jurisdictions. Most existing legislations relevant to blockchains are general and principled. Hence, it is necessary to have industry self-regulation in order to accommodate the rapid development of the blockchain industry. Secondly, one feature of blockchain transactions is that the address and the amount of transaction, which are private by nature, are accessible to all users. Everyone could therefore become a data processor of it,  and they can even summarize them into personal information such as consumption pattern, participation of project, and lifestyle. Thus, such privacy information of on-chain transaction parties could be leaked and be processed by others. However, opposite views are also prevalent. Firstly, as discussed during the nascent years of cyberspace, it's disputed whether it's necessary to tailor the law for the internet. Epitomized in Frank Easterbrook's analogy "The Law of the Horse" , the opinion that there is no need to define cyberlaw as a unique section of legal studies and litigation eventually dominated. Secondly, the disclosure  of on-chain transaction information is one of the reasons why the blockchain is trustworthy. Considering that on-chain data does not involve real identity, it should not be deemed as privacy, and there is no need to be protected. Third, the crypto world is inherently incompatible with regulation and centralization. For instance, centralized exchanges that require KYC could cooperate with the judicial authorities by freezing accounts or giving them access to certain data.  As a result, Privacy protection rules may instead become the sword of Damocles hanging over people who conduct transactions on the blockchain.

### 1.2 Do you think there is any risk that your real identity could be exposed during your on-chain activities?

A. Yes 

B. No

**Background information**
> Suggested topics for consideration/discussion
> - The underlying technology of the crypto world is the distributed ledger technology represented by the blockchain. Blockchain cannot guarantee complete anonymity , and thus leads to the risk of  personal information leakage.
 Whether your real identity is exposed during  on-chain interactions depends on following factors:
 
1. Do the on-chain data contain information that could be used to identify an individual,such as user's name? If the on-chain data is merely about the transaction, then it cannot be used to identify an individual without being associated with other data.

2. Could the on-chain data be associated with other data to identify an individual? For instance, some on-chain data demonstrate the transaction of a person. Meanwhile, that person mentions the transaction on social media. Therefore, the blockchain analysis tools that associate the information on the chain with those on social media could reveal the real identity of this person.

In general, information that does not contain the identity cannot be used to identify the specific individual without being associated with other information. 

### 1.3 As you know, when you are using Metamask to register an Ethereum account, a private key and a corresponding public key will be generated for you. The public key is stored publicly on the blockchain , while the private key is stored on your device. Do you think your public key should be protected as privacy?

A. Yes 

B. No

**Background information**

Initially, all encryption algorithms only involve one key, so both encryption and decryption could only be performed  with this one key, and such process is called symmetric encryption. However, the application scenarios of symmetric encryption are limited, thus, asymmetric encryption algorithms were created to expand the application range of encryption algorithms. The asymmetric encryption algorithms use a pair of keys, which consist of a  public key and a private key. Everyone could view the public key, but this characteristic will not affect its security adversely. The private key needs to be kept by the holder of that pair of keys and  he/she should avoid  disclosing it to other people. One classic application of asymmetric encryption is the digital signature. For example, if Alice wants to send a file to Bob, she could sign the file with her private key so that Bob can check if a malicious third party has modified the file during the transmission. And after Bob received that file, he could use Alice's previously disclosed public key to verify whether the file was sent and signed by Alice, and whether it had never been modified by others during the transmission.

### 1.4 When you use Metamask to register an Ethereum account, in addition to the public and private keys,  a unique address will also be generated. And when you initiate a transaction on the chain, the identities of both parties to the transaction are represented by their respective addresses, which are published on the blockchain . Do you think addresses should be protected as privacy?

A. Yes 

B. No

**Background information**
In the blockchain world, the address generated from the user's public key could be deemed as both the account and the identifier of the user. In a transaction, the sender and the recipient are respectively identified with their addresses. Hence, the transaction history of the address could be utilized to analyze the transaction habits of the person or entity behind the address. Based on those transaction habits, a user portrait of their owner could be made and it will be possible to infer the real identity of him/her. For example, a person frequently makes purchases from the same merchant, and all purchase records of the merchant are available to the public. Then, the spending habits of this person could be inferred from the above information. This inference could be helpful to find the person's identity in real life, or if not, to narrow down the scope.

### 1.5 When you initiate a transaction on a blockchain, the transaction amount will be published on the it. Do you think the transaction amount should  be protected as privacy?

A. Yes 

B. No

**Background information**

1. Currently, the transaction amount of each transaction is public if the transaction does not happen on the privacy chain. However, public transactions, especially when the transaction amount is big,  sometimes could cause abnormal market reactions. For example, when Vitalik, the founder of Ethereum, dumped 25 trillion SHIT tokens worth about $33,000 with his wallet on the decentralized exchange Uniswap, it triggered a sharp drop in SHIT, which fell by more than 50% in 24 hours.

2. There are some common scenarios where disclosing the transaction amount is also likely to cause many problems. For instance, many Web3 companies pay their employees with cryptocurrency, thus in this case the  salary of all employees will be accessible to the public. As a result, it may bring problems to the company's operation and management. In addition, some business services that transact through cryptocurrency also need confidentiality of transaction amounts.

### 1.6 When you use crypto wallets such as Metamask to connect to websites and sign your signature, do you think it will cause personal privacy leakage?

A. Yes 

B. No

**Background information**

Crypto wallets contain sensitive information such as private keys and mnemonic of our accounts, which are equivalent to our  passwords of bank accounts. According to Metamask's latest privacy announcement, when using Infura, a platform that allows DApps to quickly access Ether without needing to run local Ether nodes(Metamask uses Infura by default), the user's IP address as well as Ethereum addresses are collected by Infura. This means that Infura has access to the correlation between the Ethereum address in a user's wallet and his or her IP address, making it available for potential  use in judicial or regulatory scenarios.

### 1.7 When you invoke smart contracts, such as DeFi contracts for mortgages and loans, do you think there will be any privacy leak?

A. Yes 

B. No

**Background information** 

Each smart contract has an address. And the invocation of smart contract is a special transaction where the initiator of the transaction is the user and the receiver is the smart contract. When a private address frequently interacts with a smart contract, others may be able to infer personal information of that private address owner through that smart contract's functions

### 1.8 Do you think that the account/address information of important centralized crypto financial institutions such as exchanges and funds should be more transparent so that it can be monitored by the public？

A. Yes 

B. No

**Background information**

> Suggested topics for consideration/discussion
> - the  regulatory status quo of the information of financial institutions' accounts/addresses (e.g. some data obtained from relevant research)
> - Current protection of the information of individual user accounts/addresses

From the collapse of FTX, we realize that centralized crypto exchanges are in black box, being more opaque than tradition finance . In the crypto world, which takes transparency, fairness, and decentralization as the highest priority, the existence of such an uncontrolled leviathan is a per se risk. Although exchanges subsequently launched the Merkle Tree proof to prove that they haven't  misappropriated user deposits and reserves, it cannot prove that they have no threat to the transparency, fairness, and safety of the crypto world(it's still insufficient for this purpose). But this move does have positive implications. It indicates a trend toward transparency.

### 1.9 Do you think  on-chain analysis tools should be restricted from analyzing individual users' accounts/addresses, such as generating user profiles according to their on-chain activities , or  they should at least be restricted from publishing them ?

A. Yes 

B. No

**Background information** 

[TBD]

### 2. Privacy protection for blockchain data
**Background information** 

> Suggested topics for consideration/discussion
> - The application of the principles of data processing, such as the principle of data minimization under Web3 

Currently, most of the on-chain data of the public chains is information about transactions, including the accounts/addresses of both parties to the transaction and the amount of the transaction. This information is public and can be accessed through the blockchain browser. This leads to: 

1. If a person's account/address information is known to others, every past and future transaction he has made through that account/address will be known.

2. If a person's account/address information is known to others, every past and future transaction he has made through that account/address will be known. By observing the historical transactions of an account/address, it is possible to portray its owner's profile and even trace the identity of the account/address owner. Besides, according to the characteristics of the current public chain, the information on the chain cannot be changed, which means that the user cannot avoid leaking information by deleting it.

In addition, if on-chain transactions are conducted through third-party service providers such as wallets, centralized exchanges, etc., information such as the IP address of the user may be collected. Although there is a high probability that such information will not be stored on the chain, the anonymity of the transaction is further diminished in the event that the service provider misbehaves or the information is leaked due to hacking.

It is difficult for the above status to satisfy the GDPR's provisions on the privacy rights of individuals, which include deletion, portability, corrections, the right to be forgotten, and the right to object. However, we cannot assume that the protection framework of GDPR is compatible with Web3 personal information protection. The differences in data storage and data management between Web3 and Web2 cause GDPR, which is designed in the context of Web2, to be unsuitable for Web3. 

### 2.1  Are you informed / do you consent that your transaction information and other on-chain data will remain permanently on the blockchain and cannot be deleted or changed?

A. I am not informed

B. I am informed and I consent

C. I am informed but I don't consent

**Background information**

> Suggested topics for consideration/discussion
> - The unique data storage method of the distributed ledger technology makes on-chain data public and transparent
> - Treatment of personal information for common public blockchians, e.g. The disclosure of transaction address and balance on the Ethereum blockchain
> - How does the factor of user consent impact their data rights?

According to GDPR, a person has the right to require the data controller to erase personal data concerning him or her without undue delay under certain conditions. If the controller has made the personal data public,the controller should take reasonable steps to inform controllers who are processing the personal data that the data subject has requested the erasure by such controllers of any links to, or copies or replications of, that personal data. 
The prerequisite for the person to exercise the right to erase is that the data controller shall inform the method and conditions for exercising the right, which is also the requirement of the principle of transparency.

However, for the data on the chain, due to the distributed ledger, all the data on the chain is fully stored and made public by all nodes, so the data on the chain cannot be deleted technically.

### 2.2 Are you informed /  do you consent that your transaction information and other on-chain data, including the accounts/addresses of both parties and the transaction amount, can be publicly queried by anyone?

A. I am not informed

B. I am informed and I consent

C. I am informed but I don't consent

**Background information**

For example, the information about the transaction of purchasing an NFT is accessible to the public, so everyone can look up the etherscan to find the purchaser address, seller address, transaction amount, transaction time, and other information about this transaction. With the assitance of information on Web2's social media and the usage scenario of that NFT, the identity information of the buyer might be disclosed, even though Web3's user identity information is anonymous.

### 2.3 When you use Web3 applications such as Metamask wallet, should it expressly inform you the way they store and process data (such as on a blockchain or centralized servers), and ask for your consent regarding it?

A. Yes 

B. No

**Background information**

> Suggested topics for consideration/discussion
> - Under Web2, online platforms meet their data complicant obligation through privacy policies, which expressly inform users how they process, such as collect, utilize and store personal information, and the informed consent clause is at the core of them.
> - Under Web3, how could applications protect users' right to be informed and get users' consent? In addition, what should be disclosed in privacy policies?

According to data protection laws in most countries, data storing and processing require the consent of the user. In order to ensure that the user's consent is voluntary and clear, the data controller shall inform the user in advance. The context of the notifciation usually includes the identity and the contact details of the controller, the contact details of the data protection officer, the purposes of the processing, the location of storage, the storage period, the measures taken by the controller to protect data security and so on. In the Web2 era, this kind of notification is often achieved through privacy protocols.

For the Web3 service providers, they need to inform users of traditional items, such as types of data (including information users provide and information providers collect automatically), use of data, disclosure/sharing of data, international transfer, the retention and security of data, rights of data subject, teenager’s protection and so on.

Besides, due to the particularity of blockchain technology, for Web3 services, additional attention should be paid to the following key points:
1. Data on the blockchain:

1.1 Service providers shall distinguish which data is stored on the blockchain and which is not and shall notify users of the following things:
  
1.1.1 Data on the blockchain is publicly visible and/or accessible.
    
1.1.2 Data on the blockchain cannot be edited or deleted technically.
    
1.2 If the service providers only provide application service on the blockchain, they cannot custody or control over blockchains, and cannot be responsible for the security of data on the blockchain.
  
2. Providers shall illustrate where and how the data is stored in detail.

3. It’s better for the providers to inform users that users should be careful about the security of private keys and wallet seed.

4. Although the data on the blockchain is public, according to current regulations (e.g. GDPR.),  service providers still need to inform users when processing public personal data.

### 2.4 Who should be held accountable for the integrity, confidentiality,  ability to be erased etc., of your on-chain data and is obliged to protect your data rights?

A. Yourself

B. Every nodes

C. a designated third party

**Background information**

> Suggested topics for consideration/discussion
> - The difference between traditional data storage structures and decentralized distributed storage and their impact on data protection and the impact of who controls the data on users' rights to data.
> - In the traditional context, user data is controlled under the unified control of a centralized controller, and existing data protection laws (e.g., GDPR) require data controllers and processors to protect the data to a certain extent and fulfill obligations on data subjects. Data subjects can request data controllers to delete and modify their data.
> - However, in the context of the public chain, the distributed storage technology makes there is no centralized data controller, so once the data is leaked, the user cannot claim the corresponding data rights from the data controller.

In traditional data privacy law, the centralized system of responsibility is adopted. In traditional data law, a centralized system of responsibility is adopted. Generally, the obligation related to data processing would be undertaken by the data controller/processor in this system. They determine the purpose for which the data is processed. In the context of blockchain, following scenarios could be discussed:

1.  In a permissioned blockchain or consortium Blockchain, the relevant entity on the chain may be able to act as joint controllers under the traditional data law since the blockchain access requires permission.

2. But in the context of the public chain, under the decentralized and distributed storage feature of blockchain, no party could decide the purpose of processing the relevant data. Thus, there is no responsible data controller/processor.

3. In addition, until now, many DApps still store log data and other data on centralized servers, so operators of these DApps should be responsible for this off-chain data.

## 3. Privacy-preserving tools/services
### 3.1 Do we need privacy-preserving tools/services?

A. Yes 

B. No

**Background information**
> Suggested topics for consideration/discussion
> - How could technologies such as zero-knowledge proof, privacy enhancing computation protect on-chain privacy, and allow/guarantee flow of data on the blockchain.

Protecting your privacy on-chian can be easily ignored at the beginning of your crypto journey when you start  purchasing digital assets. Seriously speaking, you will be an easy target of cybercrime and theft.

Privacy will be more important when it comes to reality if your sensitive transactions are revealed to the public which you are not intending to do. You might use crypto to pay for sensitive products, salary incomes, medical bills, financial accounts, children's education expenses, or information subscriptions that you would rather not tell, all of which after discovery could put you into a dangerous position for blackmail or harassment, or to a spotlight position for embarrassment and awkwardness.

### 3.2  Who do you favor providing privacy-preserving services? Who do you favor as a  privacy preserving service provider?

A. Decentralized entities, such as DAOs

B. Centralized entities, such as corporations

**Background information**

> Suggested topics for consideration/discussion
> - Compliance risks and potential legal liabilities for providers of privacy-preserving services

DAO is the organizational structure  of Web3. It operates on the principle of   "Code is Law", instead of relying on rules and laws, which guarantees the decentralized autonomous operation on-chain through smart contracts and blockchain technology. Unlike a centralized corporate entity with a centralized management team that makes top-down decisions, DAO is dominated by decentralized community members and makes collective decisions through a bottom-up approach. A DAO is jointly managed, proposed, voted on, and decided by community members. The entire process will be recorded on the blockchain to ensure the process is open and transparent and all members have access to information. In contrast, a centralized corporate entity makes decisions through a centralized team composed of the CEO and senior executives in the form of shareholder meetings, board of directors etc, representing the will of a small group of people. The process is opaque, and the meeting minutes are not necessarily open, only accessible to a small group.

Based upon the above, while it seems feasible to maintain privacy protection/service tools through  the  "consensus" of DAO members, DAO's  legal compliance issues have to be considered.

Firstly, major Web3 jurisdictions do not explicitly recognize the DAO as a legal entity, which leaves  DAOs in an ambiguous and awkward position. For example, Tornado Cash, a virtual currency mixer that operates on the Ethereum blockchain and indiscriminately facilitates anonymous transactions by obfuscating their origin, destination, and counterparties, with no attempt to determine their origin., was sanctioned by the OFAC for assisting criminals which are a threat to U.S. national security. Tornado Cash is a on-chain smart contract instead of a legal entity, it is denied access to OFAC for sanctions relief. In addition, it is unable to meet its KYC, anti-money laundering AML compliance obligations under FinCEN and the U.S. Bank Secrecy Act as a on-chain smart contract.

Secondly, DAO members may be jointly and severally liable for DAO's behaviors, which may limit members' participation in DAO governance. We can find the case CFTC v. Ooki DAO in this regard. However, corporate legal entities rarely require their shareholders to bear joint liability.

Thirdly, the reality is that there is currently no perfect option to legally set up a DAO. Each option has its own drawbacks, and each option is complex. Unlike corporate legal entities, each jurisdiction provides a clear path for them.

At present, providing privacy protection through centralized legal entities can clearly fulfill regulatory compliance, such as KYC, AML, etc., but it can address the problem of the "evil of the minority". Maybe after the definition of DAO is further clarified, providing privacy protection/service tools with a "consensus" of DAO can be a better choice.

### 3.3 Are you willing to accept regulatory friendly privacy-preserving solutions?

A. Yes 

B. No

**Background information**

> Suggested topics for consideration/discussion
> - Explain how each type of solution resolves the conflict between regulation and privacy protection (this resolution is often at the expense of a partial degree of decentralization) and help users clarify the boundaries of their need for privacy protection.

Currently, the following regulatory-friendly privacy protection schemes exist:

1. Using permissioned blockchain(i.e., consortium blockchain): Unlike the public chain, the consortium chain sets strict identity authentication and access control of nodes and users. In the consortium chain, any entity needs permission to enter this blockchain, which will sacrifice decentralization. Using permissioned blockchain(i.e., consortium blockchain): Unlike the public chain, the consortium chain sets strict authentication and permission control on the access of nodes and users. In the consortium chain, any entity needs permission to enter this blockchain, which will sacrifice decentralization. However, in many scenarios, there is no need to use the public chain. For enterprises, once they use public chains, they will lose control of their data. Therefore, most applications integrated with their traditional businesses are based on consortium chains. For example, some enterprises choose to combine the supply chain with the consortium chain, which enables the company to manage supply chain data through permission control. It could improve the efficiency of supply chain management while ensuring that the supply chain data cannot be tampered with. The example indicates that the data controller and processor in the consortium chain are relatively easy to determine, which helps traditional data law to find the legal entity of responsibilities and obligations.

2. Using a privacy solution fulfilling regulatory obligations: On August 8, 2022, the U.S. Department of the Treasury's Office of Foreign Assets Control (OFAC) sanctioned virtual currency mixer Tornado Cash and added it to the SDN List. However, Zcash, the project that provides a service to conceal transaction information, has yet to be sanctioned despite years of existence. One possible reason for this difference might be that Zcash balance the regulation obligations and the privacy protection. Firstly, revealing transaction information is optional in Zcash, i.e., Zcash allows people to selectively share address and transaction information(including the sender and the recipient) for auditing or regulatory compliance. Besides, Zcash provides an option that allows users to create auditor keys, while regulators who receive auditor keys could review and verify transactions.

3. Using third-party tools for monitoring: TRM Labs, for example, can monitor an address you want to interact with so that it can monitor all the hundreds of addresses that have transactions with the address you want to interact with. Subsequently, big data screening could be executed to prove whether it is a secure address. Meanwhile, it could free Defi protocols from conducting KYC with all the users. These characteristics make the third-party tools a solution that could balance regulation and privacy.
