# Jaeeu Kim — Security Audit Portfolio

## Profile

| | |
| --- | --- |
| Name | KIM JAEEU (김재유) |
| Nationality | Korean |
| E-mail | epist.kr@gmail.com |
| Education | INHA University — Computer Science Engineering |
| Military service | Completed |

## Experience

| Period | Organization | Role | Work |
| ------ | ------------ | ---- | ---- |
| 2024.01 – present | Zellic | Security Engineer | Web3 and Web2 service security audits (2024 – present) |
| 2021.02 – 2023.12 | Raon Secure — Core Research | Security Researcher | Mobile kernel exploitation — primary assignment (2021 – 2023)<br>Web and mobile service penetration testing (2021 – 2023)<br>Samsung Windows application and driver exploitation (2023)<br>Android virtualization technology — developed and patented (2021) |

## Skills

| Area | Level |
| ---- | ----- |
| Web3 / smart contract auditing | Professional |
| Web and mobile service penetration testing | Advanced |
| Binary reverse engineering | Professional |
| Mobile kernel and Windows application exploitation | Professional |

Everything below is the evidence behind the Zellic row above: every engagement whose findings I can still produce, with the report that backs it.

**37 published audit reports** at Zellic from 2024-02-27 to 2026-10-19, totalling **212 classified findings** — 12 critical, 22 high, 51 medium, 62 low, and 65 informational. **19 additional private reviews** are omitted at the engagement level.

Every public row links to the report itself and reproduces its published Impact table.

## At a Glance

| | |
| --- | --- |
| Reports | 37 public (+19 private reviews omitted) |
| Distinct public engagements | 34 |
| Findings (public reports) | 212 |
| Critical + High | 34 |
| Active period | 2024-02-27 → 2026-10-19 |
| Domains covered | 11 |
| Deepest coverage | Stablecoins & CDP (7), Vaults & Yield (6), Cross-Chain & Bridges (4), Liquid Staking & Restaking (4), Derivatives & Structured Products (3) |

## Where My Coverage Is Deepest

Ranked by number of engagements. "Crit+High found" counts the critical and high-impact findings reported on those engagements, including ones found by co-auditors — it measures the risk density of the work, not individual credit.

