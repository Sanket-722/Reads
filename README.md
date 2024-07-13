![WhatsApp Image 2024-03-16 at 6 04 04 PM](https://github.com/Sanketx0722/solo-audit-reports/assets/59367143/f43cc84a-b567-47ff-9e97-1ff913bd39af)

# Audit Reports
A collection of solo audit reports From Contest or By WEB3 security experts. So Its collection of Reports I daily read and I will try to make it orginized as much as possible.

# Reads 
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

### DOS
1. [[M] Possible DOS in 'allVestingRecipients()' function because of unbounded gas consumption.](https://github.com/code-423n4/2022-09-vtvl-findings/issues/372)
2. [[M] [Denial-of-Service] Contract Owner Could Block Users From Withdrawing Their Strike](https://solodit.xyz/issues/m-06-denial-of-service-contract-owner-could-block-users-from-withdrawing-their-strike-code4rena-putty-putty-contest-git)
3. [[H] Denial of Service](https://solodit.xyz/issues/h-02-denial-of-service-code4rena-hubble-hubble-contest-git)
4. [[M] Malicious users could block liquidation or perform DOS](https://solodit.xyz/issues/m-4-malicious-users-could-block-liquidation-or-perform-dos-sherlock-notional-update-5-git)
5. [Vault can be placed back into vulnerable low supply state](https://solodit.xyz/issues/vault-can-be-placed-back-into-vulnerable-low-supply-state-openzeppelin-pods-finance-ethereum-volatility-vault-audit-2-markdown)
6. [Potential funds locked due low token decimal and long stream duration](https://solodit.xyz/issues/potential-funds-locked-due-low-token-decimal-and-long-stream-duration-spearbit-locke-pdf)
7. [[M] Unhandled chainlink revert would lock all price oracle access](https://solodit.xyz/issues/m-09-unhandled-chainlink-revert-would-lock-all-price-oracle-access-code4rena-juicebox-juicebox-v2-contest-git)

### Conditional
1. [[M] !_account.isContract() can be bypassed](https://github.com/code-423n4/2022-04-jpegd-findings/issues/128)

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

### Logical
1. [getUserInfo() returns incorrect values for locked and stakedAmount ](https://github.com/sherlock-audit/2022-10-union-finance-judging/issues/80)
2. [Maximal approvals remain for the AssetManager's adapters and tokens after removal](https://github.com/sherlock-audit/2022-10-union-finance-judging/issues/36)

### Swap 
1. [[M] `UNISWAP_FEE` is hardcoded which will lead to significant losses compared to optimal routing](https://solodit.xyz/issues/m-02-uniswap_fee-is-hardcoded-which-will-lead-to-significant-losses-compared-to-optimal-routing-code4rena-sturdy-sturdy-contest-git_)
2. [[M] `SWAP_ROUTER` in `AutoPxGmx.sol` is hardcoded and not compatible on Avalanche](https://solodit.xyz/issues/m-02-uniswap_fee-is-hardcoded-which-will-lead-to-significant-losses-compared-to-optimal-routing-code4rena-sturdy-sturdy-contest-git_)
3. [[M] AddLiquidity and decreaseLiquidity missing slippage protection](https://solodit.xyz/issues/m-15-addliquidity-and-decreaseliquidity-missing-slippage-protection-code4rena-particle-protocol-particle-protocol-git)
4. [[M] Duplicate LP token could lead to incorrect reward distribution](https://github.com/code-423n4/2022-05-aura-findings/issues/124)
5. [Missing ```fromToken != toToken``` check in ```MarginRouter.crossSwapExactTokensForTokens/MarginRouter.crossSwapTokensForExactTokens```](https://github.com/code-423n4/2021-04-marginswap-findings/issues/20)

### Oracle
1. [_updateTwav() and _getTwav() will revert when cumulativePrice overflows](https://github.com/code-423n4/2022-06-nibbl-findings/issues/246)
2. [[M] Chainlink’s latestRoundData might return stale or incorrect results](https://solodit.xyz/issues/m-05-chainlinks-latestrounddata-might-return-stale-or-incorrect-results-code4rena-mochi-mochi-contest-git)
3. [Should check return data from Chainlink aggregators](https://github.com/code-423n4/2021-05-fairside-findings/issues/70)
4. [ChainlinkAdapterOracle use BTC/USD chainlink oracle to price WBTC which is problematic if WBTC depegs](https://github.com/sherlock-audit/2023-02-blueberry-judging/issues/9)
5. [```.latestRoundData()``` does not update the oracle - ```ExchangeRate.sol```](https://github.com/code-423n4/2021-08-notional-findings/issues/18)
6. [MISUSE OF AN ORACLE](https://solodit.xyz/issues/misuse-of-an-oracle-halborn-planet-finance-pdf)
7. [ChainlinkAdapterOracle will return the wrong price for asset if underlying aggregator hits minAnswer](https://github.com/sherlock-audit/2023-02-blueberry-judging/issues/18)
8. [Oracle periodSize = 0 which is as same as not using any oracle.](https://github.com/code-423n4/2022-06-canto-v2-findings/issues/8)

### Decimal
1. [Interest accrued could be zero for small decimal tokens](https://github.com/code-423n4/2022-03-sublime-findings/issues/10)


### Math
1. [Permanent freeze of vested tokens due to overflow in _baseVestedAmount](https://github.com/code-423n4/2022-09-vtvl-findings/issues/95)
2. [Lack of sanity check on _initialTokenSupply and _initialTokenPrice can lead to a seller losing his NFT](https://github.com/code-423n4/2022-06-nibbl-findings/issues/24)
3. [Unsafe downcasting arithmetic operation in UserManager related contract and in UToken.sol](https://github.com/sherlock-audit/2022-10-union-finance-judging/issues/96)
4. [FRAX admin can adjust fee rate to harm Napier and its users ](https://github.com/sherlock-audit/2024-01-napier-judging/issues/108)
5. [Incorrect unlockTime can DOS withdrawGovernanceAsset](https://github.com/code-423n4/2022-01-behodler-findings/issues/228)

### Tokens
1. [AutoleverageBase: Must approve 0](https://github.com/code-423n4/2022-05-alchemix-findings/issues/144)

### Uniswap 
1. [block.timestamp or deadline ](https://solodit.xyz/issues/m-06-blocktimestamp-or-deadline-code4rena-amun-amun-contest-git)

### Access Control
1. [Any public vault without a delegate can be drained](https://github.com/sherlock-audit/2022-10-astaria-judging/issues/69)
