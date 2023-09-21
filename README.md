# twitter_demoContract
A smart contract with twitter like functions with dual access.

Solidity Version - >=0.5.0 <0.9.0

Author - Priyanshu Kumar

State variables - nextId
                  nextMessageId

Data Structures -
 Tweet
 -tweet id
 -tweet author
 -tweet content
 -tweet createdAt

 Message
 -message id
 -message content
 -message from
 -message to
 -message createdAt

Mappings- tweets
          tweetsOf
          conversations
          operators
          following

Functions- _tweet
           _sendMessage
           tweet (user)
           tweet (operator)
           sendMessage (user)
           sendMessage (operator)
           follow
           allow (allow operator to use account on behalf)
           disallow (disallow operator from using account)
           getLatestTweets
           getLatestofUser


Usage -
Deploy the TwitterClone contract to the Ethereum blockchain.
Users can create tweets using the tweet function.
Users can follow other users using the follow function.
Users can allow operators to use account on their behalf.
Users can disallow operators from using account.

           Security Considerations
Ensure that sensitive data such as private keys and access control are properly secured.
Implement access control modifiers to restrict functions to authorized users only.
Be cautious of gas costs, especially when dealing with large-scale data storage.
License
This Twitter Clone Smart Contract is open-source and released under the [MIT] license.

Disclaimer
This contract is provided as-is and without warranty. Use it at your own risk.
          