| Domain | Reports | Crit+High found | Representative work |
| ------ | ----------: | --------------: | ------------------- |
| Stablecoins & CDP | 7 | 1 | [frxUSD Ecosystem](https://raw.githubusercontent.com/FraxFinance/frax-solidity/2702e7e147212b85a28e198a7eba1c3bab9119db/src/audits/frxUSD%20Ecosystem%20-%20Zellic%20Audit%20Report.pdf), [River Smart Vault](https://github.com/Zellic/publications/blob/master/Smart%20Vault%20-%20Zellic%20Audit%20Report.pdf) |
| Vaults & Yield | 6 | 0 | [Agora Whitelabel](https://docs.agora.finance/_fern-files/agora.docs.buildwithfern.com/010148350a61b8d2cac00c92053973114230bc2b4a849cdf81f968b3acbe7413/docs/assets/Whitelabel%20-%20Zellic%20Audit%20Report.pdf), [StakeKit FeeWrapper](https://github.com/Zellic/publications/blob/master/StakeKit%20FeeWrapper%20-%20Zellic%20Audit%20Report.pdf) |
| Cross-Chain & Bridges | 4 | 7 | [Nori Bridge](https://github.com/Zellic/publications/blob/master/Nori%20Bridge%20-%20Zellic%20Audit%20Report.pdf), [Astria Bridge](https://github.com/Zellic/publications/blob/master/Astria%20Bridge%20-%20Zellic%20Audit%20Report.pdf) |
| Liquid Staking & Restaking | 4 | 1 | [Cosmos Liquid Staking Module (2025)](https://raw.githubusercontent.com/cosmos/gaia/618581e1ee1393b083a5c085cce503412f6596f6/contrib/audits/liquid-zellic-audit-25.pdf), [Cosmos SDK Liquid Staking Module](https://github.com/Zellic/publications/blob/master/Cosmos%20SDK%20Liquid%20Stake%20Module%20-%20Zellic%20Audit%20Report.pdf) |
| Derivatives & Structured Products | 3 | 16 | [Plaza Programmable Derivatives](https://github.com/Zellic/publications/blob/master/Plaza%20Core%20Protocol%20-%20Zellic%20Audit%20Report.pdf), [Alkimiya](https://github.com/Zellic/publications/blob/master/Alkimiya%20-%20Zellic%20Audit%20Report.pdf) |
| L1 / L2 Infrastructure | 3 | 4 | [Mitosis](https://github.com/Zellic/publications/blob/master/Mitosis%20-%20Zellic%20Audit%20Report.pdf), [Cosmos Group Module](https://raw.githubusercontent.com/cosmos/cosmos-sdk/e25c86fdb32927f0e6cebcc613c862d062050b27/docs/audits/group_module_audit.pdf) |
| Oracles & Automation | 3 | 0 | [Yei Finance Oracle](https://github.com/Zellic/publications/blob/master/Yei%20Finance%20Oracle%20-%20Zellic%20Audit%20Report.pdf), [Astria Shared Sequencer Oracle](https://github.com/Zellic/publications/blob/f9d9c32bd1863f17b8c47bf7fcf7c498e955e198/Astria%20Shared%20Sequencer%20Oracle%20-%20Zellic%20Audit%20Report.pdf) |
| RWA & Tokenization | 3 | 0 | [Anzen USDz & protocol-v2](https://github.com/Zellic/publications/blob/master/Anzen%20and%20protocol-v2%20-%20Zellic%20Audit%20Report.pdf), [Multiliquid EVM](https://github.com/Zellic/publications/blob/master/Multiliquid%20EVM%20-%20Zellic%20Audit%20Report.pdf) |
| Account Abstraction & Wallets | 2 | 1 | [Pocket Web Wallet (Avara)](https://aave.com/files/aave-account-audit-report-2024-03.pdf), [Xion Passkeys](https://github.com/Zellic/publications/blob/master/Xion%20Passkeys%20-%20Zellic%20Audit%20Report.pdf) |
| Lending & Money Markets | 1 | 0 | [Molend Protocol](https://github.com/Zellic/publications/blob/master/Molend%20Protocol%20-%20Zellic%20Audit%20Report.pdf) |
| Token Vesting & Governance | 1 | 4 | [MetaLeX MetaVesT](https://github.com/Zellic/publications/blob/master/Metavest%20-%20Zellic%20Audit%20Report.pdf)§ |

## Audit Reports

| Start | End | Report | Client | Tech | Team | C | H | M | L | I |
| ----- | --- | ------ | ------ | ---- | ---- | --- | --- | --- | --- | --- |
| 2026-09-23 | 2026-10-19 | [frxUSD Ecosystem](https://raw.githubusercontent.com/FraxFinance/frax-solidity/2702e7e147212b85a28e198a7eba1c3bab9119db/src/audits/frxUSD%20Ecosystem%20-%20Zellic%20Audit%20Report.pdf) · [web](https://github.com/FraxFinance/frax-solidity/blob/2702e7e147212b85a28e198a7eba1c3bab9119db/src/audits/frxUSD%20Ecosystem%20-%20Zellic%20Audit%20Report.pdf) | Frax | Stablecoin, Vault, Yield, ERC4626, Custodian, Timelock, Solidity | 2 | 0 | 0 | 0 | 7 | 13 |
| 2026-06-30 | 2026-07-20 | [Multiliquid EVM](https://github.com/Zellic/publications/blob/master/Multiliquid%20EVM%20-%20Zellic%20Audit%20Report.pdf) | Uniform Labs | Real-World Assets, Tokenization, Stablecoin, DEX, Solidity | 3 | 0 | 0 | 0 | 2 | 5 |
| 2026-05-11 | 2026-06-22 | [Nori Bridge](https://github.com/Zellic/publications/blob/master/Nori%20Bridge%20-%20Zellic%20Audit%20Report.pdf) | Nori | Cross-Chain, Bridge, Light Client, Mina, Rust, TypeScript, Solidity | 7 | 3 | 3 | 1 | 4 | 12 |
| 2026-01-30 | 2026-02-05 | [Cosmos Group Module](https://raw.githubusercontent.com/cosmos/cosmos-sdk/e25c86fdb32927f0e6cebcc613c862d062050b27/docs/audits/group_module_audit.pdf) · [web](https://github.com/cosmos/cosmos-sdk/blob/e25c86fdb32927f0e6cebcc613c862d062050b27/docs/audits/group_module_audit.pdf) | Cosmos Labs | L1, Cosmos SDK, Governance, DAO, Go | 2 | 0 | 0 | 1 | 1 | 6 |
| 2025-11-14 | 2025-11-17 | [MegaETH Predeposit](https://github.com/Zellic/publications/blob/5503c6f5d87df11b7864deef37c04bce99e367c2/MegaETH%20Predeposit%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/megaeth-predeposit) | MegaETH | Vault, Deposit, Signed Permits, KYC, L2, Solidity | 2 | 0 | 0 | 1 | 1 | 0 |
| 2025-10-13 | 2025-10-22 | [Agora Whitelabel](https://docs.agora.finance/_fern-files/agora.docs.buildwithfern.com/010148350a61b8d2cac00c92053973114230bc2b4a849cdf81f968b3acbe7413/docs/assets/Whitelabel%20-%20Zellic%20Audit%20Report.pdf) · [web](https://docs.agora.finance/security/smart-contract-audit-reports/whitelabel-stablecoins) | Agora team | Vault, Yield, ERC4626, Stablecoin, Tokenization, Solidity | 2 | 0 | 0 | 2 | 0 | 1 |
| 2025-10-13 | 2025-10-22 | [AgoraDollar (AUSD)](https://docs.agora.finance/_fern-files/agora.docs.buildwithfern.com/dec842e5c3006596d1c02bfa549af5cb141d31b06e330d70789a512ca1f0ba74/docs/assets/Agora%20Dollar%20EVM%20Oct%202025%20-%20Zellic.pdf) · [web](https://docs.agora.finance/security/smart-contract-audit-reports/agora-dollar) | Agora team | Stablecoin, Tokenization, Upgradeable Proxy, Access Control, Solidity | 2 | 0 | 0 | 0 | 3 | 0 |
| 2025-10-13 | 2025-10-22 | [Agora EVM Contracts](https://docs.agora.finance/_fern-files/agora.docs.buildwithfern.com/52ca6d21b4d0794dacb5e95bfafd8f0c5e5468f2209fbfc4b3462974dd03f93c/docs/assets/Agora%20EVM%20Contracts%20Oct%202025%20-%20Zellic.pdf) · [web](https://docs.agora.finance/security/smart-contract-audit-reports/periphery-contracts) | Agora team | Stablecoin, Access Control, Upgradeable Proxy, Solidity | 2 | 0 | 0 | 0 | 3 | 0 |
| 2025-10-13 | 2025-10-22 | [Agora Cross-Chain (LayerZero)](https://docs.agora.finance/_fern-files/agora.docs.buildwithfern.com/e43bc3c9e45e3631234ebf0db36f5a9938998dd1ebd07d6f8c9cfaf02f1ad248/docs/assets/Agora%20Cross-Chain%20%28LayerZero%29%20-%20Zellic%20Audit%20Report.pdf) · [web](https://docs.agora.finance/security/smart-contract-audit-reports/ausd-bridge) | Agora team | Cross-Chain, Stablecoin, LayerZero, OFT, Rate Limiting, Solidity | 2 | 0 | 0 | 2 | 0 | 0 |
| 2025-10-10 | 2025-10-10 | [OKX xBTC (EVM)](https://web3.okx.com/cdn/web3/security/audit/report/4081abb4c7c84fc39df7048801a21d80.pdf) · [web](https://web3.okx.com/security) | OKX | Tokenization, Wrapped BTC, Access Control, Upgradeable Proxy, Solidity | 2 | 0 | 0 | 0 | 1 | 0 |
| 2025-09-28 | 2025-10-02 | [River Smart Vault](https://github.com/Zellic/publications/blob/master/Smart%20Vault%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/smart-vault) | River | Stablecoin, CDP, Cross-Chain, Leverage, Yield, Solidity | 2 | 0 | 0 | 1 | 4 | 3 |
| 2025-07-18 | 2025-07-29 | [SP1 Helios](https://github.com/Zellic/publications/blob/master/SP1%20Helios%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/sp1-helios) | Succinct Labs | Smart Contracts, Rollup, Light Client, L2, Cross-Chain, Solidity, Rust | 2 | 1 | 0 | 1 | 0 | 3 |
| 2025-06-23 | 2025-07-07 | [Frax / FraxNet](https://github.com/Zellic/publications/blob/master/Frax%20-%20Zellic%20Audit%20Report.pdf) | FraxNet | Stablecoin, Real-World Assets, Mint/Redeem, Upgradeable Proxy, Solidity | 2 | 0 | 0 | 1 | 5 | 2 |
| 2025-03-31 | 2025-05-02 | [Mitosis](https://github.com/Zellic/publications/blob/master/Mitosis%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/mitosis) | Mitosis | L1, Cosmos SDK, Cross-Chain, Vault, Liquidity, Go, Solidity | 2 | 1 | 2 | 1 | 1 | 6 |
| 2025-03-05 | 2025-03-12 | [Cosmos Liquid Staking Module (2025)](https://raw.githubusercontent.com/cosmos/gaia/618581e1ee1393b083a5c085cce503412f6596f6/contrib/audits/liquid-zellic-audit-25.pdf) · [web](https://github.com/cosmos/gaia/blob/618581e1ee1393b083a5c085cce503412f6596f6/contrib/audits/liquid-zellic-audit-25.pdf) | The Hub team at Informal Systems | Liquid Staking, Staking, Slashing, Cosmos SDK, L1, Go | 2 | 0 | 0 | 2 | 1 | 0 |
| 2025-01-20 | 2025-01-23 | [Xion Passkeys](https://github.com/Zellic/publications/blob/master/Xion%20Passkeys%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/xion-passkeys) | Burnt Labs | Account Abstraction, Smart Wallet, Passkeys/WebAuthn, CosmWasm, Cryptography, Rust, Go | 2 | 0 | 0 | 0 | 2 | 0 |
| 2025-01-08 | 2025-01-16 | [Astria Shared Sequencer Oracle](https://github.com/Zellic/publications/blob/f9d9c32bd1863f17b8c47bf7fcf7c498e955e198/Astria%20Shared%20Sequencer%20Oracle%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/astria-shared-sequencer-oracle) | Astria | Oracle, Sequencer, L2, Rust | 2 | 0 | 0 | 1 | 1 | 0 |
| 2024-11-25 | 2024-12-09 | [Anzen USDz & protocol-v2](https://github.com/Zellic/publications/blob/master/Anzen%20and%20protocol-v2%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/anzen-and-protocol-v2) | Anzen Labs Inc. | Real-World Assets, Stablecoin, Governance, Vote-Escrow, Cross-Chain, Solidity | 3 | 0 | 0 | 3 | 3 | 3 |
| 2024-11-12 | 2024-11-20 | [Cosmos SDK Liquid Staking Module](https://github.com/Zellic/publications/blob/master/Cosmos%20SDK%20Liquid%20Stake%20Module%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/cosmos-sdk-liquid-stake-module) | The Hub team at Informal Systems | Liquid Staking, Staking, Slashing, Cosmos SDK, L1, Go | 2 | 0 | 1 | 0 | 1 | 0 |
| 2024-10-31 | 2024-11-08 | [Plaza Programmable Derivatives](https://github.com/Zellic/publications/blob/master/Plaza%20Core%20Protocol%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/programmable-derivatives) | Plaza Finance | Derivatives, Leverage, Liquid Staking, Oracle, Auction, Base, Solidity | 2 | 2 | 8 | 5 | 3 | 2 |
| 2024-10-14 | 2024-10-18 | [Paxos Stablecoin](https://raw.githubusercontent.com/paxosglobal/paxos-token-contracts/master/audits/Paxos%20Stablecoin%20-%20Zellic%20Audit%20Report.pdf) · [web](https://github.com/paxosglobal/paxos-token-contracts/tree/master/audits) | Paxos | Stablecoin, TradFi, Compliance, Supply Control, EIP-712, Cross-Chain, Solidity | 2 | 1 | 0 | 0 | 0 | 2 |
| 2024-09-03 | 2024-09-09 | [MetaLeX MetaVesT](https://github.com/Zellic/publications/blob/master/Metavest%20-%20Zellic%20Audit%20Report.pdf)§ | MetaLeX Labs, Inc | Token Vesting, Governance, Token Options, DAO, Solidity | 4 | 0 | 4 | 8 | 4 | 1 |
| 2024-07-15 | 2024-07-31 | [Astria Bridge](https://github.com/Zellic/publications/blob/master/Astria%20Bridge%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/astria-bridge) | Astria | Cross-Chain, Bridge, IBC, Rollup, L2, Rust, Solidity | 3 | 0 | 1 | 3 | 1 | 0 |
| 2024-07-11 | 2024-07-12 | [StakeKit FeeWrapper](https://github.com/Zellic/publications/blob/master/StakeKit%20FeeWrapper%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/stakekit-feewrapper) | StakeKit | Vault, Yield, ERC4626, Staking, Solidity | 2 | 0 | 0 | 3 | 0 | 0 |
| 2024-06-10 | 2024-06-12 | [warpdotgreen-cli](https://github.com/Zellic/publications/blob/master/warpdotgreen-cli%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/warpdotgreen-cli) | warp.green | Cross-Chain, Bridge, Validator Set, Wrapped Assets, Chia, Solidity | 2 | 0 | 0 | 0 | 0 | 0 |
| 2024-06-03 | 2024-06-03 | [Yei Finance Oracle](https://github.com/Zellic/publications/blob/master/Yei%20Finance%20Oracle%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/oracle) | Yei Finance | Oracle, Lending, Price Feeds, Sei, Solidity | 2 | 0 | 0 | 1 | 2 | 0 |
| 2024-05-13 | 2024-05-17 | [Alkimiya](https://github.com/Zellic/publications/blob/master/Alkimiya%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/alkimiya) | Alkimiya | Derivatives, Synthetic Assets, Oracle, Settlement, Solidity | 2 | 3 | 1 | 2 | 1 | 2 |
| 2024-04-29 | 2024-05-03 | [Adrastia PID Controller](https://github.com/Zellic/publications/blob/master/Adrastia%20PID%20Controller%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/adrastia-pid-controller) | Adrastia | Oracle, Automation, Lending, Rate Control, Solidity | 2 | 0 | 0 | 0 | 2 | 0 |
| 2024-04-25 | 2024-04-25 | [Trillion Stablecoin](https://github.com/Zellic/publications/blob/master/Trillion%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/trillion) | Trillion Network | Stablecoin, TradFi, Tokenization, Upgradeable Proxy, Solidity | 2 | 0 | 0 | 0 | 0 | 1 |
| 2024-04-15 | 2024-04-25 | [Infrared](https://drive.usercontent.google.com/download?id=1hRm7ZGTj6MRBKR0murPT4o5eYnjrkhfD&export=download&confirm=t) · [web](https://infrared.finance/docs/audits) | Infrared Finance | Liquid Staking, Vault, Yield, Staking Rewards, Solidity | 2 | 0 | 0 | 0 | 1 | 0 |
| 2024-04-11 | 2024-04-11 | [Hydrogen Labs Rover](https://github.com/Zellic/publications/blob/master/Hydrogen%20Labs%20Rover%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/rover) | Hydrogen Labs | Liquid Staking, Wrapped BTC, Vault, Access Control, Botanix, Solidity | 2 | 0 | 0 | 1 | 0 | 1 |
| 2024-04-10 | 2024-04-10 | [Omron (Inference Labs)](https://github.com/Zellic/publications/blob/master/Omron%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/omron) | Inference Labs | Vault, Restaking, Deposit, Points, Solidity | solo | 0 | 0 | 2 | 0 | 0 |
| 2024-03-28 | 2024-03-29 | [Definitive Smart Vaults](https://github.com/Zellic/publications/blob/master/Definitive%202024%20-%20Zellic%20Audit%20Report.pdf) | Definitive Finance, Inc | Vault, Yield, TradFi, Leverage, DEX Integration, Solidity | 2 | 0 | 0 | 0 | 1 | 0 |
| 2024-03-05 | 2024-03-13 | [Cozy Safety Module](https://github.com/Zellic/publications/blob/master/Safety%20Module%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/safety-module) | Cozy Finance Inc. | Insurance, Vault, Rewards, Receipt Tokens, Solidity | 2 | 0 | 2 | 4 | 2 | 0 |
| 2024-02-27 | 2024-03-06 | [Pocket Web Wallet (Avara)](https://aave.com/files/aave-account-audit-report-2024-03.pdf) · [web](https://aave.com/security) | Avara Labs Ltd. | Off-Chain, Web2Sec, Pentest, Smart Wallet, Passkeys/WebAuthn, XSS, SSRF, TypeScript | 4 | 1 | 0 | 2 | 3 | 0 |
| 2024-02-29 | 2024-03-01 | [Molend Protocol](https://github.com/Zellic/publications/blob/master/Molend%20Protocol%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/molend-protocol) | Molend Labs | Lending, Aave, Oracle, Chainlink, Interest Accrual, Solidity | 3 | 0 | 0 | 2 | 1 | 1 |
| 2024-02-27 | 2024-02-28 | [Blackwing (Ferum Labs)](https://github.com/Zellic/publications/blob/master/Blackwing%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/blackwing) | Ferum Labs | Vault, Yield, Aave, Deposit, Margin, Solidity | 2 | 0 | 0 | 1 | 1 | 1 |
| | **Total** | | | _(37 reports)_ | | 12 | 22 | 51 | 62 | 65 |

### Legend

| Symbol | Impact level |
| ------ | ------------ |
| C | Critical |
| H | High |
| M | Medium |
| L | Low |
| I | Informational |

Counts follow each report's **Breakdown of Finding Impacts** table (Zellic rates findings by impact, derived from severity × likelihood).

`Team` is the number of auditors on the engagement (`solo` = sole auditor). A `†` marks counts taken from the report's Severity axis, used for engagements that never reached the Impact-rating stage. A `§` marks a count set with a source or version caveat. A `‡` marks an engagement where my contribution is evidenced by authorship of the report repository rather than by the published consultant roster.

## Specializations

### Stablecoins & CDP — 7 reports

| Date | Report | Focus | C | H | M | L | I |
| ---- | ------ | ----- | --- | --- | --- | --- | --- |
| 2026-10-19 | [frxUSD Ecosystem](https://raw.githubusercontent.com/FraxFinance/frax-solidity/2702e7e147212b85a28e198a7eba1c3bab9119db/src/audits/frxUSD%20Ecosystem%20-%20Zellic%20Audit%20Report.pdf) · [web](https://github.com/FraxFinance/frax-solidity/blob/2702e7e147212b85a28e198a7eba1c3bab9119db/src/audits/frxUSD%20Ecosystem%20-%20Zellic%20Audit%20Report.pdf) | Stablecoin, Vault, Yield, ERC4626 | 0 | 0 | 0 | 7 | 13 |
| 2025-10-22 | [AgoraDollar (AUSD)](https://docs.agora.finance/_fern-files/agora.docs.buildwithfern.com/dec842e5c3006596d1c02bfa549af5cb141d31b06e330d70789a512ca1f0ba74/docs/assets/Agora%20Dollar%20EVM%20Oct%202025%20-%20Zellic.pdf) · [web](https://docs.agora.finance/security/smart-contract-audit-reports/agora-dollar) | Stablecoin, Tokenization, Upgradeable Proxy, Access Control | 0 | 0 | 0 | 3 | 0 |
| 2025-10-22 | [Agora EVM Contracts](https://docs.agora.finance/_fern-files/agora.docs.buildwithfern.com/52ca6d21b4d0794dacb5e95bfafd8f0c5e5468f2209fbfc4b3462974dd03f93c/docs/assets/Agora%20EVM%20Contracts%20Oct%202025%20-%20Zellic.pdf) · [web](https://docs.agora.finance/security/smart-contract-audit-reports/periphery-contracts) | Stablecoin, Access Control, Upgradeable Proxy, Solidity | 0 | 0 | 0 | 3 | 0 |
| 2025-10-02 | [River Smart Vault](https://github.com/Zellic/publications/blob/master/Smart%20Vault%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/smart-vault) | Stablecoin, CDP, Cross-Chain, Leverage | 0 | 0 | 1 | 4 | 3 |
| 2025-07-07 | [Frax / FraxNet](https://github.com/Zellic/publications/blob/master/Frax%20-%20Zellic%20Audit%20Report.pdf) | Stablecoin, Real-World Assets, Mint/Redeem, Upgradeable Proxy | 0 | 0 | 1 | 5 | 2 |
| 2024-10-18 | [Paxos Stablecoin](https://raw.githubusercontent.com/paxosglobal/paxos-token-contracts/master/audits/Paxos%20Stablecoin%20-%20Zellic%20Audit%20Report.pdf) · [web](https://github.com/paxosglobal/paxos-token-contracts/tree/master/audits) | Stablecoin, TradFi, Compliance, Supply Control | 1 | 0 | 0 | 0 | 2 |
| 2024-04-25 | [Trillion Stablecoin](https://github.com/Zellic/publications/blob/master/Trillion%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/trillion) | Stablecoin, TradFi, Tokenization, Upgradeable Proxy | 0 | 0 | 0 | 0 | 1 |
| | **Subtotal** | | 1 | 0 | 2 | 22 | 21 |

### Vaults & Yield — 6 reports

| Date | Report | Focus | C | H | M | L | I |
| ---- | ------ | ----- | --- | --- | --- | --- | --- |
| 2025-11-17 | [MegaETH Predeposit](https://github.com/Zellic/publications/blob/5503c6f5d87df11b7864deef37c04bce99e367c2/MegaETH%20Predeposit%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/megaeth-predeposit) | Vault, Deposit, Signed Permits, KYC | 0 | 0 | 1 | 1 | 0 |
| 2025-10-22 | [Agora Whitelabel](https://docs.agora.finance/_fern-files/agora.docs.buildwithfern.com/010148350a61b8d2cac00c92053973114230bc2b4a849cdf81f968b3acbe7413/docs/assets/Whitelabel%20-%20Zellic%20Audit%20Report.pdf) · [web](https://docs.agora.finance/security/smart-contract-audit-reports/whitelabel-stablecoins) | Vault, Yield, ERC4626, Stablecoin | 0 | 0 | 2 | 0 | 1 |
| 2024-07-12 | [StakeKit FeeWrapper](https://github.com/Zellic/publications/blob/master/StakeKit%20FeeWrapper%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/stakekit-feewrapper) | Vault, Yield, ERC4626, Staking | 0 | 0 | 3 | 0 | 0 |
| 2024-04-10 | [Omron (Inference Labs)](https://github.com/Zellic/publications/blob/master/Omron%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/omron) | Vault, Restaking, Deposit, Points | 0 | 0 | 2 | 0 | 0 |
| 2024-03-29 | [Definitive Smart Vaults](https://github.com/Zellic/publications/blob/master/Definitive%202024%20-%20Zellic%20Audit%20Report.pdf) | Vault, Yield, TradFi, Leverage | 0 | 0 | 0 | 1 | 0 |
| 2024-02-28 | [Blackwing (Ferum Labs)](https://github.com/Zellic/publications/blob/master/Blackwing%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/blackwing) | Vault, Yield, Aave, Deposit | 0 | 0 | 1 | 1 | 1 |
| | **Subtotal** | | 0 | 0 | 9 | 3 | 2 |

### Cross-Chain & Bridges — 4 reports

| Date | Report | Focus | C | H | M | L | I |
| ---- | ------ | ----- | --- | --- | --- | --- | --- |
| 2026-06-22 | [Nori Bridge](https://github.com/Zellic/publications/blob/master/Nori%20Bridge%20-%20Zellic%20Audit%20Report.pdf) | Cross-Chain, Bridge, Light Client, Mina | 3 | 3 | 1 | 4 | 12 |
| 2025-10-22 | [Agora Cross-Chain (LayerZero)](https://docs.agora.finance/_fern-files/agora.docs.buildwithfern.com/e43bc3c9e45e3631234ebf0db36f5a9938998dd1ebd07d6f8c9cfaf02f1ad248/docs/assets/Agora%20Cross-Chain%20%28LayerZero%29%20-%20Zellic%20Audit%20Report.pdf) · [web](https://docs.agora.finance/security/smart-contract-audit-reports/ausd-bridge) | Cross-Chain, Stablecoin, LayerZero, OFT | 0 | 0 | 2 | 0 | 0 |
| 2024-07-31 | [Astria Bridge](https://github.com/Zellic/publications/blob/master/Astria%20Bridge%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/astria-bridge) | Cross-Chain, Bridge, IBC, Rollup | 0 | 1 | 3 | 1 | 0 |
| 2024-06-12 | [warpdotgreen-cli](https://github.com/Zellic/publications/blob/master/warpdotgreen-cli%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/warpdotgreen-cli) | Cross-Chain, Bridge, Validator Set, Wrapped Assets | 0 | 0 | 0 | 0 | 0 |
| | **Subtotal** | | 3 | 4 | 6 | 5 | 12 |

### Liquid Staking & Restaking — 4 reports

| Date | Report | Focus | C | H | M | L | I |
| ---- | ------ | ----- | --- | --- | --- | --- | --- |
| 2025-03-12 | [Cosmos Liquid Staking Module (2025)](https://raw.githubusercontent.com/cosmos/gaia/618581e1ee1393b083a5c085cce503412f6596f6/contrib/audits/liquid-zellic-audit-25.pdf) · [web](https://github.com/cosmos/gaia/blob/618581e1ee1393b083a5c085cce503412f6596f6/contrib/audits/liquid-zellic-audit-25.pdf) | Liquid Staking, Staking, Slashing, Cosmos SDK | 0 | 0 | 2 | 1 | 0 |
| 2024-11-20 | [Cosmos SDK Liquid Staking Module](https://github.com/Zellic/publications/blob/master/Cosmos%20SDK%20Liquid%20Stake%20Module%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/cosmos-sdk-liquid-stake-module) | Liquid Staking, Staking, Slashing, Cosmos SDK | 0 | 1 | 0 | 1 | 0 |
| 2024-04-25 | [Infrared](https://drive.usercontent.google.com/download?id=1hRm7ZGTj6MRBKR0murPT4o5eYnjrkhfD&export=download&confirm=t) · [web](https://infrared.finance/docs/audits) | Liquid Staking, Vault, Yield, Staking Rewards | 0 | 0 | 0 | 1 | 0 |
| 2024-04-11 | [Hydrogen Labs Rover](https://github.com/Zellic/publications/blob/master/Hydrogen%20Labs%20Rover%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/rover) | Liquid Staking, Wrapped BTC, Vault, Access Control | 0 | 0 | 1 | 0 | 1 |
| | **Subtotal** | | 0 | 1 | 3 | 3 | 1 |

### Derivatives & Structured Products — 3 reports

| Date | Report | Focus | C | H | M | L | I |
| ---- | ------ | ----- | --- | --- | --- | --- | --- |
| 2024-11-08 | [Plaza Programmable Derivatives](https://github.com/Zellic/publications/blob/master/Plaza%20Core%20Protocol%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/programmable-derivatives) | Derivatives, Leverage, Liquid Staking, Oracle | 2 | 8 | 5 | 3 | 2 |
| 2024-05-17 | [Alkimiya](https://github.com/Zellic/publications/blob/master/Alkimiya%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/alkimiya) | Derivatives, Synthetic Assets, Oracle, Settlement | 3 | 1 | 2 | 1 | 2 |
| 2024-03-13 | [Cozy Safety Module](https://github.com/Zellic/publications/blob/master/Safety%20Module%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/safety-module) | Insurance, Vault, Rewards, Receipt Tokens | 0 | 2 | 4 | 2 | 0 |
| | **Subtotal** | | 5 | 11 | 11 | 6 | 4 |

### L1 / L2 Infrastructure — 3 reports

| Date | Report | Focus | C | H | M | L | I |
| ---- | ------ | ----- | --- | --- | --- | --- | --- |
| 2026-02-05 | [Cosmos Group Module](https://raw.githubusercontent.com/cosmos/cosmos-sdk/e25c86fdb32927f0e6cebcc613c862d062050b27/docs/audits/group_module_audit.pdf) · [web](https://github.com/cosmos/cosmos-sdk/blob/e25c86fdb32927f0e6cebcc613c862d062050b27/docs/audits/group_module_audit.pdf) | L1, Cosmos SDK, Governance, DAO | 0 | 0 | 1 | 1 | 6 |
| 2025-07-29 | [SP1 Helios](https://github.com/Zellic/publications/blob/master/SP1%20Helios%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/sp1-helios) | Smart Contracts, Rollup, Light Client, L2 | 1 | 0 | 1 | 0 | 3 |
| 2025-05-02 | [Mitosis](https://github.com/Zellic/publications/blob/master/Mitosis%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/mitosis) | L1, Cosmos SDK, Cross-Chain, Vault | 1 | 2 | 1 | 1 | 6 |
| | **Subtotal** | | 2 | 2 | 3 | 2 | 15 |

### Oracles & Automation — 3 reports

| Date | Report | Focus | C | H | M | L | I |
| ---- | ------ | ----- | --- | --- | --- | --- | --- |
| 2025-01-16 | [Astria Shared Sequencer Oracle](https://github.com/Zellic/publications/blob/f9d9c32bd1863f17b8c47bf7fcf7c498e955e198/Astria%20Shared%20Sequencer%20Oracle%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/astria-shared-sequencer-oracle) | Oracle, Sequencer, L2, Rust | 0 | 0 | 1 | 1 | 0 |
| 2024-06-03 | [Yei Finance Oracle](https://github.com/Zellic/publications/blob/master/Yei%20Finance%20Oracle%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/oracle) | Oracle, Lending, Price Feeds, Sei | 0 | 0 | 1 | 2 | 0 |
| 2024-05-03 | [Adrastia PID Controller](https://github.com/Zellic/publications/blob/master/Adrastia%20PID%20Controller%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/adrastia-pid-controller) | Oracle, Automation, Lending, Rate Control | 0 | 0 | 0 | 2 | 0 |
| | **Subtotal** | | 0 | 0 | 2 | 5 | 0 |

### RWA & Tokenization — 3 reports

| Date | Report | Focus | C | H | M | L | I |
| ---- | ------ | ----- | --- | --- | --- | --- | --- |
| 2026-07-20 | [Multiliquid EVM](https://github.com/Zellic/publications/blob/master/Multiliquid%20EVM%20-%20Zellic%20Audit%20Report.pdf) | Real-World Assets, Tokenization, Stablecoin, DEX | 0 | 0 | 0 | 2 | 5 |
| 2025-10-10 | [OKX xBTC (EVM)](https://web3.okx.com/cdn/web3/security/audit/report/4081abb4c7c84fc39df7048801a21d80.pdf) · [web](https://web3.okx.com/security) | Tokenization, Wrapped BTC, Access Control, Upgradeable Proxy | 0 | 0 | 0 | 1 | 0 |
| 2024-12-09 | [Anzen USDz & protocol-v2](https://github.com/Zellic/publications/blob/master/Anzen%20and%20protocol-v2%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/anzen-and-protocol-v2) | Real-World Assets, Stablecoin, Governance, Vote-Escrow | 0 | 0 | 3 | 3 | 3 |
| | **Subtotal** | | 0 | 0 | 3 | 6 | 8 |

### Account Abstraction & Wallets — 2 reports

| Date | Report | Focus | C | H | M | L | I |
| ---- | ------ | ----- | --- | --- | --- | --- | --- |
| 2025-01-23 | [Xion Passkeys](https://github.com/Zellic/publications/blob/master/Xion%20Passkeys%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/xion-passkeys) | Account Abstraction, Smart Wallet, Passkeys/WebAuthn, CosmWasm | 0 | 0 | 0 | 2 | 0 |
| 2024-03-06 | [Pocket Web Wallet (Avara)](https://aave.com/files/aave-account-audit-report-2024-03.pdf) · [web](https://aave.com/security) | Off-Chain, Web2Sec, Pentest, Smart Wallet | 1 | 0 | 2 | 3 | 0 |
| | **Subtotal** | | 1 | 0 | 2 | 5 | 0 |

### Lending & Money Markets — 1 reports

| Date | Report | Focus | C | H | M | L | I |
| ---- | ------ | ----- | --- | --- | --- | --- | --- |
| 2024-03-01 | [Molend Protocol](https://github.com/Zellic/publications/blob/master/Molend%20Protocol%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/molend-protocol) | Lending, Aave, Oracle, Chainlink | 0 | 0 | 2 | 1 | 1 |
| | **Subtotal** | | 0 | 0 | 2 | 1 | 1 |

### Token Vesting & Governance — 1 reports

| Date | Report | Focus | C | H | M | L | I |
| ---- | ------ | ----- | --- | --- | --- | --- | --- |
| 2024-09-09 | [MetaLeX MetaVesT](https://github.com/Zellic/publications/blob/master/Metavest%20-%20Zellic%20Audit%20Report.pdf)§ | Token Vesting, Governance, Token Options, DAO | 0 | 4 | 8 | 4 | 1 |
| | **Subtotal** | | 0 | 4 | 8 | 4 | 1 |

### Languages reviewed

| Language | Reports |
| --- | --- |
| Solidity | 30 |
| Rust | 5 |
| TypeScript | 2 |
| Go | 2 |
| Go (Cosmos SDK) | 2 |
| JavaScript | 1 |

### Platforms / runtimes

| Platform | Reports |
| --- | --- |
| EVM | 30 |
| Cosmos | 4 |
| Mina | 1 |
| CosmWasm | 1 |
| Rust runtime | 1 |
| Web | 1 |

## Critical & High-Impact Findings

| Report | Impact | Finding |
| ------ | ------ | ------- |
| [Nori Bridge](https://github.com/Zellic/publications/blob/master/Nori%20Bridge%20-%20Zellic%20Audit%20Report.pdf) | High | [d3034] Compromised admin is not prevented from minting or unlocking illegitimately |
| [Nori Bridge](https://github.com/Zellic/publications/blob/master/Nori%20Bridge%20-%20Zellic%20Audit%20Report.pdf) | High | [4279a] Unvalidated oldestAction in dispatchAndEvict can permanently brick ETH to Mina minting |
| [Nori Bridge](https://github.com/Zellic/publications/blob/master/Nori%20Bridge%20-%20Zellic%20Audit%20Report.pdf) | High | [a3850] The committed deposit root is not constrained to be complete |
| [SP1 Helios](https://github.com/Zellic/publications/blob/master/SP1%20Helios%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/sp1-helios) | Critical | No test suite is in place |
| [Mitosis](https://github.com/Zellic/publications/blob/master/Mitosis%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/mitosis) | Critical | Missing unstake-amount validation |
| [Mitosis](https://github.com/Zellic/publications/blob/master/Mitosis%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/mitosis) | High | Slashing bypass through unbonding mechanism |
| [Mitosis](https://github.com/Zellic/publications/blob/master/Mitosis%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/mitosis) | High | First depositor inflation attack via missing _decimalsOffset() override in ERC-4626 vault |
| [Cosmos SDK Liquid Staking Module](https://github.com/Zellic/publications/blob/master/Cosmos%20SDK%20Liquid%20Stake%20Module%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/cosmos-sdk-liquid-stake-module) | High | Accounting validator bonds share could be broken |
| [Plaza Programmable Derivatives](https://github.com/Zellic/publications/blob/master/Plaza%20Core%20Protocol%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/programmable-derivatives) | Critical | Distributor could be drained by fake pool |
| [Plaza Programmable Derivatives](https://github.com/Zellic/publications/blob/master/Plaza%20Core%20Protocol%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/programmable-derivatives) | Critical | A malicious bidder could drain the Auction contract |
| [Plaza Programmable Derivatives](https://github.com/Zellic/publications/blob/master/Plaza%20Core%20Protocol%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/programmable-derivatives) | High | Incorrect PreDeposit reward |
| [Plaza Programmable Derivatives](https://github.com/Zellic/publications/blob/master/Plaza%20Core%20Protocol%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/programmable-derivatives) | High | Claim function could be broken by timing attack |
| [Plaza Programmable Derivatives](https://github.com/Zellic/publications/blob/master/Plaza%20Core%20Protocol%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/programmable-derivatives) | High | Lack of handling of auction failures |
| [Plaza Programmable Derivatives](https://github.com/Zellic/publications/blob/master/Plaza%20Core%20Protocol%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/programmable-derivatives) | High | Bidders are unable to claim the expected amount of reserve tokens |
| [Plaza Programmable Derivatives](https://github.com/Zellic/publications/blob/master/Plaza%20Core%20Protocol%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/programmable-derivatives) | High | Distribution's claim function does not update storage variables |
| [Plaza Programmable Derivatives](https://github.com/Zellic/publications/blob/master/Plaza%20Core%20Protocol%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/programmable-derivatives) | High | Huge bid could cause overflow in subsequent bids |
| [Plaza Programmable Derivatives](https://github.com/Zellic/publications/blob/master/Plaza%20Core%20Protocol%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/programmable-derivatives) | High | Number of coupon tokens obtained from the auction may differ from number of coupon tokens to be distributed |
| [Plaza Programmable Derivatives](https://github.com/Zellic/publications/blob/master/Plaza%20Core%20Protocol%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/programmable-derivatives) | High | Decimals of the data in the function latestRoundData |
| [Paxos Stablecoin](https://raw.githubusercontent.com/paxosglobal/paxos-token-contracts/master/audits/Paxos%20Stablecoin%20-%20Zellic%20Audit%20Report.pdf) · [web](https://github.com/paxosglobal/paxos-token-contracts/tree/master/audits) | Critical | Frozen tokens available for cross-chain transfer |
| [MetaLeX MetaVesT](https://github.com/Zellic/publications/blob/master/Metavest%20-%20Zellic%20Audit%20Report.pdf)§ | High | Anyone can vote on any majority amendment proposal with arbitrary voting power |
| [MetaLeX MetaVesT](https://github.com/Zellic/publications/blob/master/Metavest%20-%20Zellic%20Audit%20Report.pdf)§ | High | Possibility for users to buy tokens from MetaVesT for free |
| [MetaLeX MetaVesT](https://github.com/Zellic/publications/blob/master/Metavest%20-%20Zellic%20Audit%20Report.pdf)§ | High | Incorrect calculation in terminate function |
| [MetaLeX MetaVesT](https://github.com/Zellic/publications/blob/master/Metavest%20-%20Zellic%20Audit%20Report.pdf)§ | High | Reward tokens corresponding to removed milestones are locked |
| [Astria Bridge](https://github.com/Zellic/publications/blob/master/Astria%20Bridge%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/astria-bridge) | High | Invalid address could break down the bridge withdrawer |
| [Alkimiya](https://github.com/Zellic/publications/blob/master/Alkimiya%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/alkimiya) | Critical | Fake pool could drain all the pool's tokens |
| [Alkimiya](https://github.com/Zellic/publications/blob/master/Alkimiya%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/alkimiya) | Critical | The redeemShort function is available before the pool is closed |
| [Alkimiya](https://github.com/Zellic/publications/blob/master/Alkimiya%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/alkimiya) | High | Simultaneous pool starting and closing is possible |
| [Alkimiya](https://github.com/Zellic/publications/blob/master/Alkimiya%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/alkimiya) | Critical | Redeem functions do not work correctly |
| [Cozy Safety Module](https://github.com/Zellic/publications/blob/master/Safety%20Module%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/safety-module) | High | Deposit/stake functions are front-runnable |
| [Cozy Safety Module](https://github.com/Zellic/publications/blob/master/Safety%20Module%20-%20Zellic%20Audit%20Report.pdf) · [web](https://reports.zellic.io/publications/safety-module) | High | Queued SafetyModule configuration updates may be applied when the SafetyModule is TRIGGERED by pausing |
| [Pocket Web Wallet (Avara)](https://aave.com/files/aave-account-audit-report-2024-03.pdf) · [web](https://aave.com/security) | Critical | Cross-site scripting via image proxy |

## Sources

- Published PDFs: <https://github.com/Zellic/publications>
- Report site: <https://reports.zellic.io>
- Reports hosted by clients are linked directly in the table above.
