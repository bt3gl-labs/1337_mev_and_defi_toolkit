# 🕹⛓ mev toolkit


<br>

<p align="center">
<img src="https://user-images.githubusercontent.com/1130416/210285135-2d0c3965-a3cd-44f7-a167-3ec14a9ad695.png" width="50%" align="center" style="padding:1px;border:1px solid black;"/>
 </p>


<br>

## tl; dr

<br>

#### 👾 maximal extractable value (MEV) encompasses the profits generated by participant parties in the block production supply chain, a revenue stream generated from priority gas auction (PGA).

#### 👾 MEV extraction can be a force of good in a non-predatory blockspace free-market as an incentive for economic security. order flow toxicity is a trader's exposure to counter-parties possess private informational advantages.

#### 👾 the initial concept of MEV started as a thread by [pmcgooohan](https://twitter.com/pmcgoohancrypto?lang=en) on [e/ethereum](https://www.reddit.com/r/ethereum/comments/2d84yv/miners_frontrunning/), and it was formalized by [phildaian](https://twitter.com/phildaian)'s paper [flash boys 2.0](https://arxiv.org/abs/1904.05234). 

#### ⚠️ this repository is an ongoing boundless catalog from my own research. therefore, no guarantees, no promises; use it at your own risk.

<br>

---

## 🍕 notes && code in this repo

<br>

### extraction strategies

<br>

* [arbitrage](arbitrage)
* [sandwich](sandwich)
* [liquidations](liquidations)
* [nft arbitrage](nft_arbitrage)
* [frontrunning](frontrunning)
* [backrunning](backrunning)
* [just-in-time](uniswap/uniswap-v3/just-in-time.md)
* [flashloans](flashloans)
* [sniping](sniping)
* [statistical](stat_strategies)


<br>

### mev on the chains

* [mev on ethereum](MEV_on_Ethereum)
* [mev on avalanche](MEV_on_Avalanche)
* [mev on arbitrum](MEV_on_Arbitrum)
* [mev on optimism](MEV_on_Optimism)
* [mev on solana](MEV_on_Solana)
* [mev on cosmos](MEV_on_Cosmos)
* [mev on binance](MEV_on_Binance)
* [mev on polygon](MEV_on_Polygon)

<br>

### building a toolkit

<br>

* [pvp battles](pvp_war)
* [build your mev bot](anatomy_of_mev_bots)
* [latency optimization](latency)
* [cross-domain mev](cross_domain_mev)
* [private order flows](private_order_flows)



<br>

### mev-related projects

<br>

* [flashbots](flashbots)
* [cow protocol](cow_protocol)
* [rook dao](rook)



<br>

### related defi stuff

<br>

