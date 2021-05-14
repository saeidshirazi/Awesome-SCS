
# Awesome Smart Contracts Security [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A curated list of awesome Smart contracts security references, guidance, tools, research and more.


## Table Of Contents


* [Tools](#security-analysis-tools)
* [2020 Papers](#2020-papers) 
* [2019 Papers](#2019-papers) 
* [2018 Papers](#2018-papers) 
* [2017 Papers](#2017-papers)
* [2015 Papers](#2015-papers)
* [Security SCI(E) Journal list](#security-sci(e)-journal-list)
* [Links / Tutorials](#links--tutorials)
* [References](#references)

* [Learning](#learning)
  * [Security references](#security-references)
  * [Insecurity references](#insecurity-references)
  * [Capture the Flag and Wargames](#capture-the-flag-and-wargames)
    * [Writeups](#writeups)
  * [Coordinated disclosure](#coordinated-disclosure)
  * [Blogs](#blogs)
  * [Notable blog posts](#notable-blog-posts)
  * [Conference talks](#conference-talks)
  * [Podcasts and Episodes](#podcasts-and-episodes)
    * [Podcasts](#podcasts)
    * [Episodes](#episodes)
* [Tools](#tools)
  * [Visualization](#visualization)
  * [Linters](#linters)
  * [Bug finding tools](#bug-finding-tools)
  * [Verification tools](#verification-tools)
  * [Reversing tools](#reversing-tools)
* [Communities](#communities)
* [Other Awesome Lists](#other-awesome-lists)

## Learning

### Security references

* [Comprehensive list of known attack vectors for Solidity](https://blog.sigmaprime.io/solidity-security.html)
* [Consensys Best Practices](https://github.com/ConsenSys/smart-contract-best-practices)
* [Decentralized Application Security Project](https://www.dasp.co/)
* [Solidity Security Considerations](https://solidity.readthedocs.io/en/latest/security-considerations.html)
* [Solidity v0.5.0 Breaking Changes](https://solidity.readthedocs.io/en/latest/050-breaking-changes.html)

### Insecurity references

* [Awesome Buggy ERC20 Tokens](https://github.com/sec-bit/awesome-buggy-erc20-tokens)
* [EVM Analyzer Benchmark](https://github.com/ConsenSys/evm-analyzer-benchmark-suite)
* [Not So Smart Contracts](https://github.com/trailofbits/not-so-smart-contracts)

### Capture the Flag and Wargames

* [Capture the Ether](https://capturetheether.com/)
* [Ethernaut](https://ethernaut.zeppelin.solutions/)
* [EtherHack](https://etherhack.positive.com/)
* [SI Blockchain CTF](https://blockchain-ctf.securityinnovation.com/)

#### Writeups

* [Hands on the Ethernaut CTF](https://blog.trailofbits.com/2017/11/06/hands-on-the-ethernaut-ctf/) - Writeups for various Ethernaut CTF challenge contracts.
* [Ethernaut - Naught Coin (ERC20) Exploitation](https://medium.com/coinmonks/ethernaut-naught-coin-erc20-exploitation-218c86bb953b) - Writeup for a vulnerable ERC20 from the Ethernaut CTF.
* [EtherHack CTF Writeup](https://blog.positive.com/phdays-8-etherhack-contest-writeup-794523f01248) - Writeup for EtherHack CTF challenges.
* [PolySwarm Smart Contract Hacking Challenge Writeup](https://raz0r.name/writeups/polyswarm-smart-contract-hacking-challenge-writeup/) - Demonstrates advanced use of Manticore

### Coordinated disclosure

* [Blockchain Security Contacts](https://github.com/trailofbits/blockchain-security-contacts) - Security contact info for blockchain projects

### Blogs

* [Hacking Distributed](http://hackingdistributed.com/) - Emin Gün Sirer, professor in Cornell Tech’s IC3 lab focused on blockchain security.
* [Phil Does Security](https://pdaian.com/blog/) - Phil Daian, grad student behind KEVM, Hydra, and other Ethereum academic projects
* [Trail of Bits](https://blog.trailofbits.com/) - Cybersecurity R&D firm with a blockchain security practice
* [Martin Holst Swende](http://swende.se/) - Martin Swende, programmer and appsec consultant
* [SmartDec blog](https://blog.smartdec.net/) - Company blog about security issues and practices within blockchain ecosystem

### Notable blog posts

* [Contract upgrade anti-patterns](https://blog.trailofbits.com/2018/09/05/contract-upgrade-anti-patterns/)
* [How the winner got Fomo3D prize — A Detailed Explanation](https://medium.com/coinmonks/how-the-winner-got-fomo3d-prize-a-detailed-explanation-b30a69b7813f)
* [How to debug Solidity Smart Contracts with Tenderly and Truffle](https://medium.com/tenderly/how-to-debug-solidity-smart-contracts-with-tenderly-and-truffle-da995cfe098f)
* [Lashing out at a Spank Channel](https://medium.com/coinmonks/lashing-out-at-a-spank-channel-2b42b23f0dc6)
* [Malicious GasToken Minting](https://medium.com/level-k/public-disclosure-malicious-gastoken-minting-236b2f8ace38)
* [Missing return value bug in ERC20 tokens](https://medium.com/coinmonks/missing-return-value-bug-at-least-130-tokens-affected-d67bf08521ca)
* [Not A Fair Game – Fairness Analysis of Dice2win](http://blogs.360.cn/post/Fairness_Analysis_of_Dice2win_EN.html)
* [Initial Formal Verification of Ethereum Casper Protocol](https://runtimeverification.com/blog/runtime-verification-completes-formal-verification-of-ethereum-casper-protocol/)
* [Security considerations for Shamir's secret sharing](https://ethresear.ch/t/security-considerations-for-shamirs-secret-sharing/4294)
* [SmartDec smart contract audit beginner's guide](https://blog.smartdec.net/smartdec-smart-contract-audit-beginners-guide-d04cc7f1c571)
* [The Anatomy of a Block Stuffing Attack](https://osolmaz.com/2018/10/18/anatomy-block-stuffing/)
* [The phenomenon of smart contract honeypots](https://medium.com/@gerhard.wagner/the-phenomena-of-smart-contract-honeypots-755c1f943f7b)
* [Use our suite of Ethereum security tools](https://blog.trailofbits.com/2018/03/23/use-our-suite-of-ethereum-security-tools/)
* [Vertcoin (VTC) was successfully 51% attacked](https://medium.com/coinmonks/vertcoin-vtc-is-currently-being-51-attacked-53ab633c08a4)

### Conference talks

| Title | Conference | Year |
| --- | --- | --- |
| [Predicting Random Numbers in Ethereum Smart Contracts](https://schd.ws/hosted_files/appseccalifornia2018/00/AppSecCali%202018%20-%20Predicting%20Random%20Numbers%20in%20Ethereum%20Smart%20Contracts.pdf) | OWASP AppSec | 2018 |
| [Blockchain Autopsies - Analyzing Smart Contract Deaths](https://github.com/trailofbits/publications/tree/master/presentations/Blockchain%20Autopsies%20-%20Analyzing%20Smart%20Contract%20Deaths) | Blackhat USA | 2018 |
| [Rattle - an EVM binary analysis framework](https://www.trailofbits.com/presentations/rattle/) | reCON | 2018 |
| [Blackhat Ethereum](https://github.com/trailofbits/publications/blob/master/presentations/Blackhat%20Ethereum) | CanSecWest | 2018 |
| [Smashing Ethereum Smart Contracts for Fun and Profit](https://github.com/b-mueller/smashing-smart-contracts) | HITB Amsterdam | 2018 |
| [Automatic Bug Finding for the Blockchain](https://github.com/trailofbits/publications/blob/master/presentations/Automatic%20bugfinding%20for%20the%20blockchain) | EkoParty | 2017 |

### Podcasts and Episodes

#### Podcasts

* [CoinSec Podcast](https://coinsecpodcast.com/)
* [The Smartest Contract](http://www.thesmartestcontract.com/)
* [Zero Knowledge](http://www.zeroknowledge.fm/)

#### Episodes

* [The Smartest Contract #15](http://www.thesmartestcontract.com/15) - Trail of Bits’ Outlook on Security w/ JP Smith
* [The Smartest Contract #8](http://www.thesmartestcontract.com/8) - Smart Contract Security and Honeypots w/ Gerhard Wagner
* [Zero Knowledge #29](http://www.zeroknowledge.fm/29) - The DAO, the White Hat Hacker Group & Giveth w/ Griff Green
* [Zero Knowledge #16](http://www.zeroknowledge.fm/16) - Talking security with JP Smith from Trail of Bits
* [Risky Business #488](https://risky.biz/RB488/) - JP Smith about all things blockchain

## Tools

### Visualization

* [ethereum-graph-debugger](https://github.com/fergarrui/ethereum-graph-debugger) - A graphical EVM debugger. Displays the entire program control flow graph.
* [Slither](https://github.com/trailofbits/slither) - Slither can map method visibility and modifiers, state variables that are read and written, calls, and can print the inheritance graph of a smart contract
* [Solgraph](https://github.com/raineorshine/solgraph) - Generates DOT graphs with function control flow of a solidity contract
* [Surya](https://github.com/ConsenSys/surya) - Generates various visual outputs of function call graphs
* [sol-function-profiler](https://github.com/EricR/sol-function-profiler) - Solidity contract function profiler

### Linters

* [Remix](https://remix.ethereum.org/) - Browser-based Solidity IDE with linting features
* [SmarrtCheck](https://tool.smartdec.net/) - A linter for Solidity and Vyper that checks code for security issues and bad practices.
* [Solhint](https://github.com/protofire/solhint) - Linter for both security and style-guide validations. It strictly adheres to the [Solidity Style Guide](https://solidity.readthedocs.io/en/latest/style-guide.html).
* [Solium](https://github.com/duaraghav8/Solium) - Linter for both security and style-guide validations. Does not strictly adhere to the Solidity Style Guide.

### Bug finding tools

* [Echidna](https://github.com/trailofbits/echidna) - Fuzzer for Ethereum smart contracts. Uses property testing to generate malicious inputs that break smart contracts.
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool for Ethereum smart contracts that includes detectors for common security flaws
* [Mythril OSS](https://github.com/ConsenSys/mythril/) - Open-source security analysis tool for Ethereum smart contracts built around detector modules
* [Securify](https://github.com/eth-sri/securify) - Static analysis tool from ChainSecurity
* [Slither](https://github.com/trailofbits/slither) - Static analysis framework, written in Python, with detectors for many common Solidity issues

### Verification tools

* [KEVM](https://github.com/kframework/evm-semantics) - K Semantics of the Ethereum Virtual Machine (EVM)
* [Manticore](https://github.com/trailofbits/manticore) - Symbolic execution tool for EVM

### Reversing tools

* [abi-decompiler](https://github.com/beched/abi-decompiler) - EVM reverse engineering helper utility
* [ethereum-dasm](https://github.com/tintinweb/ethereum-dasm) - EVM disassembler with static and dynamic analysis abilities, including function signature lookup
* [Ethersplay](https://github.com/trailofbits/ethersplay) - Visual disassembler for EVM bytecode built on Binary Ninja
* [evmlab](https://github.com/ethereum/evmlab) - Utilities for interacting with the Ethereum virtual machine
* [IDA-EVM](https://github.com/trailofbits/ida-evm) - IDA plugin to view EVM instructions
* [Panoramix](http://eveem.org/about)
* [pyevmasm](https://github.com/trailofbits/pyevmasm) - EVM assembler and disassembler with a CLI and a Python API
* [Rattle](https://github.com/trailofbits/rattle) - EVM binary static analysis framework. Produces SSA representations of EVM code.

### Custody

* [Subzero](https://medium.com/square-corner-blog/open-sourcing-subzero-ee9e3e071827) - Subzero is an HSM-backed method for cold storage of Bitcoin developed by Square

## Communities

* [Enterprise Ethereum Alliance Security Task Force](https://entethalliance.org/working-groups/)
* [Empire Hacking Slack](https://empireslacking.herokuapp.com/) #ethereum

## Other Awesome Lists

* [Awesome AppSec](https://github.com/paragonie/awesome-appsec)
* [Awesome Ethereum Virtual Machine](https://github.com/pirapira/awesome-ethereum-virtual-machine)
* [Awesome Solidity](https://github.com/bkrem/awesome-solidity)
* [Crypto projects that might not suck](https://github.com/sweis/crypto-might-not-suck)




### 2018 papers
*Newly published papers (in this year) which are worth reading*
- **Securify: Practical Security Analysis of Smart Contracts** (2018), Petar Tsankov et al. [[pdf]](https://arxiv.org/pdf/1806.01143.pdf)
- **Ekiden: A Platform for Confidentiality-Preserving, Trustworthy, and Performant Smart Contract Execution** (2018), Raymond Cheng et al. [[pdf]](https://arxiv.org/pdf/1804.05141.pdf)
- **Smart Contracts: Security Patterns in the Ethereum Ecosystem and Solidity** (2018), Maximilian Wöhrer and Uwe Zdun. [[pdf]](http://eprints.cs.univie.ac.at/5433/7/sanerws18iwbosemain-id1-p-380f58e-35576-preprint.pdf)
- **ZEUS: Analyzing Safety of Smart Contracts** (2018), Sukrit Kalra et al. [[pdf]](https://www.ndss-symposium.org/wp-content/uploads/sites/25/2018/02/ndss2018_09-1_Kalra_paper.pdf)
- **Finding The Greedy, Prodigal, and Suicidal Contracts at Scale** (2018), Ivica Nikolic et al. [[pdf]](https://arxiv.org/pdf/1802.06038.pdf)
- **Scilla: a Smart Contract Intermediate-Level LAnguage** (2018), Ilya Sergey et al. [[pdf]](https://arxiv.org/pdf/1801.00687.pdf)
- **Formal verification of smart contracts based on users and blockchain behaviors models** (2018), Tesnim Abdellatif et al. [[pdf]](https://hal.archives-ouvertes.fr/hal-01760787/document)
- **Smashing Ethereum smart contracts for fun and real profit** (2018),  Bernhard Mueller. [[pdf]](https://github.com/b-mueller/smashing-smart-contracts/blob/master/smashing-smart-contracts-1of1.pdf)
- **Towards Verifying Ethereum Smart Contract Bytecode in Isabelle/HOL** (2018), Sidney Amani et al. [[pdf]](http://ssrg.nicta.com/publications/csiro_full_text//Amani_BSB_18.pdf)
- **SoK: unraveling Bitcoin smart contracts** (2018), Nicola Atzei et al. [[pdf]](https://eprint.iacr.org/2018/192.pdf)
- **From contracts to “smart” contracts** (2018), Massimo Bartoletti et al. [[pdf]](http://www.dmi.unipg.it/DLTWorkshop/presentazioni%20DLT%20workshop/bartoletti.pdf)
- **BitML : a calculus for Bitcoin smart contracts** (2018), Massimo Bartoletti et al. [[pdf]](https://eprint.iacr.org/2018/122.pdf)
- **Quantitative Analysis of Smart Contracts** (2018), Krishnendu Chatterjee et al. [[pdf]](http://pub.ist.ac.at/~akafshda/paperpdfs/esop2018.pdf)
- **Smart Contracts Vulnerabilities: A Call for Blockchain Software Engineering?** (2018), Giuseppe Destefanis et al. [[pdf]](http://dspace.stir.ac.uk/bitstream/1893/27135/1/smart-contracts-vulnerabilities-3.pdf)
- **Smart Contracts: Security Patterns in the Ethereum Ecosystem and Solidity** (2018), Maximilian Wöhrer and Uwe Zdun. [[pdf]](http://eprints.cs.univie.ac.at/5433/7/sanerws18iwbosemain-id1-p-380f58e-35576-preprint.pdf)


### 2017 papers
*Published papers in 2017 which are worth reading*
- **Ethereum Smart Contracts: Security Vulnerabilities and Security Tools** (2017), Ardit Dika. [[pdf]](https://brage.bibsys.no/xmlui/bitstream/handle/11250/2479191/18400_FULLTEXT.pdf?sequence=1)
- **Validation and Verification of Smart Contracts: A Research Agenda** (2017),  Daniele Magazzeni et al. [[pdf]](https://core.ac.uk/download/pdf/96761687.pdf)
- **Designing Secure Ethereum Smart Contracts: A Finite State Machine Based Approach** (2017), Anastasia Mavridou et al. [[pdf]](https://fc18.ifca.ai/preproceedings/101.pdf)
- **Ethereum: state of knowledge and research perspectives** (2017),Sergei Tikhomirov. [[pdf]](https://allquantor.at/blockchainbib/pdf/tikhomirov2017ethereum.pdf)
- **Quantstamp : The protocol for securing smart contracts** (2017), Richard Ma et al. [[pdf]](https://crushcrypto.com/wp-content/uploads/2017/10/QSP-Whitepaper.pdf)
- **Findel: Secure Derivative Contracts for Ethereum** (2017), Alex Biryukov et al. [[pdf]](https://orbilu.uni.lu/bitstream/10993/30975/1/Findel_2017-03-08-CR.pdf)



### 2015 papers
*Published papers in 2015 (2015 is when smart contract was born) which are worth reading*
- **Making Smart Contracts Smarter** (2016), Loi Luu et al. [[pdf]](https://eprint.iacr.org/2016/633.pdf)
- **Short Paper: Formal Verification of Smart Contracts** (2016), Karthikeyan Bhargavan et al. [[pdf]](https://www.cs.umd.edu/~aseem/solidetherplas.pdf)
- **A Survey of Attacks on Ethereum Smart Contracts (SoK)** (2016),Nicola Atzei et al. [[pdf]](https://eprint.iacr.org/2016/1007.pdf)
- **Writing Secure Smart Contracts** (2016), IC3. [[pdf]](http://upyun-assets.ethfans.org/uploads/doc/file/f035d9aa385448f280a785715fff89e0.pdf?_upd=devcon-ic3.pdf)
- **Step by Step Towards Creating a Safe Smart Contract: Lessons and Insights from a Cryptocurrency Lab** (2015), Kevin Delmolino et al. [[pdf]](https://eprint.iacr.org/2015/460.pdf)

* * * *

### Security SCI(E) Journal list

* IEEE Transactions on Information Forensics and Security [[web]](http://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=10206)
* Computer & Security[[web]](http://www.elsevier.com/wps/find/journaldescription.cws_home/405877/description#description)
* IET Information Security[[web]](http://www.ietdl.org/IET-IFS)
* ACM Transactions on Information and System Security[[web]](http://tissec.acm.org/)
* International Journal of Information Security[[web]](http://www.springerlink.com/content/107927/)
* Security and Communication Networks[[web]](http://www.wiley.com/bw/journal.asp?ref=1939-0114)
* IEEE Security & Privacy[[web]](	http://www.computer.org/portal/web/security/home)
* IEEE Transactions on Dependable and Secure Computing [[web]](http://www.computer.org/tdsc/)
* Security and Communication Networks[[web]](http://onlinelibrary.wiley.com/journal/10.1002/(ISSN)1939-0122)
* Computer Fraud & Security[[web]](http://www.elsevierscitech.com/nl/cfs/home.asp )

## Contributing

We welcome contributions that help curate this awesome list. Please refer to the [contributing guidelines](CONTRIBUTING.md) when submitting PRs. Thanks!
