# A conduit for parsing network frames

`network-data-conduit` provides a `Conduit` that allows you to parse
`ByteString`s into network data structures like IPv4/6, UDP, TCP and
IP headers.

**See also**: [pcap-conduit][] provides a simple `Source` you can use
to capture such data from `pcap` files or live network interfaces.

[travis-ci.org](http://travis-ci.org) results: [![Build Status](https://secure.travis-ci.org/thoughtpolice/network-data-conduit.png?branch=master)](http://travis-ci.org/thoughtpolice/network-data-conduit)

# Installation

It's just a `cabal install` away on [Hackage][]:

```
$ cabal install network-data-conduit
```

# Join in

File bugs in the GitHub [issue tracker][].

Master [git repository][gh]:

* `git clone https://github.com/thoughtpolice/network-data-conduit.git`

There's also a [BitBucket mirror][bb]:

* `git clone https://bitbucket.org/thoughtpolice/network-data-conduit.git`

# Authors

See [AUTHORS.txt](https://raw.github.com/thoughtpolice/network-data-conduit/master/AUTHORS.txt).

# License

BSD3. See [LICENSE.txt](https://raw.github.com/thoughtpolice/network-data-conduit/master/LICENSE.txt) for terms of copyright and redistribution.


[pcap-conduit]: http://github.com/thoughtpolice/pcap-conduit
[main page]: http://thoughtpolice.github.com/network-data-conduit
[issue tracker]: http://github.com/thoughtpolice/network-data-conduit/issues
[gh]: http://github.com/thoughtpolice/network-data-conduit
[bb]: http://bitbucket.org/thoughtpolice/network-data-conduit
[Hackage]: http://hackage.haskell.org/package/network-data-conduit