* [uniswap](uniswap)
* [oracles, twap, twamm](oracles)
* [0x protocol and rfq](0x_protocol)
* [defi and trading](defi_and_trading)
* [daos and tokenomics](https://github.com/go-outside-labs/daos-and-tokenomics)


<br>



---

## 🍟 other resources


<br>

### mev explorers

<br>

* [ethtx transaction decoder](https://ethtx.info/)
* [tx.eth.samczsun.com](https://tx.eth.samczsun.com/)
* [public mev explorer, by metablock](https://metablock.dev/tools/mev/)
* [mev dashboard, by metablock](https://mev.metablock.dev/1/dashboard)
* [bundle explorer, by flashbots](https://flashbots-explorer.marto.lol/)
* [zero mev, by pmcgoohan](https://www.zeromev.org/)


<br>

### tx analysis

<br>

##### ethereum mainnet


* [bloxy, by bitquey](https://bloxy.info/)
* [ethvm ethereum explorer](https://www.ethvm.com/)
* [txn finance, by band protocol](https://txn.finance/)
* [ethereum token explorer, by diem](https://ethplorer.io/)
* [explorer and txs, by anyblock](https://explorer.anyblock.tools/)
* [mev explorer, by eigenphi](https://www.eigenphi.io/)
* [block explorer, by blockscout](https://blockscout.com/eth/mainnet/)
* [block explorer, by blockchair](https://blockchair.com/ethereum)
* [block and tokens explorer, by oklink](https://www.oklink.com/en/eth)
* [tx explorer, by blocksec](https://phalcon.blocksec.com/)
* [address explorer, by breadcrumbs](https://www.breadcrumbs.app/home)


##### goerli testnet


* [etherscan goerli](https://goerli.etherscan.io/)



<br>

### data && analytics

<br>

* [mev dashboard, by flashbots](https://explore.flashbots.net/).
* [cross-domain arbitrage tracker, by odos](https://www.odos.xyz/arbitrage)
* [mev live-stream, by eigenphi](https://eigenphi.io/)
* [flashloans, by blocksec](https://tools.blocksec.com/flashloan/eth)
* [sandwiched?](https://sandwiched.wtf/)
* [etherscan data on flashbots](https://etherscan.io/blocks/label/flashbots)
* [mev data corpus, by manifold](https://github.com/manifoldfinance/mev-corpus)
* [ethereum datafarm, by nerolation](https://github.com/Nerolation/ethereum-datafarm)
* [parsec.finance](https://parsec.finance/)
* [nansen](https://www.nansen.ai/)
* [token terminal](https://tokenterminal.com/terminal)



##### dune boards

* [mev-boost blocks w/ last tx w/ transfer from fee receiver to validator address](https://dune.com/ChainsightAnalytics/mev-after-ethereum-merge)
* [just-in-time liquidity sandwich large trades in uniswap v3](https://dune.com/ChainsightAnalytics/Uniswap-v3-Just-in-Time-(JIT)-Liquidity-MEV)
* [all uniswap v3 mev activity](https://dune.com/alexth/uniswap-v3-mev-activity) and [all uniswap v2 mev activity](https://dune.com/alexth/uniswap-v2-mev)
* [flashbots data for extracted good mev](https://dune.com/chorus_one/ethereum-mev-data)
* [solana mev data](https://dune.com/chorus_one_research/solana-mev-data)
* [ethereum tx reverts](https://dune.com/kroeger0x/ethereum-transaction-reverts)
* [dune board for gas prices](https://dune.com/kroeger0x/gas-prices)
* [sleuthing hashed function and event signatures](https://dune.com/agaperste/event-and-function-signature-sleuthing?)
* [mev flashbots unleashed](https://dune.com/ivanmolto/mev-flashbots-unleashed)


<br>



### useful tools 

<br>

* [abi for unverified contracts](https://abi.w1nt3r.xyz/)
* [calldata decoder](https://tools.deth.net/calldata-decoder)
* [eth converter](https://eth-converter.com/)
* [smart contract allowance checker](https://app.unrekt.net/)
* [tornado cash pool anonymity](https://tutela.xyz/)
* [eth detective](https://www.ethtective.com/address/)
* [contracts diff checker](https://etherscan.io/contractdiffchecker)
* [ultrasound money dashboard](https://ultrasound.money/)
* [revoke.cash](https://revoke.cash/)
* [ankr rpc endpoints](https://www.ankr.com/rpc/)
* [back run me](https://backrunme.com/swap)
* [ethereum signature database](https://www.4byte.directory/)
* [source of deployed ethereum contracts in vscode](https://github.com/dethcrypto/dethcode)
* [token security detector](https://gopluslabs.io/token-security/)
* [whatsabi: guess an abi for ethereum contracts](https://github.com/shazow/whatsabi)


##### gas trackers


* [eth gas alert](https://ethgasalerts.xyz/)
* [gas price io](https://www.gasprice.io/)
* [ethereum gas tracker](https://www.useweb3.xyz/gas)
* [nansei gas tracker](https://pro.nansen.ai/gas-tracker)
* [gas fee prediction](https://www.blocknative.com/gas-estimator)
* [gastrology](https://dethgasstation.eth.link/)



##### alert bots


* [mevboost bot](https://twitter.com/MevBoostBot)
* [mevrefund bot](https://twitter.com/MevRefund)
* [highgwei bot](https://twitter.com/HighGwei)
* [mev proposer bot](https://twitter.com/mevproposerbot)
* [eigenphi bot](https://twitter.com/EigenPhi_Alert)
* [mevwatch bot](https://twitter.com/mevwatchbot)



<br>


---

## 🍿 relevant readings

<br>

- [endgame, by vitalik](https://vitalik.ca/general/2021/12/06/endgame.html)
- [ethereum is a dark forest, by paradigm](https://www.paradigm.xyz/2020/08/ethereum-is-a-dark-forest)
- [escaping the dark forest, by samczsun](https://samczsun.com/escaping-the-dark-forest/)
- [how to build an ethereum mining pool, by dragonfly](https://medium.com/dragonfly-research/how-to-build-an-ethereum-mining-pool-6be356520b7a)
- [mev and me, by paradigm](https://research.paradigm.xyz/MEV)
- [return to the dark forest, by rekt](https://rekt.news/return-to-the-dark-forest/)
- [modern mev sandwich attacks, by totlsota](https://mirror.xyz/totlsota.eth/9JaNkZ1XQfQD6Y79aLYHC_kb_dSBoJ2JYiag5BuGGM8)
- [how i learned to stop worrying and love mev, by sreeni](https://medium.com/dragonfly-research/dr-reorg-or-how-i-learned-to-stop-worrying-and-love-mev-2ee72b428d1d)
- [how to light up the dark forest, by robert miller](https://writings.flashbots.net/writings/the-anatomy-of-an-inspector/)
- [hiding in plain sight, by samczsun](https://samczsun.com/hiding-in-plain-sight/)
- [we live in a mempool, by tom schmidt](https://medium.com/dragonfly-research/we-live-in-a-mempool-backrunning-the-mev-crisis-a4ea0b493b05)
- [wrecking sandwich traders for fun and profit, by n. worsley](https://github.com/Defi-Cartel/salmonella)
- [tricking frontrunners into being transaction relayers, by sankar4033](https://ethresear.ch/t/surrogeth-tricking-frontrunners-into-being-transaction-relayers/6937/1)
- [The enemy of your enemy is not your friend, by kobayashi](https://fiona.mirror.xyz/QXdCOAggA5g_j5R_JpO-V5LqK89EbimnYIV6c2rOsT0)
- [anatomy of an mev strategy: synthetix, by robert miller](https://bertcmiller.com/2021/09/05/mev-synthetix.html)
- [mev wat to do, by phill daian](https://pdaian.com/blog/mev-wat-do/)
- [mev: the first 5 years, by james prestwich](https://medium.com/@Prestwich/mev-c417d9a5eb3d)
- [mev: the next 5 years, by james prestwich](https://medium.com/@Prestwich/mev-the-next-five-years-63f84fffdf36)
- [mev-boost, relays, self-sovereignty, by dr. m. von steinkirch](https://mirror.xyz/steinkirch.eth/Xo_5rIpRQpFOC__kYfjLJVOFwlSZH2n8tUnHoXo6VyI)
- [implementing ethereum trading front-runs on the bancor exchange, by ivan bogatyy](https://hackernoon.com/front-running-bancor-in-150-lines-of-python-with-ethereum-api-d5e2bfd0d798)



<br>


### wikis || talks || ideas

<br>

* [mev research, by eigenphi](https://www.eigenphi.io/mev/research)
* [mev wiki, by automata network](https://www.mev.wiki/)
* [mev extraction strategies, by r. miller](https://docs.google.com/presentation/d/1YVFLnh_MnDtDDQjucW-UKxLD28iGlyi_Pj1ri_hGqRs/edit#slide=id.g124f588a727_0_51)
* [mev auction, by the ethereum foundation](https://ethresear.ch/t/mev-auction-auctioning-transaction-ordering-rights-as-a-solution-to-miner-extractable-value/6788)
* [the daily ape on mev](https://thedailyape.notion.site/MEV-8713cb4c2df24f8483a02135d657a221)
* [mev.day amsterdam 2022](https://mevday.org/)
* [cryptocurrency historical data snapshot](https://coinmarketcap.com/historical/)
* [mempool privacy research list, by a. obadia](https://collective.flashbots.net/t/bookmarks-relevant-for-mempool-privacy-researchers/1091)
* [cyph3rs.xyz](https://www.cyph3rs.xyz/)

<br>

### research papers

<br>

- [flash boys 2.0: frontrunning, transaction reordering, and consensus instability, by philip daian e al.](https://arxiv.org/pdf/1904.05234.pdf)
- [towards a theory of mev I, by diamandis et al.](https://people.eecs.berkeley.edu/~ksk/files/MEV_CFMM.pdf)
- [transparent dishonesty: front-running attacks on blockchain, by shayan eskandari et al.](https://arxiv.org/pdf/1902.05164.pdf)
- [combining ghost and casper, by vitalik et al.](https://arxiv.org/abs/2003.03052)
- [three attacks on pos ethereum, by caspar schwarz-schilling et al.](https://arxiv.org/abs/2110.10086)
- [two attacks on pos ghost/ethereum, by joachim neu et al.](https://arxiv.org/abs/2203.01315)
- [quantifying blockchain extractable value: how dark is the forest?, by kaihua qin et al.](https://arxiv.org/pdf/2101.05511.pdf)
- [dex arbitrage, mathematical optimizations & me, by noxx](https://noxx.substack.com/p/dex-arbitrage-mathematical-optimisations)
- [censorship resistance in on-chain auctions, by m. pai et al.](https://github.com/eljhfx/Decentralized-Auctions/blob/main/Censorship_Resistance_in_On-Chain_Auctions.pdf)



<br>


---


## 🌭 [bonus] 𝕥𝕙𝕖 𝕞𝕒𝕜𝕖 𝕠𝕗 𝕒 𝕔𝕪𝕡𝕙𝕖𝕣𝕡𝕦𝕟𝕜

<br>

* [a graduate course in applied cryptography, by dan boneh](http://toc.cryptobook.us/)
* [the cypherpunk manifest, by eric hughes](https://activism.net/cypherpunk/manifesto.html)
* [the crypto anarchist manifest, by timothy c. may](https://nakamotoinstitute.org/crypto-anarchist-manifesto/)
* [the hacker manifest, by the mentor](http://phrack.org/issues/7/3.html)
* [bitcoin whitepaper by satoshi nakamoto](https://bitcoin.org/bitcoin.pdf)
* [the meaning of decentralization, by vitalik](https://medium.com/@VitalikButerin/the-meaning-of-decentralization-a0c92b76a274)
* [teal organizations wiki](https://reinventingorganizationswiki.com/)

<br>
<br>

