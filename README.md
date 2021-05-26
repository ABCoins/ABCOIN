# ABCOIN

[![Build Status](https://travis-ci.com/ABcoin/ABcoin.svg?branch=master)](https://travis-ci.com/ABcoin/ABcoin)

ABcoin is a cryptocurrency like Bitcoin, although it  use SHA256 as
its proof of work (POW). ABcoin currently employs a simplified variant of scrypt.
- **Website:** ! （1） ![ABCOIN](https://user-images.githubusercontent.com/68141675/118925483-64e36800-b971-11eb-8753-b6cbca29976d.jpg)
- （Use your WeChat scan code to dig）

   （2）![ABLK](https://user-images.githubusercontent.com/68141675/118925826-f18e2600-b971-11eb-928f-996282f50586.jpg)
   
   （3）AB movie For sale！
   
   （4）ABwk  For sale！
   
   For sale！
  
  Financial news：
 1：https://www.chainhoo.com/archives/128197 
 2：http://www.weilaicaijing.com/article/57259
 3： http://www.fn.com/news/152762.html 
 4：http://fengniaocaijing.com/article/detail?article_id=237217

## License – Much license ⚖️
ABcoin Core is released under the terms of the MIT license. See
[COPYING](COPYING) for more information or see
[opensource.org](https://opensource.org/licenses/MIT)

## Development and contributions – omg developers
Development is ongoing, and the development team, as well as other volunteers,
can freely work in their own trees and submit pull requests when features or
bug fixes are ready.

#### Version strategy
Version numbers are following ```major.minor.patch``` semantics.

#### Branches
There are 3 types of branches in this repository:

- **master:** Stable, contains the latest version of the latest *major.minor* release.
- **maintenance:** Stable, contains the latest version of previous releases, which are still under active maintenance. Format: ```<version>-maint```
- **development:** Unstable, contains new code for planned releases. Format: ```<version>-dev```

*Master and maintenance branches are exclusively mutable by release. Planned*
*releases will always have a development branch and pull requests should be*
*submitted against those. Maintenance branches are there for **bug fixes only,***
*please submit new features against the development branch with the highest version.*

#### Contributions ✍️

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/qa) of the RPC interface, written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/qa) are installed) with: `qa/pull-tester/rpc-tests.py`

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

## Very Much Frequently Asked Questions ❓

### How much ABC can exist? 
Early 2021  there will be
approximately 100,000,000 coins.
Each subsequent block will grant 10,000 coins to encourage miners to continue to
secure the network and make up for lost wallets on hard drives/phones/lost
encryption passwords/etc.


### Such mining information ⛏

ABcoin uses a simplified variant of the scrypt key derivation function as its
proof of work with a target time of one minute per block and difficulty
readjustment after every block. The block rewards are fixed and halve every
100,000 blocks. Starting with the 600,000th block, a permanent reward of
10,000 Dogecoin per block will be issued.  

