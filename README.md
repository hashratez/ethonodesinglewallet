# ethonodesinglewallet
A smart contract that gathers all your Etho Node payments into a single address.

USE AT YOUR OWN RISK.  I WILL NOT PROVIDE ANY SUPPORT OF THIS CONTRACT.

Each Etho Node requires a wallet to be funded for its deposit.  10 nodes, 10 wallets.  If you run a lot of nodes this can be burdensome to manage your payments. With this smart contact, it creates a wallet address (it is a contract address that is used as a wallet address) that you fund.  When the node payment is made, this smart contract forwards the payment to the wallet that deployed it. 

Note, the threshold for payment is anything less than 100 ETHO.  So if you send 99 ETHO to the created contract address, the ETHO wil be forwarded to the address that deployed it.  If you send MORE than 100, it will stay in the contract (as needed for Service Node 5000 ETHO, Master Node 15000 ETHO, Gateway Node 30000 ETHO).

You can recover the deposit by interacting with the conract and using the withdrawl function

CREDIT: This Smart Contract was created by Dev-James for my use.  LOL I am not smart enought to write anything like this:)>
