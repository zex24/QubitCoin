Qubitcoin Core integration/staging tree
=======================================

https://qubitcoin.cc

What is Qubitcoin?
-----------------

Qubitcoin is an experimental new digital currency that enables instant payments to
anyone, anywhere in the world. Qubitcoin uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Qubitcoin Core is the name of open source
software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Qubitcoin Core software, see https://qubitcoin.cc

License
-------

Qubitcoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Qubitcoin
development team members simply pulls it.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see [doc/developer-notes.md](doc/developer-notes.md)) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/qubitcoin/qubitcoin/tags) are created
regularly to indicate new official, stable release versions of Qubitcoin.

Testing
-------

### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run (assuming they weren't disabled in configure) with: `make check`

### Manual Quality Assurance (QA) Testing

Large changes should have a test plan, and should be tested by somebody other
than the developer who wrote the code.
See https://github.com/bitcoin/QA/ for how to create a test plan.

