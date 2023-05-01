# Optimistic-Rollups-Vs-Zk-Roll-ups
Ethereum scalability.
Optimistic Rollups vs ZK-Rollups: The Ultimate Comparison

Table of Contents
Crypto Basics
Optimistic Rollups vs ZK-Rollups: The Ultimate Comparison
By Ivan Cryptoslav
9m
Created 4w ago, last updated 4w ago
Optimistic rollups vs ZK-rollups: which one will prove to be a better solution to Ethereum's scalability issues?


Optimistic Rollups vs ZK-Rollups: The Ultimate Comparison
Table of Contents
What Are Rollups?
What Are Optimistic Rollups?
What Are ZK-Rollups?
Advantages And Disadvantages of Optimistic Rollups
Advantages and Disadvantages of ZK-Rollups
Optimistic Rollups vs ZK-Rollups
Optimistic vs ZK-rollups: Scalability and Costs
Optimistic vs ZK-rollups: Security
Optimistic vs ZK-rollups: Latency
Optimistic vs ZK-rollups: Privacy
Optimistic vs ZK-rollups: Validity Proof
Optimistic vs ZK-rollups: Readiness for DeFi
Optimistic vs ZK-rollups: Programming Easiness
Popular Optimistic Rollup And ZK-Rollup Projects
One of the biggest challenges facing Ethereum today is scalability. More users and applications are flocking to the network, leading to congestion and high fees.
Optimistic rollups and ZK rollups are some of the most promising ways to increase throughput and lower costs. This article will compare optimistic rollups vs ZK rollups while covering:
What rollups are
How optimistic rollups work
How ZK-rollups work
The benefits and drawbacks of optimistic rollups and ZK-rollups
A comparison of optimistic rollups vs ZK-rollups
Applications of optimistic and ZK-rollups
Subscribe
Join us in showcasing the cryptocurrency revolution, one newsletter at a time. Subscribe now to get daily news and market updates right to your inbox, along with our millions of other subscribers (that’s right, millions love us!) — what are you waiting for?

What Are Rollups?
Rollups are layer-two scaling solutions that move transactions off-chain and maintain the mainnet's security and decentralization. The name rollup comes from the fact that transactions are grouped together into batches (or rolls) and then posted on Ethereum's mainchain for finality.
The main benefit of rollups is that they can significantly reduce gas fees and increase transaction speed while preserving smart contract compatibility and composability. This means that users and developers can enjoy a better user experience and more innovation on Ethereum without compromising its core values.
The main challenge of rollups is that different rollups require different ways of verifying transactions off-chain and handling disputes on-chain. Not all rollups are created equal. The two main types are optimistic rollups and ZK-rollups. They differ in their transaction verification and dispute handling and come with different benefits and drawbacks.
What Are Optimistic Rollups?
Optimistic rollups derive their name from an optimistic assumption: transactions are valid by default unless proven otherwise.

The three main components of optimistic rollups are the smart contract, the sequencer, and the validators. The smart contract acts as the bridge between the Ethereum mainnet and the second layer. It receives transaction data from the sequencer as calldata, which is stored for future verification on the blockchain.
Transactions are executed off-chain by a centralized entity called a sequencer. The sequencer publishes the data on Ethereum's main chain as calldata. The transactions don't require any proof of validity or correctness. A promise that they will be available for verification if needed is enough.

The validator network monitors the sequencer's activity and checks if any transaction violates the rules of Ethereum. This verification process can uncover invalid transactions, which can be challenged by submitting a fraud proof on-chain to challenge it. It contains evidence showing how and why the transaction is invalid. If the challenge is successful, the invalid transaction is reverted, and the sequencer is penalized.
What Are ZK-Rollups?
ZK-Rollups rely on a cryptographic technique called zero-knowledge proofs: transactions are valid by default if proven to be so. They are executed off-chain by a network of nodes generating transaction data and proofs of validity. These are then submitted to the Ethereum mainnet as calldata.
ZK-rollups have three main components: transactions, state commitments, and zero-knowledge validity proofs. Users sign transactions, which sends them to layer-two producing blocks and batches.
State commitments are snapshots of the current state of the second-layer blockchain. They are hashed and stored on the mainnet as calldata.

Zero-knowledge validity proofs are cryptographic proofs guaranteeing the transactions in a batch are valid and follow Ethereum’s rules and do not mess with the state of the blockchain.

Users sign transactions and send them to the operator. The operator executes transactions on the L2 according to Ethereum’s rules and updates the state accordingly. It then generates a state commitment for each block and a zero-knowledge proof for each batch of blocks. The data is submitted to Ethereum as calldata and its validity can be verified by anyone using the proofs and state commitments without running any computation or state transition.

Advantages And Disadvantages of Optimistic Rollups
The main advantage of optimistic rollups is the high potential throughput and low latency. Transactions are executed almost instantly off-chain and don't have to wait for on-chain confirmation. They also preserve smart contract compatibility and composability with Ethereum since they use the same virtual machine (EVM) and state transition rules.
The main disadvantage of optimistic rollups is the long withdrawal period, which is required for users to exit the system safely. Users need to wait for a sufficient amount of time to ensure that no fraud proofs are submitted against their transactions. Otherwise, their funds could be at risk if an invalid transaction affects their balance. This waiting period can be more than one week but can be circumvented by using specialized bridges, which allow faster withdrawals.
Advantages and Disadvantages of ZK-Rollups
The main advantage of ZK-rollups is also high potential throughput and low latency. Just like with optimistic rollups, transactions are executed off-chain and ultimately secured by the L1.
The main disadvantage of ZK-rollups is the complex cryptography and engineering structure of the rollups themselves. Consequently, they are more expensive and harder to implement than optimistic rollups. They also may not support all types of smart contracts or functionalities that Ethereum offers.
Optimistic Rollups vs ZK-Rollups
Here is a quick overview table comparing optimistic and ZK-rollups according to different attributes:


Optimistic vs ZK-rollups: Scalability and Costs
One of the main goals of rollup solutions is to increase the throughput of transactions on Ethereum and reduce the gas fees for users. Optimistic rollups and ZK-rollups achieve this goal by batching transactions and periodically submitting them to the mainnet. However, they have different trade-offs in terms of scalability and costs.

Optimistic rollups can handle more transactions per second than ZK-rollups. On the other hand, they require more gas to submit their batches to the main chain. Zk-rollups can save more gas than optimistic rollups, but they also have higher computational costs to generate their zero-knowledge proofs.

Additionally, optimistic rollups have lower entry barriers for developers and users than ZK-rollups. They support any Ethereum smart contract without modification and do not require special hardware or software. ZK-rollups, on the other hand, require developers to rewrite their smart contracts in a specific language and users to install a compatible wallet or browser extension.

