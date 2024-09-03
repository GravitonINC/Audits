# **dappslap Audit Competition on Hats.finance** 


## Introduction to Hats.finance


Hats.finance builds autonomous security infrastructure for integration with major DeFi protocols to secure users' assets. 
It aims to be the decentralized choice for Web3 security, offering proactive security mechanisms like decentralized audit competitions and bug bounties. 
The protocol facilitates audit competitions to quickly secure smart contracts by having auditors compete, thereby reducing auditing costs and accelerating submissions. 
This aligns with their mission of fostering a robust, secure, and scalable Web3 ecosystem through decentralized security solutions​.

## About Hats Audit Competition


Hats Audit Competitions offer a unique and decentralized approach to enhancing the security of web3 projects. Leveraging the large collective expertise of hundreds of skilled auditors, these competitions foster a proactive bug hunting environment to fortify projects before their launch. Unlike traditional security assessments, Hats Audit Competitions operate on a time-based and results-driven model, ensuring that only successful auditors are rewarded for their contributions. This pay-for-results ethos not only allocates budgets more efficiently by paying exclusively for identified vulnerabilities but also retains funds if no issues are discovered. With a streamlined evaluation process, Hats prioritizes quality over quantity by rewarding the first submitter of a vulnerability, thus eliminating duplicate efforts and attracting top talent in web3 auditing. The process embodies Hats Finance's commitment to reducing fees, maintaining project control, and promoting high-quality security assessments, setting a new standard for decentralized security in the web3 space​​.

## dappslap Overview

Dappslap.ai is a token launching platform.

## Competition Details


- Type: A public audit competition hosted by dappslap
- Duration: 10 days
- Maximum Reward: $25,025
- Submissions: 36
- Total Payout: $17,017 distributed among 15 participants.

## Scope of Audit

## Project overview

Write here a brief project overview. What's the goal and vision of the project, main feature, and functionality?


This project uses a bonding curve to create and distribute tokens to purchasers (using SOL). Once the target amount of SOL enters the bonding curve, some SOL and tokens will be reserved as a fee for the platform, the remaining liquidity should be added to Meteora, and the bonding curve should be disabled. The project should execute according to the following parameters:

Supply of Tokens
    1,000,000,000

Escape Bonding Curve Amount (Tokens purchased by buyers)
    800,000,000

Escape Bonding Curve Token Reserve (Set aside for liquidity and platform fees)
    200,000,000

Graviton Tokens Fee (Amount of tokens platform will keep as a fee)
    6,900,000

Target USD Reserve (Collected in SOL but mapped to USD)
    $10,000.00

Escape Fee (% of Target USD Reserve)
    10.69%

Escape Fee (USD)
    $1,069.00


## Audit competition scope

Everything inside the "programs/tokens" folder is in scope.

```
|-- programs/
|   |-- tokens/
|   |   |-- Cargo.toml
|   |   |-- Xargo.toml
|   |   |-- src/
|   |   |   |-- instructions/
|   |   |   |   |-- withdraw_tokens_fee.rs
|   |   |   |   |-- init_market.rs
|   |   |   |   |-- init_token.rs
|   |   |   |   |-- init_ata.rs
|   |   |   |   |-- process_completed_curve.rs
|   |   |   |   |-- mod.rs
|   |   |   |   |-- sell.rs
|   |   |   |   |-- buy.rs
|   |   |   |-- events.rs
|   |   |   |-- lib.rs
|   |   |   |-- state/
|   |   |   |   |-- market.rs
|   |   |   |   |-- bonding_curve.rs
|   |   |   |   |-- mod.rs
|   |   |   |-- errors.rs

```



## Conclusion

The audit report for the dappslap Audit Competition on Hats.finance showcases the innovative and decentralized approach of Hats.finance in enhancing the security of Web3 projects through community-driven audit competitions. Hats.finance, committed to securing the DeFi ecosystem, leverages the collective skills of numerous auditors competing to identify vulnerabilities efficiently and cost-effectively, ensuring high-quality security assessments.

In this competition hosted by dappslap, a token-launching platform, auditors scrutinized various components of the token creation and distribution process, specifically focusing on the "programs/tokens" folder. Over a period of 10 days, 36 submissions were made, resulting in total payouts of $17,017 to 15 participants, with the maximum reward capped at $25,025.

The audit concentrated on the smart contracts involved in token management and distribution. It aimed to ensure that the bonding curve effectively controlled liquidity, reserved adequate tokens for fees, and followed specified escape parameters seamlessly. The outcome of the competition highlighted the efficacy of Hats.finance’s model in promoting security, reducing costs, and attracting top auditing talent, setting a high standard for decentralized security within the Web3 space.

## Disclaimer


This report does not assert that the audited contracts are completely secure. Continuous review and comprehensive testing are advised before deploying critical smart contracts.


The dappslap audit competition illustrates the collaborative effort in identifying and rectifying potential vulnerabilities, enhancing the overall security and functionality of the platform.


Hats.finance does not provide any guarantee or warranty regarding the security of this project. Smart contract software should be used at the sole risk and responsibility of users.

