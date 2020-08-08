---
templateKey: blog-post
title: Decentralized Voting
date: 2018-09-28T15:04:10.000Z
featuredpost: false
featuredimage: /img/block-chain.PNG
description: 
tags:
  - blockchain
  - voting
  - decentralization
# testimonials:
#   - author: Joseph Stalin
#     quote: >-
#       I consider it completely unimportant who in the party will vote, or how; but what is extraordinarily important is this who will count the votes, and how.
---

> I consider it completely unimportant who in the party will vote, or how; but what is extraordinarily important is this who will count the votes, and how.
>
> -- <cite>Benjamin Franklin</cite>

Stalin's proverb is more relevant now than ever. With claims of Russia interfering the 2016 US Election, it is difficult for people to trust if they really hold power in democracy. Power lies in those few who count the votes. Whether we want it or not, we have to trust unknown people to count our votes. Is there a way to shift that trust from unknown people to us? What if there was a way we could verify that our votes were indeed counted for the candidates we voted for? More than one solution comes to my mind but the best way to tackle this problem is by making use of a public, shared and immutable ledger - **Blockchain**.

Don't run away. Blockchain is not just a hyped complicated word although if you follow cryptocurrencies, it might seem so but that is not the case. The word 'Blockchain' itself means it is a chain of blocks. Each block stores certain information and one block refers to other block by the use of unique 256 bit hash. For anyone who has taken an algorithms class, they can think of blockchain as similar to a reversed linked list. In a linked list, a head node points to the node behind it while in blockchain, a block points to the block in front of it and hence the term 'reversed linked list.' To be more precise, each block is a hash pointer since each of them contain hashes of the previous block.

![blockchain](/img/block-chain.PNG)

All the blocks after the first contain a hash of the previous block. Each block also contains transactions. 



In the above diagram, transaction is a general term. Transactions could of course mean financial (process of sending money from one to another) like that of the bitcoin blockchain. However there are lot more uses of blockchain and sending a vote from me to a candidate could also serve as a transaction.Since blockchain is a shared, public yet cryptographically secured ledger, we can use the ledger to record public votes. 

Before Election:
Voter registers and receives voter ID

During Election:
Voter visits the designated voting station, submits the vote
Voter ID and Randomly generated Ballot ID are hashed
Hash and Plaintext candidate choice are written to the block
Block meets majority consensus and is added to the blockchain

After Election:
Blockchain released to Public
Votes are counted and winners are determined