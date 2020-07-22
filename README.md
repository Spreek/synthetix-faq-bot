# synthetix-faq-bot
Implementation of Discord bot for answering synthetix related questions

# Usage in channel
The bot is triggered by the prefix **!FAQ** in channels.  
The bot can answer predefined questions either by their question number of by alias.  
Examples:  
**!FAQ question 1**  
**!FAQ gas price**  

The list of all questions is shown bellow.  
All aliases are defined in: https://github.com/dgornjakovic/synthetix-faq-bot/blob/master/categories/aliases.json

# Usage in direct messaging

The bot is intended to be used in direct messaging.
It has a list of predefined commands which can be browser if 'help' message is sent to the bot.

Additonally to known commands, the bot can be asked a custom question (detected by a question mark at the end). It will search for best possible match in the list of know questions.

# Known commands

**help**  
Displays the list of known commands


**list**  
Lists all known questions

**categories**  
Lists all categories of known questions


**category categoryName**  
List all known questions for a given category name, e.g. **category Staking&Minting**

**question questionNumber**  
Shows the answer to the question defined by its number, e.g. **question 7**

**search searchTerm**  
Search all known questions by given search term, e.g. **search SNX price**


# List of questions currently available
To get the answer to a predefined question send the bot the message **question X**  
**X** being the question number, e.g. **question 21**

1  
I claimed my SNX staking rewards but I don't see them in my wallet?  
2  
How can I check exactly how many of my SNX are unlocked?  
3  
I previously locked my SNX to mint sUSD. How can I unlock my SNX?  
4  
How can I cash out my Synth gains for ETH?  
5  
How can I unlock/vest my escrowed tokens from the HAV token sale?  
6  
My wallet says I have havvens (HAV) but no SNX?  
7  
What is the current gas price?  
8  
What is the current sUSD price?  
9  
What is the current SNX price?  
10  
How to delegate claiming of SNX Rewards?  
11  
Why does my total sUSD debt fluctuate over time?  
12  
How to claim Synth Exchange Rewards without Mintr, directly using the smart contract?  
13  
How can I earn Synth exchange rewards?  
14  
How do I increase my C-Ratio (Collateralization Ratio)?  
15  
How can I claim my SNX Staking Rewards?  
16  
Now that I've minted sUSD, what can I do with it?  
17  
How can I receive SNX staking rewards?  
18  
Do I need to register or open a trading account to use Synthetix.Exchange?  
19  
How can I see how many fees were generated by a trade?  
20  
How can I make a trade on Synthetix.Exchange?  
21  
Why are my transactions failing?  
22  
Why am I blocked from claiming rewards?  
23  
Why are Synthetix transactions so expensive?  
24  
I don't have MetaMask, Trezor, Ledger, or Coinbase Wallet. How can I use the Synthetix dApps?  
25  
Why are transactions taking so long to process?  
26  
Why did I get a less synths on trade? 
27  
I am not able to burn my sUSD because the transaction keeps failing.  
28  
How to interact with a Synthetix contract using Metamask Mobile Wallet (Android/IOS)?  
29  
How often are prices updated? And where is the price feed/oracle coming from?  
30  
How can I see all of the Synths I own?  
31  
Where can I find a list of all the contracts?  
32  
Why is there a minimum deposit of 50 sUSD into the Depot?  
33  
What's the minimum amount of SNX to stake?  
34  
Where do Synth price feeds come from?  
35  
Why is it important to incentivise people to create a Synth liquidity pool?  
36  
Why aren't my SNX tokens showing up in Etherscan (or another platform)  
37  
Why does the number of my staked SNX fluctuate?  
38  
What is Curve Stablecoin Pool?  
39  
What are the rules for transferring SNX or synths?  
40  
What are SIPs & SCCPs?  
41  
What are inverse synths (iSynths)?  
42  
What is SNX inflation schedule?  
43  
Is SNX Liquid?  
44  
What is Discord Tip Bot  
45  
Why Is Gas So High  
46  
how can I use my sUSD?  
47  
What is layer 2?  
48  
What are chanlink oracles?  
49  
Can I use ether as collateral?  
50  
How to Trade?  
51  
How do I cancel a pending or stuck transaction?  



# List of aliases currently available
Use them in channels with **!FAQ alias**, e.g. **!FAQ gas price**.  

* gas price  
* gas  
* SNX price  
* snx  
* peg  
* snx unlock  
* havven  
* inflation    

