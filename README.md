# Leonidcoin

Copyright (c) 2009-2012 The Bitcoin Core developers

Copyright (c) 2012-2014 The PPCoin developers

Copyright (c) 2017-2018 The Leonidcoin Core developers
License

Leonidcoin is released under the terms of the MIT license. See COPYING for more information or see http://opensource.org/licenses/MIT.

# Leonidcoin Specifications

Coin Type : POW/POS Hybrid

Algorithm : Scrypt

Coin Abbreviation : LNDC

Premine : 5 Million

Maximum coin supply : 27 Million

POW:

Block Reward : 10000 LNDC

Total POW block Reward : 10000 Block

After Block 10000 : 0 LNDC

Time between reward : 120 Second

POS:

Minimum stake age : 15 minutes

Maximum stake age : 360 days

POS Yearly interest : 10%
Intro

Leonidcoin (LNDC) is an online payment system, enabling instant payments to anyone in the world without using an intermediary. Leonidcoin can be minted by computational devices including personal computers and portable devices through PoW and PoS. Leonidcoin aims at fairness, cost effective and energy efficiency during coin minting. Leonidcoin is a hybrid PoW/PoS-based cryptocurrency that integrates two mechanisms: proof-of-work (PoW) and proof-of-stake (PoS) protocols. Leonidcoin is a CPU & GPU only. Features

PoW, the Leonidcoin proof-of-work (PoW) protocol, in addition to required computational works to be done to deter denial of service attacks, is also a network-dependent rewarding model system. The PoW rewards participants who solve complicated cryptographical questions not only to validate transactions but also to create new blocks in order to generate coins. The coins mined via PoW are adjusted and balanced by two primary mechanisms:

    stimulating network activities by issuing rewards

    mitigating redundant mining sources by reducing rewards.

    The particular designed block reward system to remove the competitive nature of mining and offer an even playing field for anyone looking to issue coins without expensive equipment - offering features such as energy saving, proof of mining.

    PoS, the Leonidcoin proof-of-stake (PoS) protocol, aims to achieve distributed consensus through operations in addition to PoW. PoS is designed such that it rejects potential attacks, for example, through accumulating a large amount of coins or offline stake time. Leonidcoin hybridizes PoW with PoS, and integrate both consensus approaches in order to acquire benefits from the two mechanisms and create a more robust payment system. PoS particularly enhances the security of REC's staking system that distinguishes itself from the original concept developed by PPCoin.

# Development Process

The master branch is regularly built and tested, but is not guaranteed to be completely stable. Tags are created regularly to indicate new official, stable release versions of Leonidcoin Core.

The developer mailing list should be used to discuss complicated or controversial changes before working on a patch set.
Testing

Testing and code review is the bottleneck for development; we get more pull requests than we can review and test on short notice. Please be patient and help out by testing other people's pull requests, and remember this is a security-critical project where any mistake might cost people lots of money.
Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to submit new unit tests for old code. Unit tests can be compiled and run (assuming they weren't disabled in configure) with: make check.

# Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the code. This is especially important for large or high-risk changes. It is useful to add a test plan to the pull request description if testing the changes is not straightforward.
Info

Bitcointalk thread: https://bitcointalk.org/index.php?topic=2731422
Disclaimer

# This is a Leonidcoin and is in no way affiliated with any government or government agency.
