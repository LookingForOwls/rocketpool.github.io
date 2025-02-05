# :question: Choosing a Platform

Alright! So you've decided to try your hand at running a Rocket Pool node. The first step of the process is to decide what kind of platform you want to run your node on. If you already have one in mind, great! You can skip to the next section. If you aren't sure yet, then read on for some information about your options.


## Full Node Requirements

A **full node** is one that runs both a full eth1 client and a full eth2 client along with the Rocket Pool stack. This is the best option in terms of decentralization, self-reliance, and consistency. It also has the highest requirements. While you *can* run Rocket Pool by using publicly available eth1 or eth2 clients (such as [Infura](https://infura.io/) or [Alchemy](https://www.alchemyapi.io/)), relying exclusively on these options is not recommended.

Here is a simple breakdown of what is required to run a full Rocket Pool node well:

- A **stable Internet connection**. The longer you stay online, the better your rewards. A spotty Internet connection will hurt your returns, and by extension, the rETH ratio growth.
- At least **1 MB/s of bandwidth**. A full node usually takes around 500 KB/s to 1 MB/s of network traffic, depending on your settings.
- **No data cap** imposed by your ISP. Running a full node will take a lot of data - we have seen reports of over 1 TB per month on chain data alone. This can be mitigated somewhat with a few settings tweaks to the ETH clients, but as a rule of thumb, don't run a full node if your Internet plan comes with a monthly data cap.
- **Stable electricity**. For the same reason as needing a stable Internet connection, you also want to have reliable power. This can be mitigated with a large UPS (backup battery) to deal with short blackouts.
- A **computer** with sufficient specs. This is pretty flexible because it *really* depends on what eth1 and eth2 client you use, and what settings you configure them with. The computer can be a local machine, or it can be a Virtual Private Server (VPS) hosted in the cloud. Read below for some more information on those two options, and how to decide which is best for you.


## Running a Local Node

If you have reliable electricity and uncapped Internet access, and are willing to build (or buy pre-made) and maintain a computer, then running a local node might be a great choice for you. With this option, you will set up a dedicated computer as a Rocket Pool node and run it locally in your own home.

Advantages:

- No monthly fees, other than utilities
- Complete control over your own machine and its data (including your wallet's key)
- Access to perform maintenance and upgrades whenever you want
- Contributes to eth1's, eth2's, and Rocket Pool's decentralization (and thus, their security)

Disadvantages:

- Requires stable, uncapped Internet and electricity
- You're solely responsible for network & computer security
- Can be challenging if you're not experienced with computer maintenance
- Vulnerable to theft

If the advantages sound like they outweight the disadvantages for you, then take a look at our Local Node Operator's Guide.


## Running a VPS on the Cloud

If you don't have a reliable uncapped Internet plan, or you just don't want to deal with building and maintaining your own physical computer, you may want to look at running a virtual private server. These are virtual servers that you rent from hosting providers, such as Amazon Web Services, Microsoft Azure, Netcup, Contabo, or other companies. Essentially, these companies will happily create and run a server for you, for a monthly fee. If you don't mind that fee and want to run a Rocket Pool node, using a VPS can be a good strategy.

Advantages:

- No maintenance, support is usually available to fix issues
- Doesn't affect your Internet plan or data cap
- Usually run in a professional data center, very little down time
- May be more cost effective than buying / building your own computer

Disadvantages:

- Makes eth1, eth2, and Rocket Pool somewhat more centralized, which weakens the security of the networks
- Monthly fees
- Servers may come with data caps, or have expensive network I/O rates
- Possible for hosts to examine your machine's contents and take your wallet's key if not secured

If those advantages sound like they outweight the disadvantages for you, then take a look at our VPS Node Operator's Guide.