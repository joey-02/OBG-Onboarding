# Resources

## Courses
- [Awesome course for basics](https://decentralizedthoughts.github.io/start-here/)
- [In depth course](https://ece595uwseattle.github.io/schedule)
- [Stanford course](https://cs251.stanford.edu/syllabus.html)

## Awesome papers about blockchain consensus
- [Rethinking largescale consensus](https://eprint.iacr.org/2018/302.pdf)
- [Byzantine Generals in the permissionless setting](https://arxiv.org/abs/2101.07095)
- [CAP theorum](https://arxiv.org/abs/2006.10698)
- [Hybrid BFT/Chain-based consensus](https://arxiv.org/abs/2009.04987)
- [Casper BFT finality gadget](https://arxiv.org/abs/1710.09437)

## Awesome BFT consensus papers
BFT (quorum-based) consensus emerged out of academia in the 1980s. Used in protocols such as Solana, Polygon PoS, Tendermint, and Ethereum's finality gadget! Under network partitions it optimizes for consistency (safety) instead of availability (liveness). 
- [The Byzantine General's problem](https://lamport.azurewebsites.net/pubs/byz.pdf)
- [Partial synchrony and 3f + 1 tolerance proof](https://groups.csail.mit.edu/tds/papers/Lynch/jacm88.pdf)
- [Impossibility theorems](https://groups.csail.mit.edu/tds/papers/Lynch/FischerLynchMerritt-dc.pdf)
- [BFT first adopted for blockchains](https://tendermint.com/static/docs/tendermint.pdf)
- [Next-gen BFT](https://decentralizedthoughts.github.io/2022-06-28-DAG-meets-BFT/)
- [Narwhal & Tusk](https://arxiv.org/abs/2105.11827)


## Awesome chain-based consensus papers
Chain-based consensus was invented by Satoshi Nakamoto. Used in protocols such as Bitcoin, Ethereum, and Cardano. Under network partitions it optimizes for availability (liveness) instead of consistency (safety). This means that chain splits and reorgs can happen until synchronicity is reached across nodes. Chain-based consensus allows for dynamic availability which lets nodes drop in and out during consensus rounds! 
- [Bitcoin](https://bitcoin.org/bitcoin.pdf)
- [The sleepy model of consensus](https://eprint.iacr.org/2016/918.pdf)
- [Everything is a race and Nakamoto always wins](https://arxiv.org/abs/2005.10484)
- [Formal proof of bitcoin](https://eprint.iacr.org/2014/765.pdf)
- [Speeding up synchrony](https://blog.ethereum.org/2014/07/11/toward-a-12-second-block-time)
- [Fast money grows on trees not chains (GHOST protocol)](https://eprint.iacr.org/2013/881.pdf)
- [Two attacks on PoS Ethereum](https://arxiv.org/abs/2203.01315)
- [No more attacks on PoS Ethereum?](https://eprint.iacr.org/2022/1171)


## Modular consensus
Modular consensus is an emerging paradigm that separates settlement, execution, and data availability into different networks. 
- [Data availability sampling](https://arxiv.org/abs/1809.09044)
- [Pinnochio (zk proofs)](https://eprint.iacr.org/2013/279.pdf)
- [TinyRam (zk proofs)](https://eprint.iacr.org/2013/507.pdf)
- [Cairo (zk proofs)](https://eprint.iacr.org/2021/1063.pdf)
- [RiscZero (zk proof standard ISA)](https://www.risczero.com/blog/announce)
- [Accountable safety for rollups](https://arxiv.org/abs/2210.15017)
- [Optimistic rollups](https://arxiv.org/pdf/1904.06441.pdf)
- [Meta-consensus](https://arxiv.org/abs/2210.11571)


## MEV
- [Flashboys](https://arxiv.org/abs/1904.05234)
- [Flashbots resource vault](https://github.com/flashbots/mev-research/blob/main/resources.md)
- [Blockspace economics](https://github.com/0xperp/awesome-blockspace)

## Cryptoeconomics
- [Awesome-cryptoeconomics](https://github.com/jpantunes/awesome-cryptoeconomics)
