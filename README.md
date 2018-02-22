Vertcoin Core integration/staging tree
=====================================

https://vertcoincash.org

What is Vertcoin Cash?
----------------

Vertcoin Cash is a fork of Vertcoin that is a fork of Bitcoin that is designed to resist the monopolisation of
mining power and perform better than Vertcoin.
 - 1 minute block targets
 - subsidy halves in 1,051,200 blocks (~2 years)
 - ~420 million total coins
 - 500 coins per block (25 after block 420,000)
 - Difficulty retargeting every block to recover from large hashrate swings
 - Lyra2REv2 proof of work algorithm for ASIC resistance

For more information, as well as an immediately useable, binary version of
the Vertcoin client sofware, see http://www.vertcoincash.org.

License
-------

Vertcoin Cash Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/vertcoincash/vertcoincash/tags) are created
regularly to indicate new official, stable release versions of Vertcoin Core.

Developers work on their own forks and submit pull requests in order to merge
changes with `master`. Due to the relatively small size of the development team,
developers also commit directly to the repo often. Anyone is allowed to contribute
though and useful pull requests will almost always be accepted given various
obvious stipulations regarding stability etc. 

The Vertcoin Cash [discord](https://discord.gg/AnC3K) or [subreddit](https://reddit.com/r/vertcoincash)
should be used to discuss complicated or controversial changes with the developers 
before working on a patch set.

Testing
-------

Vertcoin Cash currently relies on Vertcoin Core and Bitcoin Core for its testcases, and few of them are
known to work, though the software is based on fully test conforming upstream 
Bitcoin and Vertcoin Core versions. We would be grateful to those who can help port the existing
Vertcoin Core test cases to Vertcoin Cash such that they can be used to assure correctness.

Translations
------------

Changes to translations as well as new translations can be submitted to as pull
requests to this repo or to upstream Vertcoin Core.
