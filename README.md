![Screenshot from 2024-07-13 19-54-08](https://github.com/user-attachments/assets/6a74f7f6-394c-4986-9135-e43861e2b925)

# Audit Reports
A collection of solo audit reports From Contest or By WEB3 security experts. So Its collection of Reports I daily read and I will try to make it orginized as much as possible.

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
17. [THORChain_Router’s‌‌transferOut‌‌ does‌‌ not‌‌ check‌‌ transfer‌‌ return‌‌ values No 8](https://github.com/thorchain/Resources/blob/master/Audits/THORChain-TrailOfBits-FullAudit-Aug2021.pdf)  

### Logical
1. [getUserInfo() returns incorrect values for locked and stakedAmount ](https://github.com/sherlock-audit/2022-10-union-finance-judging/issues/80)
2. [Maximal approvals remain for the AssetManager's adapters and tokens after removal](https://github.com/sherlock-audit/2022-10-union-finance-judging/issues/36)

### Swap 
1. [[M] `UNISWAP_FEE` is hardcoded which will lead to significant losses compared to optimal routing](https://solodit.xyz/issues/m-02-uniswap_fee-is-hardcoded-which-will-lead-to-significant-losses-compared-to-optimal-routing-code4rena-sturdy-sturdy-contest-git_)
2. [[M] `SWAP_ROUTER` in `AutoPxGmx.sol` is hardcoded and not compatible on Avalanche](https://solodit.xyz/issues/m-02-uniswap_fee-is-hardcoded-which-will-lead-to-significant-losses-compared-to-optimal-routing-code4rena-sturdy-sturdy-contest-git_)
3. [[M] AddLiquidity and decreaseLiquidity missing slippage protection](https://solodit.xyz/issues/m-15-addliquidity-and-decreaseliquidity-missing-slippage-protection-code4rena-particle-protocol-particle-protocol-git)
4. [[M] Duplicate LP token could lead to incorrect reward distribution](https://github.com/code-423n4/2022-05-aura-findings/issues/124)
5. [Missing ```fromToken != toToken``` check in ```MarginRouter.crossSwapExactTokensForTokens/MarginRouter.crossSwapTokensForExactTokens```](https://github.com/code-423n4/2021-04-marginswap-findings/issues/20)
6. [[H] swapTokens Function Is Unusable](https://solodit.xyz/issues/swaptokens-function-is-unusable-openzeppelin-none-radiant-riz-audit-markdown)

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
2. [Malicious actors can lock all FEI and TRIBE in the GenesisGroup](https://solodit.xyz/issues/m01-malicious-actors-can-lock-all-fei-and-tribe-in-the-genesisgroup-openzeppelin-fei-protocol-audit-markdown)
3. [onlyOwner Role Can Unintentionally Influence "settleAuction()"](https://solodit.xyz/issues/m-03-onlyowner-role-can-unintentionally-influence-settleauction-code4rena-kuiper-kuiper-contest-git)
4. [[M]Hackers can deploy token with respective name as the stable one to impersonate the stable token](https://solodit.xyz/issues/m-03-hackers-can-deploy-token-with-respective-name-as-the-stable-one-to-impersonate-the-stable-token-code4rena-canto-canto-git)
5. [[C] Slot Collision](https://www.trust-security.xyz/post/learning-by-breaking-a-layerzero-case-study-part-one)

### CrossChain
1. [[M] It Will Not Be Possible to Bridge DAI to Blast](https://solodit.xyz/issues/across-it-will-not-be-possible-to-bridge-dai-to-blast-openzeppelin-none-across-v3-and-oval-incremental-audit-markdown)
2. [[L] Error-Prone Initialization of Blast_Adapter.sol](https://blog.openzeppelin.com/across-v3-and-oval-incremental-audit#:~:text=%5BAcross%5D-,Error%2DProne%20Initialization%20of%20Blast_Adapter.sol,-The%20constructor%20of)
3. [[L] Permit2 Witness Is Not Fully Compliant With EIP-712](https://blog.openzeppelin.com/across-v3-and-oval-incremental-audit#:~:text=%5BAcross%5D-,Permit2%20Witness%20Is%20Not%20Fully%20Compliant%20With%20EIP%2D712,-The%20ERC7683Permit2Lib%20library)
4. [[L]  Users May Lose Assets if They Specify an Empty Address as a Call Target](https://blog.openzeppelin.com/across-v3-and-oval-incremental-audit#:~:text=%5BAcross%5D-,Users%20May%20Lose%20Assets%20if%20They%20Specify%20an%20Empty%20Address%20as%20a%20Call%20Target,-The%20attemptCalls%20function)

### Other 
1. [Incorrect hardcoded address](https://solodit.xyz/issues/incorrect-hardcoded-address-mixbytes-none-barter-dao-markdown)

   
# Go Reads 

### Cosmos SDK
1. [Incorrect Signers](https://secure-contracts.com/not-so-smart-contracts/cosmos/incorrect_getsigners/)
2. [Non-determinism](https://secure-contracts.com/not-so-smart-contracts/cosmos/non_determinism/index.html)
3. [Proposal: deterministic execution](https://github.com/golang/go/issues/33702)
4. [Non-deterministic rank calculation](https://github.com/cybercongress/go-cyber/issues/66)

### Math 
1. [Incorrect implementation of integer math functions](https://solodit.xyz/issues/incorrect-implementation-of-integer-math-functions-trailofbits-none-ochain-labs-arbos-30-nitro-upgrade-pdf)
