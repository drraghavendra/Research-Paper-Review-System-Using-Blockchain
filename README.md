#SolidityBlockchainBasedimplementationofpeerreviewsystem.

Objective The idea is to build a platform, say SARA to provide BaaS (Blockchain as a service) platform. Based on the essentials of Blockchain Technology, We, the team SARA decided to design a platform in the necessitous field such as paper publication, review industry, supply chain management, healthcare and education services on SARA network.


In recent years, many organizations have sprung up which publish journals submitted to the conferences organized by them. Such prestige system is a complex socio-economic system perpetuated by journals and researchers themselves by rewarding publication in prestigious journals and punishing a lack thereof. It is self-reinforcing and is very difficult to remove. Hence there is a need of a new reputation ecosystem which can assure the credibility of the papers published and gain the trust. The system aims at creating Decentralised Autonomous Organisation (DAO) which encourages peer review and creates its own reputation ecosystem to provide an alternative to the current prestige system that dominates academic publishing with detrimental consequences. Information is stored on the Ethereum blockchain to allow version control of documents and provide redundancy and resiliency to the information in the network.

The review platform of the SARA network implements the Blockchain technology in order to ensure feedback legitimacy and as a backbone for the economic model which ensures that all feedback is genuine and tamper proof.

During the development of the peer review platforms, SARA network noticed the importance of the review or audit activities of the processes or the standards in Traceability system so that we have decided to utilize SIRI platform in Supply Chain Management which mainly focuses on Traceability.

SARA tokens shall be the native token of the system, with the purpose of tokenizing the review industry as well as the Supply Chain Management. In traditional systems, the contributors of the system do not get any instant reward for reviewing, hence we made this system completely incentivised using cyptocurrencies and smart contracts using self created reward distribution function.

#SARAARCHITECTURE 

![alt image](https://github.com/Apollo9999/SARA_REVIEWMANAGER/blob/main/SARA%20ARCHITECTURE.png)

Implementation

Tokens(ETH and SAT)

Our project is different from most other Blockchain projects since two tokens are required for the system to function smoothly. ETH is the Ethereum token which is linked to our own created token SAT for internal mechanism vital to the functioning of the platform. ETH is mainly the transaction fee for every transaction on Ethereum Blockchain whereas SAT token will be exclusively used inside the SARA network. This approach allows for a stable exchange rate. All interactions between platform, users, stakeholders and companies is based on this approach. We understand that as more and more people use our platform, the demand of the SAT token will become higher than the supply and it’s price on exchanges will start to grow. The system design ensures that the currency rate of SAT should not be affected by the market. To accomplish this, we have decided to make 1 SAT equals to 10 INR for now. It will be later decided on Crowdfunding.

Design

The main public Ethereum decentralized network, which uses the concept of smart contract, is chosen to serve as the decentralized settlement layer of the SARA Platform with SAT Token and provide transparency of transactions, submission of documents and reviews. SARA Platform introduces a hybrid architecture approach, bridging between public Ethereum chain and the high performance, scalable private side-blockchain transaction services for scalable interactions with the SAT token. The key reasons for not using a purely public chain architecture are scalability and transaction fees. The current Ethereum network’s capabilities do not allow us to launch and scale the service globally due to several issues, including:

• The Ethereum network currently is theoretically capable of handling about 10 transactions per second , which is definitely not enough for the scale of millions of users (or even hundreds of thousands of users).
• Ethereum’s transaction confirmation times are significantly delayed - which affect the user experience.
• Every transaction on Ethereum blockchain is required to pay transaction fee in ETH which most likely will be costly and creating an adoption barrier for the average user.
This hybrid approach will help avoid network fees in transactions between users, avoid stress on the public network due to the large volume of transactions and improve the user experience in terms of responsiveness and latency. This design is applicable for every type of review and SIRI Supply Chain where the auditor plays the same role as the reviewer in SIRI review and mainly responsible for auditing, checking the compliance of the processes and standards of Supply Chain system.

Motivations and Economical problems

How can a company be so sure that reviews are being written by genuine clients and not competitors? Doubtlessly, reviews on the internet are important and can impact the image of a company. Besides the obvious function of feedback, reviews affect the popularity of the business among new and potential clients. This eventually attracts competitors who will try to tarnish the reputation of this rival. Meanwhile , companies have no way of knowing who writes the comments/reviews.

Economical problems can be described as follows : User Motivation: Writing a quality review is not a simple task. It requires time and effort , it involves detailed descriptions of the pros and cons of a product and a conclusion . In the light of this , the following question arises: “What does the author a review receive as a reward for their efforts?” Of course , there are people who do not need to be motivated to write a review , and yet the majority of users would prefer to be compensated for their time.

Review Credibility: If there is no incentive to write reviews , could it be that some parts of reviews are created by means of artificial intelligence? Nowadays it is not impossible to use artificial intelligence to generate several hundred of short texts that would look like they were written by a human , or simply just buy reviews.

Our platform implements several innovative technologies , most of which are based on the blockchain technology. Smart contracts let us publicly save thousands of reviews , thus making it impossible to delete or modify them. Our economic model involves the ETH and SAT tokens and helps motivate users to leave only genuine feedback. In addition , we use mathematical formulas for calculating rewards that make submitting fake reviews economically unprofitable.
Applications 1) Blockchain based paper review system. 2) Blockchain based peer review system(Blockdoor) 3) Blockchain based supply management system.

Please find the detailed explanation of above applications' design and implementation with diagrams in the attached pdf 

Possible issues

User may over populate the system by uploading many documents: The SARa platform denies such behaviour as user can be allowed to upload only limited papers in fixed time frame.

Digital Ownership of documents: Authors can digitally sign the papers using the private key.

Too much information needs to be stored on Blockchain: Complete information is not mandatory to be stored on Blockchain. Part of few data could be stored in database and only critically important information to be stored on Blockchain.

Companies purchasing reviews: This type of behaviour is not economically feasible in our system, since the review fee will grow continuously.

Companies rejecting all critical reviews: Since all reviews and the company’s rejection or approval pf them are visible to everyone on the system, companies with high rejection rates will raise suspicion.

Unauthentic user may try to change the information related to product: Our system doesn’t allow such behaviour to as for each change in the information on Blockchain, it get’s the change verified from every other nodes on the SARA network (Consensus Mechanism)


