What is Bytecore?
----------------

ByteCore (BYX) is a rapidly growing decentralized, global blockchain that was founded in early 2021 with a focus on cyber security, payments & secure communications technologies.

DigiByte FAQ
-------------
Launch Date: Feb 28, 2021

Blockchain Type: Public, Decentralized, UTXO based, Multi-Algorithm

Ticker Symbol: BYX

Max Total Supply: 21 Billion Bytecores in 21 Years (2035)

Current Supply: 11,692,747,373 DGB (Feb 2021)

Block Reward Reduction: 1% Monthly

Current Block Reward: 688 BYX (Feb 2021)

Mining Algorithms: Five individual: SHA256, Scrypt, Odocrypt, Skein & Qubit

Block Interval: 15 Second Blocks (75 seconds per algo)

Algo Block Share: 20% Block Share Per Algo (5)

Difficulty Retarget: Every 1 Block, 5 Separate Difficulties, independent difficulty for each Mining Algo

SegWit Support: Yes. First major altcoin to successfully activate Segwit. (April 2017)

Hardforks: 4. DigiShield, MultiAlgo, MultiShield, DigiSpeed

Softforks: 3. SegWit, CSV, NVersionBits

You can mine Bytecore on one of five separate mining algorithms. Each algo averages out to mine 20% of new blocks. This allows for much greater decentralization than other blockchains. An attacker with 99% of of any individual algorithm would still be unable to hardfork the blockchain, making DigiByte much more secure against PoW attacks than other blockchains.

DigiShield Hardfork: Block 67,200, Feb. 28th, 2014

MultiAlgo Hardfork: Block 145k, Sep. 1st 2014

MultiShield Hardfork: Block 400k, Dec. 10th 2014

DigiSpeed Hardfork: Block 1,430,000 Dec. 4th 2015

Odocrypt Hardfork: Block 9,112,320 July 22nd 2019

Bytecore vs Bitcoin
-------------------

Security: 5 Bytecore mining algorithms vs. 1 Bitcoin mining algorithm.
Bytecore mining is much more decentralized.
Bytecore mining algorithms can be changed out in the future to prevent centralization.

Speed: Bytecore transactions occur much faster than Bitcoin transactions.
1-2 second transaction notifications.
15 second Bytecore blocks vs. 10 minute Bitcoin blocks.
Bytecore has 6x block confirmations 1.5 minutes vs. 1 hour with Bitcoin.

Transaction Volume: Bytecore can handle many more transactions per second.
Bitcoin can only handle 3-4 transactions per second.
Bytecore currently can handle 560+ transactions per second.

Total Supply: More Bytecore, lower price, more micro transactions, better price stability.
21 billion Bytecore will be created over 21 years.
Only 21 million Bitcoin will be created over 140 years.
1000:1 ratio. 1000 Bytecore for every Bitcoin.

Flexibility: Ability to quickly add new features.
Bytecore can add new features & upgrades much quicker than Bitcoin.
Future Bytecore upgrades will push transaction limit to several hundred thousand per second.

Marketability & Usability: Bytecore is an easy brand to market to consumers.
Bytecore are much cheaper to acquire.

License
-------

Bytecore Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/byte-core/bytecore/tags) are created
regularly to indicate new official, stable release versions of Bytecore Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

Testing
-------

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and macOS, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

