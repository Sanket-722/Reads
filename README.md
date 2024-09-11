<img src="https://github.com/user-attachments/assets/6a74f7f6-394c-4986-9135-e43861e2b925" alt="Reading_Boy" width="1000" height="400"/>

# Reports
Simply want to collect reports which i read day in and out.

# Solidity Reads 

### Rug Pull :
1. [[M] Schain owners can rug pull users' funds](https://solodit.xyz/issues/m-05-schain-owners-can-rug-pull-users-funds-code4rena-skale-skale-contest-git)
2. [[M] Centralisation risk: admin role of `TokenManagerEth` can rug pull all Eth from the bridge](https://solodit.xyz/issues/m-06-centralisation-risk-admin-role-of-tokenmanagereth-can-rug-pull-all-eth-from-the-bridge-code4rena-skale-skale-contest-git)
3. [[M] compromised `owner` can drain funds from`VeTokenMinter.sol`](https://solodit.xyz/issues/m-01-compromised-owner-can-drain-funds-fromvetokenmintersol-code4rena-vetoken-finance-vetoken-finance-contest-git)
4. [[M] `VoterProxy` incorrectly assumes a 1-1 mapping between the gauge and the LP tokens.](https://solodit.xyz/issues/m-21-voterproxy-incorrectly-assumes-a-1-1-mapping-between-the-gauge-and-the-lp-tokens-code4rena-vetoken-finance-vetoken-finance-contest-git)

### Constructor 
1. [[M] NPM Dependency confusion. Unclaimed NPM Package and Scope/Org](https://github.com/code-423n4/2022-03-timeswap-findings/issues/9)
2. [[M] No use of upgradeable SafeERC20 contract in Controller.sol](https://github.com/code-423n4/2022-03-rolla-findings/issues/5)
3. [[M] Inconsistency between constructor and setting method for slippageTolerance](https://github.com/code-423n4/2022-04-backd-findings/issues/97)
4. [[M] ERC721SeaDrop owner can choose an address they control as the admin when the constructor is](https://solodit.xyz/issues/erc721seadrop-owner-can-choose-an-address-they-control-as-the-admin-when-the-constructor-is-spearbit-seadrop-pdf)

### NFT 
1. [[M] Use safeTransferFrom instead of transferFrom for ERC721 transfers](https://solodit.xyz/issues/m-09-use-safetransferfrom-instead-of-transferfrom-for-erc721-transfers-code4rena-cally-cally-contest-git)
2. [QSP-1 Max supply of 500 is not enforced at the token level](https://certificate.quantstamp.com/full/sele-ct-x-storm-x-nft.pdf)
3. [QSP-2 Minter can burn token on any address](https://certificate.quantstamp.com/full/sele-ct-x-storm-x-nft.pdf)
4. [[M]Possibility of DOS due to overﬂow](https://github.com/Quillhash/QuillAudit_Reports/blob/master/AntiGravity%20Smart%20Contract%20Audit%20Report%20-%20QuillAudits.pdf)

### DOS
1. [[M] Possible DOS in 'allVestingRecipients()' function because of unbounded gas consumption.](https://github.com/code-423n4/2022-09-vtvl-findings/issues/372)
2. [[M] [Denial-of-Service] Contract Owner Could Block Users From Withdrawing Their Strike](https://solodit.xyz/issues/m-06-denial-of-service-contract-owner-could-block-users-from-withdrawing-their-strike-code4rena-putty-putty-contest-git)
3. [[H] Denial of Service](https://solodit.xyz/issues/h-02-denial-of-service-code4rena-hubble-hubble-contest-git)
4. [[M] Malicious users could block liquidation or perform DOS](https://solodit.xyz/issues/m-4-malicious-users-could-block-liquidation-or-perform-dos-sherlock-notional-update-5-git)
5. [Vault can be placed back into vulnerable low supply state](https://solodit.xyz/issues/vault-can-be-placed-back-into-vulnerable-low-supply-state-openzeppelin-pods-finance-ethereum-volatility-vault-audit-2-markdown)
6. [Potential funds locked due low token decimal and long stream duration](https://solodit.xyz/issues/potential-funds-locked-due-low-token-decimal-and-long-stream-duration-spearbit-locke-pdf)
7. [[M] Unhandled chainlink revert would lock all price oracle access](https://solodit.xyz/issues/m-09-unhandled-chainlink-revert-would-lock-all-price-oracle-access-code4rena-juicebox-juicebox-v2-contest-git)
8. [[H] PEUSD.CONVERTTOPEUSD() CALL COULD CAUSE A DENIAL OF SERVICE IN THE DISTRIBUTEREWARDS FUNCTION](https://github.com/HalbornSecurity/PublicReports/blob/master/Solidity%20Smart%20Contract%20Audits/Lybra_Finance_V2_Smart_Contract_Security_Assessment_Report_Halborn_Final.pdf)

### Conditional
1. [[M] !_account.isContract() can be bypassed](https://github.com/code-423n4/2022-04-jpegd-findings/issues/128)
2. [Passing multiple ETH deposits in orders array will use the same `msg.value` many times](https://solodit.xyz/issues/m-08-passing-multiple-eth-deposits-in-orders-array-will-use-the-same-msgvalue-many-times-code4rena-nested-finance-nested-finance-contest-git)
3. [Incorrect Revert Condition in submitBatch()](https://certificate.quantstamp.com/full/tensorplex-labs/fac85f03-dfa2-4f47-88d6-732ed5ea9360/index.html#findings-qs4)

### Functional 
1. [[M] Unsafe call to `ERC20::transfer` can result in stuck funds.](https://solodit.xyz/issues/m-01-unsafe-call-to-erc20transfer-can-result-in-stuck-funds-pashov-none-zerem-markdown) 
2. [[H] First vault depositor can steal subsequent depositors’ tokens.](https://solodit.xyz/issues/h-02-first-vault-depositor-can-steal-subsequent-depositors-tokens-pashov-none-yield-ninja-markdown_)
3. [[M] UniswapV3’s path issue for swapExactOutput](https://solodit.xyz/issues/m-06-uniswapv3s-path-issue-for-swapexactoutput-code4rena-mellow-protocol-mellow-protocol-contest-git)
4. [[M] https://solodit.xyz/auth?next=/issues/m-01-code4rena-blockswap-blockswap-formal-verification-contest-with-certora-git ](https://solodit.xyz/auth?next=/issues/m-01-code4rena-blockswap-blockswap-formal-verification-contest-with-certora-git)
5. [[M] Cancellation refunds should return tokens to order creator, not recipient](https://solodit.xyz/issues/m-3-cancellation-refunds-should-return-tokens-to-order-creator-not-recipient-sherlock-none-dinari-git)
6. [[M] M-2: Because of rounding issues, users may not be able to withdraw airdrop tokens if their claim has been adjust()'ed upwards](https://solodit.xyz/issues/m-2-because-of-rounding-issues-users-may-not-be-able-to-withdraw-airdrop-tokens-if-their-claim-has-been-adjusted-upwards-sherlock-none-tokensoft-git)
7. [[M] Gas stipend for external call might be insufficient and lead to stuck ETH](https://solodit.xyz/issues/m-02-gas-stipend-for-external-call-might-be-insufficient-and-lead-to-stuck-eth-pashov-none-zerem-markdown)
8. [[WP-H3] L1Migrator.sol#migrateETH() Improper implementation of L1Migrator causing migrateETH() always reverts, can lead to ETH in BridgeMinter getting stuck in the contract](https://github.com/code-423n4/2022-01-livepeer-findings/issues/198)
9. [[M] Gas stipend for external call might be insufficient and lead to stuck ETH](https://solodit.xyz/issues/m-02-gas-stipend-for-external-call-might-be-insufficient-and-lead-to-stuck-eth-pashov-none-zerem-markdown)
10. [[M] Any native assets in the LiFiDiamond can be took by anyone](https://github.com/code-423n4/2022-03-lifinance-findings/issues/16)
11. [[M] Ether can be locked in the `PoolFactory` contract without a way to retrieve it](https://solodit.xyz/issues/m-01-ether-can-be-locked-in-the-poolfactory-contract-without-a-way-to-retrieve-it-code4rena-sublime-sublime-contest-git)
12. [Stop Using Solidity's transfer() Now](https://consensys.io/diligence/blog/2019/09/stop-using-soliditys-transfer-now/)
13. [[M] BLOCK_PERIOD is incorrect](https://github.com/code-423n4/2022-10-zksync-findings/issues/259)
14. [keccak123 - abi.encodePacked Allows Hash Collision](https://github.com/sherlock-audit/2022-10-nftport-judging/issues/118)
15. [XSS via SVG Construction contract](https://github.com/code-423n4/2022-01-timeswap-findings/issues/131)
16. ['onlyEOAEx' modifier that ensures call is from EOA might not hold true in the future](https://github.com/sherlock-audit/2023-02-blueberry-judging/issues/21)
17. [THORChain_Router’s‌‌transferOut‌‌ does‌‌ not‌‌ check‌‌ transfer‌‌ return‌‌ values No 8](https://github.com/thorchain/Resources/blob/master/Audits/THORChain-TrailOfBits-FullAudit-Aug2021.pdf)
18. [AccountManage Can Be Initialized With No Required Signers](https://certificate.quantstamp.com/full/net-mind/e7dfdc3c-7589-4fc8-b3d8-4872c783a735/index.html#findings-qs4)
19. [Staking] [[H] Loss of Pending Reward when Unstaking](https://certificate.quantstamp.com/full/zero-staking/40ffa176-7b8d-43ec-a7e2-29732c12f21e/index.html#findings-qs2)
20. [ERC-20 Staking and Governance] [[M] Users Can Move Votes with delegateBySig()](https://certificate.quantstamp.com/full/music-protocol-token-staking-and-dao/3cb260d9-3d7c-47a8-b247-6ca4ce733ab6/index.html#findings-qs3)
21. [ERC-20 Staking and Governance] [[M] Potentially Inaccurate Quorum Calculations](https://certificate.quantstamp.com/full/music-protocol-token-staking-and-dao/3cb260d9-3d7c-47a8-b247-6ca4ce733ab6/index.html#findings-qs4)

### Logical
1. [getUserInfo() returns incorrect values for locked and stakedAmount ](https://github.com/sherlock-audit/2022-10-union-finance-judging/issues/80)
2. [Maximal approvals remain for the AssetManager's adapters and tokens after removal](https://github.com/sherlock-audit/2022-10-union-finance-judging/issues/36)
3. [CURVEPOOL.EXCHANGEUNDERLYING() CALL COULD CONSTANTLY REVERT IN THE DISTRIBUTEREWARDS FUNCTION](https://github.com/HalbornSecurity/PublicReports/blob/master/Solidity%20Smart%20Contract%20Audits/Lybra_Finance_V2_Smart_Contract_Security_Assessment_Report_Halborn_Final.pdf)
4. [Staking] [[H] Malicious User Can Drain Rewards Through Reentrancy in Staking](https://certificate.quantstamp.com/full/zero-staking/40ffa176-7b8d-43ec-a7e2-29732c12f21e/index.html#findings-qs1)
5. [Staking] [[H] A malicious user can reduce other users' rewards due to incorrect accounting of stake balances](https://certificate.quantstamp.com/full/nayms-2024-retainer/04e1c37c-19e8-4c7d-b743-268e4a6466c9/index.html#findings-qs2)
6. [Staking] [[H] Incorrect accounting when users of a staking entity stake into that entity](https://certificate.quantstamp.com/full/nayms-2024-retainer/04e1c37c-19e8-4c7d-b743-268e4a6466c9/index.html#findings-qs3)

### Swap 
1. [[M] `UNISWAP_FEE` is hardcoded which will lead to significant losses compared to optimal routing](https://solodit.xyz/issues/m-02-uniswap_fee-is-hardcoded-which-will-lead-to-significant-losses-compared-to-optimal-routing-code4rena-sturdy-sturdy-contest-git_)
2. [[M] `SWAP_ROUTER` in `AutoPxGmx.sol` is hardcoded and not compatible on Avalanche](https://solodit.xyz/issues/m-02-uniswap_fee-is-hardcoded-which-will-lead-to-significant-losses-compared-to-optimal-routing-code4rena-sturdy-sturdy-contest-git_)
3. [[M] AddLiquidity and decreaseLiquidity missing slippage protection](https://solodit.xyz/issues/m-15-addliquidity-and-decreaseliquidity-missing-slippage-protection-code4rena-particle-protocol-particle-protocol-git)
4. [[M] Duplicate LP token could lead to incorrect reward distribution](https://github.com/code-423n4/2022-05-aura-findings/issues/124)
5. [Missing ```fromToken != toToken``` check in ```MarginRouter.crossSwapExactTokensForTokens/MarginRouter.crossSwapTokensForExactTokens```](https://github.com/code-423n4/2021-04-marginswap-findings/issues/20)
6. [[H] swapTokens Function Is Unusable](https://solodit.xyz/issues/swaptokens-function-is-unusable-openzeppelin-none-radiant-riz-audit-markdown)
7. [LP tokens can be transferred to empty address](https://github.com/Quillhash/QuillAudit_Reports/blob/master/Eddy%20Finance%20Smart%20Contract%20Audit%20Report%20-%20QuillAudits.pdf)
8. [Rebate Estimator Address Desync](https://certificate.quantstamp.com/full/oasis-swap/878751e5-152a-4dae-9353-c9cd2acaedcf/index.html#findings-qs1)
   
### Oracle
1. [_updateTwav() and _getTwav() will revert when cumulativePrice overflows](https://github.com/code-423n4/2022-06-nibbl-findings/issues/246)
2. [[M] Chainlink’s latestRoundData might return stale or incorrect results](https://solodit.xyz/issues/m-05-chainlinks-latestrounddata-might-return-stale-or-incorrect-results-code4rena-mochi-mochi-contest-git)
3. [Should check return data from Chainlink aggregators](https://github.com/code-423n4/2021-05-fairside-findings/issues/70)
4. [ChainlinkAdapterOracle use BTC/USD chainlink oracle to price WBTC which is problematic if WBTC depegs](https://github.com/sherlock-audit/2023-02-blueberry-judging/issues/9)
5. [```.latestRoundData()``` does not update the oracle - ```ExchangeRate.sol```](https://github.com/code-423n4/2021-08-notional-findings/issues/18)
6. [MISUSE OF AN ORACLE](https://solodit.xyz/issues/misuse-of-an-oracle-halborn-planet-finance-pdf)
7. [ChainlinkAdapterOracle will return the wrong price for asset if underlying aggregator hits minAnswer](https://github.com/sherlock-audit/2023-02-blueberry-judging/issues/18)
8. [Oracle periodSize = 0 which is as same as not using any oracle.](https://github.com/code-423n4/2022-06-canto-v2-findings/issues/8)
9. [latestRoundData() has no check for round completeness](https://solodit.xyz/issues/m-7-latestrounddata-has-no-check-for-round-completeness-sherlock-isomorph-isomorph-git)
10. [MISSING STALENESS CHECKS IN THE CHAINLINK.LATESTROUNDDATA() CALLS](https://solodit.xyz/issues/missing-staleness-checks-in-the-chainlinklatestrounddata-calls-halborn-none-lybra-finance-v2-security-assessment-pdf)
11. [Oracle May Return Outdated Nav Information](https://certificate.quantstamp.com/full/solv-protocol-solv-btc/1eca9413-0b03-4b7d-9885-e5373ee2d722/index.html#findings-qs2)
12. [[M] Attackers Can Profit by Creating Repeated Long or Short Positions Using Known Oracle Prices](https://certificate.quantstamp.com/full/storm-trade/21e4074a-b2cb-409d-b5df-48f683d0e8f3/index.html#findings-qs1) ---> Exploit Scenario

### Decimal
1. [Interest accrued could be zero for small decimal tokens](https://github.com/code-423n4/2022-03-sublime-findings/issues/10)
2. [WithdrawPeriphery uses incorrect value for MAX_BPS which will allow much higher slippage than intended](https://solodit.xyz/issues/m-4-withdrawperiphery-uses-incorrect-value-for-max_bps-which-will-allow-much-higher-slippage-than-intended-sherlock-rage-trade-rage-trade-git)
3. [Basis points constant BPS_MAX is used as minimal fee amount requirement](https://solodit.xyz/issues/m-01-basis-points-constant-bps_max-is-used-as-minimal-fee-amount-requirement-code4rena-aave-lens-aave-lens-contest-git)
4. [[M] IMPRECISE INTEREST RATE CALCULATIONS](https://github.com/arbitraryexecution/publications/blob/main/assessments/Sentiment_Protocol_20220727.pdf)

### Dynamic Thinking 
1. [[L]lastBatchNonce Does Not Have Upper Bound Sanity Check](https://certificate.quantstamp.com/full/tensorplex-labs/fac85f03-dfa2-4f47-88d6-732ed5ea9360/index.html)
2. [[L] Double Reserve in vault Can Lead to Transaction Failure](https://certificate.quantstamp.com/full/storm-trade/21e4074a-b2cb-409d-b5df-48f683d0e8f3/index.html#findings-qs7)


### Math
1. [Permanent freeze of vested tokens due to overflow in _baseVestedAmount](https://github.com/code-423n4/2022-09-vtvl-findings/issues/95)
2. [Lack of sanity check on _initialTokenSupply and _initialTokenPrice can lead to a seller losing his NFT](https://github.com/code-423n4/2022-06-nibbl-findings/issues/24)
3. [Unsafe downcasting arithmetic operation in UserManager related contract and in UToken.sol](https://github.com/sherlock-audit/2022-10-union-finance-judging/issues/96)
4. [FRAX admin can adjust fee rate to harm Napier and its users ](https://github.com/sherlock-audit/2024-01-napier-judging/issues/108)
5. [Incorrect unlockTime can DOS withdrawGovernanceAsset](https://github.com/code-423n4/2022-01-behodler-findings/issues/228)

### Tokens
1. [AutoleverageBase: Must approve 0](https://github.com/code-423n4/2022-05-alchemix-findings/issues/144)
2. [Staking][[M] Mixing of Staked Tokens and Reward Tokens](https://certificate.quantstamp.com/full/zero-staking/40ffa176-7b8d-43ec-a7e2-29732c12f21e/index.html#findings-qs4)

### Rounding Errors and Precision Loss
1. [[M] Potential Loss Due to Unrefunded Excess when Purchasing NMT](https://certificate.quantstamp.com/full/net-mind/e7dfdc3c-7589-4fc8-b3d8-4872c783a735/index.html#findings-qs9)
2. [[M] Precision Loss](https://certificate.quantstamp.com/full/net-mind/e7dfdc3c-7589-4fc8-b3d8-4872c783a735/index.html#findings-qs12)
3. [[M]Loss of Precision Due to Division Before Multiplication](https://certificate.quantstamp.com/full/oasis-swap/878751e5-152a-4dae-9353-c9cd2acaedcf/index.html#findings-qs3)
4. [Staking] [[M] Users Can Lose Out on Rewards if They Claim Too Frequently](https://certificate.quantstamp.com/full/zero-staking/40ffa176-7b8d-43ec-a7e2-29732c12f21e/index.html#findings-qs3)


### AMM
1. [block.timestamp or deadline ](https://solodit.xyz/issues/m-06-blocktimestamp-or-deadline-code4rena-amun-amun-contest-git)
2. [Existing token hooks are replaceable while adding new](https://github.com/Quillhash/QuillAudit_Reports/blob/master/Burve%20Smart%20Contracts%20Audit%20Report%20-%20QuillAudits.pdf)

### Access Control
1. [Any public vault without a delegate can be drained](https://github.com/sherlock-audit/2022-10-astaria-judging/issues/69)
2. [Malicious actors can lock all FEI and TRIBE in the GenesisGroup](https://solodit.xyz/issues/m01-malicious-actors-can-lock-all-fei-and-tribe-in-the-genesisgroup-openzeppelin-fei-protocol-audit-markdown)
3. [onlyOwner Role Can Unintentionally Influence "settleAuction()"](https://solodit.xyz/issues/m-03-onlyowner-role-can-unintentionally-influence-settleauction-code4rena-kuiper-kuiper-contest-git)
4. [[M]Hackers can deploy token with respective name as the stable one to impersonate the stable token](https://solodit.xyz/issues/m-03-hackers-can-deploy-token-with-respective-name-as-the-stable-one-to-impersonate-the-stable-token-code4rena-canto-canto-git)
5. [[C] Slot Collision](https://www.trust-security.xyz/post/learning-by-breaking-a-layerzero-case-study-part-one)
6. [Restaking] [[M] Vault Accounting Inconsistency if Harvester Calls Delegator Functions Directly](https://certificate.quantstamp.com/full/affine-labs-ultra-eth-lrt/f1c58be1-9f7a-4716-b96a-6d38816396d2/index.html#findings-qs1)
7. [Staking] [[H] User can artificially inflate stake boosts for the next interval by repeating stake and unstake actions](https://certificate.quantstamp.com/full/nayms-2024-retainer/04e1c37c-19e8-4c7d-b743-268e4a6466c9/index.html#findings-qs1)
   

### CrossChain
1. [[M] It Will Not Be Possible to Bridge DAI to Blast](https://solodit.xyz/issues/across-it-will-not-be-possible-to-bridge-dai-to-blast-openzeppelin-none-across-v3-and-oval-incremental-audit-markdown)
2. [[L] Error-Prone Initialization of Blast_Adapter.sol](https://blog.openzeppelin.com/across-v3-and-oval-incremental-audit#:~:text=%5BAcross%5D-,Error%2DProne%20Initialization%20of%20Blast_Adapter.sol,-The%20constructor%20of)
3. [[L] Permit2 Witness Is Not Fully Compliant With EIP-712](https://blog.openzeppelin.com/across-v3-and-oval-incremental-audit#:~:text=%5BAcross%5D-,Permit2%20Witness%20Is%20Not%20Fully%20Compliant%20With%20EIP%2D712,-The%20ERC7683Permit2Lib%20library)
4. [[L]  Users May Lose Assets if They Specify an Empty Address as a Call Target](https://blog.openzeppelin.com/across-v3-and-oval-incremental-audit#:~:text=%5BAcross%5D-,Users%20May%20Lose%20Assets%20if%20They%20Specify%20an%20Empty%20Address%20as%20a%20Call%20Target,-The%20attemptCalls%20function)
5. [MintCap Check Missing in Cross-Chain Transfer](https://solodit.xyz/issues/mintcap-check-missing-in-cross-chain-transfer-mixbytes-none-dforce-markdown)
6. [Loss of Funds if Unsupported Chain ID Specified](https://certificate.quantstamp.com/full/tensorplex-labs/fac85f03-dfa2-4f47-88d6-732ed5ea9360/index.html#findings-qs3)
7. [[L] Source Chain ID in a Submitted Batch Can Be Modified](https://certificate.quantstamp.com/full/tensorplex-labs/fac85f03-dfa2-4f47-88d6-732ed5ea9360/index.html#findings-qs6)

### Replay 
1. [Signature Replay](https://certificate.quantstamp.com/full/net-mind/e7dfdc3c-7589-4fc8-b3d8-4872c783a735/index.html#findings-qs1)
2. [[M] Replay Attack to Close or Open Market Unexpectedly](https://certificate.quantstamp.com/full/storm-trade/21e4074a-b2cb-409d-b5df-48f683d0e8f3/index.html#findings-qs2)
3. [Risk of Signature Replay Attack in ApprovedCallsPolicy](https://solodit.xyz/issues/risk-of-signature-replay-attack-in-approvedcallspolicy-openzeppelin-none-ironblocks-onchain-firewall-audit-markdown)

### Other 
1. [Incorrect hardcoded address](https://solodit.xyz/issues/incorrect-hardcoded-address-mixbytes-none-barter-dao-markdown)
2. [Incorrect comparison operator while checking](https://github.com/Quillhash/QuillAudit_Reports/blob/master/Burve%20Smart%20Contracts%20Audit%20Report%20-%20QuillAudits.pdf)
3. [Excessive Privileges for Wards](https://certificate.quantstamp.com/full/net-mind/e7dfdc3c-7589-4fc8-b3d8-4872c783a735/index.html#findings-qs2)
4. [Centralization Risks](https://certificate.quantstamp.com/full/net-mind/e7dfdc3c-7589-4fc8-b3d8-4872c783a735/index.html#findings-qs3)
5. [[M] Malicious Manager Can Pass Any Proposal and Drain Funds](https://certificate.quantstamp.com/full/net-mind/e7dfdc3c-7589-4fc8-b3d8-4872c783a735/index.html#findings-qs7)
6. [Executor and Referral Rewards Can Be Lost After Vault Updates Due to a Race Condition](https://certificate.quantstamp.com/full/storm-trade/21e4074a-b2cb-409d-b5df-48f683d0e8f3/index.html#findings-qs4) --- Exploit Scenario
7. [Race Condition in Bounce Messages Handling Lead to Overwritten Balances](https://certificate.quantstamp.com/full/storm-trade/21e4074a-b2cb-409d-b5df-48f683d0e8f3/index.html#findings-qs5) --- Exploit Scenario
8. [ERC-20 Staking and Governance] [[L] Checks-Effects-Interactions Pattern Violation](https://certificate.quantstamp.com/full/music-protocol-token-staking-and-dao/3cb260d9-3d7c-47a8-b247-6ca4ce733ab6/index.html#findings-qs5)
9. [Liquid Staking Token] [[M] Missing Enforcements for Voting](https://certificate.quantstamp.com/full/stake-stone/4b7cbc5e-5595-4ac4-ac36-176f43ee9adf/index.html#findings-qs1)

### ERC20
1. [Transfer token without user approval](https://github.com/Quillhash/QuillAudit_Reports/blob/master/AntiGravity%20Smart%20Contract%20Audit%20Report%20-%20QuillAudits.pdf)
2. [Potential locking of funds due to non standard ERC20 transfers](https://github.com/Quillhash/QuillAudit_Reports/blob/master/LivaatVerse%20Smart%20Contracts%20Audit%20Report%20-%20QuillAudits.pdf)
3. [[C] INCORRECT ERC-20 TOKEN VALUATION](https://github.com/arbitraryexecution/publications/blob/main/assessments/Sentiment_Protocol_20220727.pdf)
4. [[C] MAINTAINERS MAY NOT BE ABLE TO PERFORM LIQUIDATIONS](https://github.com/arbitraryexecution/publications/blob/main/assessments/Sentiment_Protocol_20220727.pdf)
5. [[C] POSSIBLE ACCOUNT TAKEOVER BY A MALICIOUS USER](https://github.com/arbitraryexecution/publications/blob/main/assessments/Sentiment_Protocol_20220727.pdf)
6. [ERC-20 Staking and Governance] [[H] Redeeming Does Not Discount Tokens of Removed Artists, Leading to Inflated Rewards](https://certificate.quantstamp.com/full/music-protocol-token-staking-and-dao/3cb260d9-3d7c-47a8-b247-6ca4ce733ab6/index.html#findings-qs1)
7. [ERC-20 Staking and Governance] [[M] Unstoppable Proposal](https://certificate.quantstamp.com/full/music-protocol-token-staking-and-dao/3cb260d9-3d7c-47a8-b247-6ca4ce733ab6/index.html#findings-qs2) ---> Exploit
8. [ERC-20 Staking and Governance] [[L] Staking Web3MusicNativeToken Deviates From the ERC-20 Standard](https://certificate.quantstamp.com/full/music-protocol-token-staking-and-dao/3cb260d9-3d7c-47a8-b247-6ca4ce733ab6/index.html#findings-qs6)
9. [Staking] [[H] User Pending Rewards Can Never Be Paid Out](https://certificate.quantstamp.com/full/intent-x/a195e62f-30b6-4219-b9e5-42af8a9e2fd5/index.html#findings-qs1)
10. [ENS] [[H] ETHRegistrarController.register is vulnerable to front running](https://consensys.io/diligence/audits/2019/03/ens-permanent-registrar/#ethregistrarcontrollerregister-is-vulnerable-to-front-running)
   
### EIP712
1. [Replay attack in case of Hard fork](https://github.com/code-423n4/2022-07-golom-findings/issues/391)
2. [If name is changed then the domain seperator would be wrong](https://github.com/code-423n4/2023-01-reserve-findings/issues/211)
3. [encodedData argument of hashStruct is not calculated perfectly for EIP712 singed messages in CultureIndex.sol](https://github.com/code-423n4/2023-12-revolutionprotocol-findings/issues/77)

### ERC-3525
1. [[H] Attacker Can Drain Value From Contract](https://certificate.quantstamp.com/full/solv-protocol-solv-btc/1eca9413-0b03-4b7d-9885-e5373ee2d722/index.html#findings-qs1)
   
# Go Reads 

### Cosmos SDK
1. [Incorrect Signers](https://secure-contracts.com/not-so-smart-contracts/cosmos/incorrect_getsigners/)
2. [Non-determinism](https://secure-contracts.com/not-so-smart-contracts/cosmos/non_determinism/index.html)
3. [Proposal: deterministic execution](https://github.com/golang/go/issues/33702)
4. [Non-deterministic rank calculation](https://github.com/cybercongress/go-cyber/issues/66)

### Math 
1. [Incorrect implementation of integer math functions](https://solodit.xyz/issues/incorrect-implementation-of-integer-math-functions-trailofbits-none-ochain-labs-arbos-30-nitro-upgrade-pdf)
2. [Staking] [[L] Missing Conversion to Gwei](https://certificate.quantstamp.com/full/liquid-collective-lceth/727416a8-3cf6-46fb-a103-701d5c94649e/index.html#findings-qs4)

### Dos
1. [Staking] [[M] Potential Denial of Service in Report Generation Due to Underflow](https://certificate.quantstamp.com/full/liquid-collective-lceth/727416a8-3cf6-46fb-a103-701d5c94649e/index.html#findings-qs1) 

# Rust Reads

### Dynamic Thinking 
1. [The user index is not updated if the computed reward is zero](https://github.com/SCV-Security/PublicReports/blob/19e1f50e43251f8feb07434e5c3a1067d0070454/Eris%20Protocol%2FERIS%20-%20Contracts%20ve3%20-%20Audit%20Report%20v1.0.pdf)

### Rounding
1. [Users might receive more funds due to rounding issue](https://github.com/SCV-Security/PublicReports/blob/19e1f50e43251f8feb07434e5c3a1067d0070454/Eris%20Protocol%2FERIS%20-%20Contracts%20ve3%20-%20Audit%20Report%20v1.0.pdf)

### Conditional 
1. [[L] pool.rs - Off by one error in create_position function](https://github.com/fluidity-money/long.so/blob/development/audits/hashlock.pdf)
2. [[L] pool.rs - Production code should not panic](https://github.com/fluidity-money/long.so/blob/development/audits/hashlock.pdf)
3. [[L] lib.rs - exchange function might be error prone](https://github.com/fluidity-money/long.so/blob/development/audits/hashlock.pdf)


# Pentest Web3.0 Projects

### Bugs to look for Pentest :
1. [[H] Private Key Leaked in Server Logs for ETH Wallet](https://github.com/Quillhash/QuillAudit_Reports/blob/master/TWallet%20Pentest%20Audit%20Report%20-%20QuillAudits.pdf)
2. [[H] Hardcoded Secrets, Api Keys, Private keys and more](https://github.com/Quillhash/QuillAudit_Reports/blob/master/TWallet%20Pentest%20Audit%20Report%20-%20QuillAudits.pdf)
3. [[M] Lack of Rate Limiting](https://github.com/Quillhash/QuillAudit_Reports/blob/master/TWallet%20Pentest%20Audit%20Report%20-%20QuillAudits.pdf)
4. [[M] Lack of Authentication in API Endpoints](https://github.com/Quillhash/QuillAudit_Reports/blob/master/TWallet%20Pentest%20Audit%20Report%20-%20QuillAudits.pdf)
5. [[M] Id param issue in 'get_Notiﬁcation_By_Id'](https://github.com/Quillhash/QuillAudit_Reports/blob/master/TWallet%20Pentest%20Audit%20Report%20-%20QuillAudits.pdf)
