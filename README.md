Second Hydra Airdrop
====================

Dear IOP Community,

Initially we planned to open registration for the second Hydra airdrop on Monday, January 1, 2:00 PM UTC. Due to the large amount of new members during christmas time and the increasing demand for another airdrop, we have decided to prolong this airdrop with a second round. The rewards for both rounds can be claimed together on January 7, 2:00 PM UTC. 

The first round has started with the first block after midnight on December 25 (UTC) and will end with the first block after midnight on December 31. The next round will start with the first block in the New Year (UTC) and ends with the first block after midnight on January 7.

This time, each address is awarded a fixed amount of Hydra, which is predetermined during the two rounds mentioned above. Details on the distribution method are given in the corresponding section. To claim your Hydra, please follow the instructions below. Unclaimed Hydra will be saved for distribution in a new airdrop.

Claiming HYD Tokens
===================

To take part and receive your Hydra tokens, you need a valid Ethereum address **for which you control the privat key**. You can register for the lottery using the IoPCommunityBot in our official [Telegram Channel](https://t.me/IoPofficial). Please talk to the bot using private messages, so people can use the channel for asking questions. 

The command used for claiming an IOP address is `/%register YOUR_IOP_ADDRESS YOUR_ETH_ADDRESS SIGNATURE`. In this, `YOUR_IOP_ADDRESS` is the IOP address you want to claim and `YOUR_ETH_ADDRESS` is the address you want to receive the Hydra on. `SIGNATURE` is generated by using the *Sign Message* function of your IoP Core wallet. Enter your Ethereum address in the message field, without any other symbols or whitespace. Choose the IOP address you want to register and click *Sign*. Copy the resulting signature into the command for the telegram bot. This is used to verify that you indeed own the IOP address you want to register.

A very helpful videos has been uploaded to our official Internet of People YouTube Channel, explaining how to [register for the first Hydra Airdrop](https://youtu.be/hvMySKfQZ7Q). The procedure is exactly the same for the second airdrop. The only difference is that the amount of Tokens is already fixed when you register.

Distribution Method
===================
We monitor the blockchain over a period of seven days, using 7 snapshots made with the first block after midnight each day. Addresses enter the airdrop using the balance they held for at least 4 of the 7 snapshots. With this method we want to reward people who see IOP as a project worth of long-term investment.

While our first airdrop was held as a lottery to give owners of smaller wallets a chance to win more Hydras, this time we want to reward the people that put their trust into our ecosystem, people that share our vision of people interacting and cooperating freely. For this reason we chose a distribution function that rewards addresses with balances in the medium range more than addresses with low or very high balance. An address is eligible for the airdrop if it contains more than 1 IOP. The exact details will only be revealed during the second round of airdropping to prevent people from trying to *hack* the system. However, if you have a lot of small change laying around in your wallet, we recommend to send it all to yourself in one large transaction.

I received fewer Hydras than expected
=====================================

If you find an address is credited with fewer Hydras than expected, please remember that your wallet generates change addresses everytime you send a transaction. Depending on their balance during the snapshot phases, these addresses might also be eligible. You can get a list of all addresses in your wallet--including change addresses--by running `listaddressgroupings` in the console found in your IoP Core Wallet under *Help->Debug Window->Console*. To find out which of these is eligible for registration, you can compare them against the snapshot data [here](src/data/snapshots.json). 
Registration will be open until Monday, January 14, 2:00 PM UTC. After registration closes, we will update this repository with the full registration data. 



# FAQ


If you still have questions, you should be able to find the answers here.

**Q**: What is an airdrop?
**A**: An airdrop is a distribution of free cryptocurrency to holders of a different currency. It’s a way to establish a broad base of token holders, reward a certain group of people or just generate buzz for a new token.

**Q**: Does it cost anything?
**A**: No, an airdrop is a free gift.

**Q**: Why is this airdrop happening? Who is it for?
**A**: To celebrate the long-standing partnership between IoP and Libertaria, Libertaria is rewarding members of the IoP community with a free gift of Hydra, Libertaria’s new cryptotoken.

**Q**: What is Hydra?
**A**: Hydra is Libertaria’s new cryptotoken. Eventually it will run on Libertaria’s new Hydra blockchain protocol, but for now it is an ERC20 token on the Ethereum blockchain. The address of the contract is 0xd233495c48eb0143661ffc8458eafc21b633f97f, the Token symbol is **HYD** and uses 12 digits.

**Q**: How many Hydra tokens are being airdropped?
**A**: 500,000 Hydra tokens are being distributed in this airdrop.

**Q**: Is everyone eligible to receive free Hydra tokens?
**A**: No, only IOP addresses containing a minimum of 1 IOP for at least 4 of the 7 snapshots per round are eligible to receive Tokens in this airdrop. The requirements for participation will change for each airdrop.

**Q**: Will every eligible address receive free Hydra tokens?
**A**: Yes. The minimum amount will be given here the moment it is known.

**Q**: Can I receive Hydra from my IOP on Bittrex?
**A**: No, you cannot receive Hydra tokens based on Bittrex holdings. Only IOP addresses for which you own the private keys are eligible to register for the lottery.

**Q**: What do I need to register my address?
**A**: You’ll need an eligible IOP address, an Ethereum wallet address for a wallet supporting ERC20 tokens and an IOP wallet capable of signing a message using the private key for the eligible IOP address. The official IoP Core wallet is perfect for this, exchange addresses are NOT. Another possibility is to use the Coinomi Wallet.

**Q**: Which wallets support ERC20 tokens?
**A**: There are several options, but we recommend MyEtherWallet.com. We have created a short instruction video explaining how to set up a wallet address in MEW.

**Q**: How do I register my address?
**A**: You can register your address in our official IoP Token telegram channel by messaging our bot. The bot also accepts direct messages.

**Q**: The bot says I need a signature. What’s that?
**A**: We need a cryptographic signature to verify that you own the IoP address you’re trying to register. In your IoP core wallet, select “Sign Message” from the File menu. Paste the eligible IoP address in the top bar and your ETH address in the message box. Click the Sign Message button and the signature will be generated. You can use the Copy button to the right of the signature to copy it to the clipboard.

**Q**: I’m pretty sure I had an eligible amount of tokens in an eligible IOP address. However, when I try to register the address with the bot I get a message saying “That IoP address isn't on the list of IoP addresses eligible for this airdrop. Sorry.” Why am i getting that message?
**A**: First check [this list](src/data/snapshots.json) for your address. If it’s not in the list, don’t worry. It may have been stored in a different address than you think. Go to *Help->Debug Window->Console*, enter `listaddressgroupings` and hit return. In the console window you will see all the addresses that the wallet used for your transactions. Check that list against the first list and you should find the tokens you’re looking for.gi

