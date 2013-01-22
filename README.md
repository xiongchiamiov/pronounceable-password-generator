Want pronounceable passwords that aren't real words?  This is for you!

# Pronounceable Passphrase Generation #

It's recently [come to people's attention][xkcd] that long pass*phrases* of
multiple words are better than short pass*words* that are hard to remember.  As
a result, [there are][xkcd-generator] passphrase generators that string
together a number of words.

However, this approach still allows dictionary attacks.  If you [use uncommon
words][ppg], it's better, but I still like to use words that don't actually
exist.  It's still important to have things my brain *thinks* are words,
though, because "words" I can pronounce are easier to remember than strings of
random characters.

The backend is written by [Tom Van Vleck][tvv], based on work by Morrie Gasser.
In addition to [this Javascript version][gpw-js], he has written made it
available [in Java][gpw-java], [in C][gpw-c], and [for iOS][gpw-ios].

gpw-js (and this frontend to it) is available under the following license:

* Share your source with others freely
* Let Tom Van Vleck know you're using it
* Give me credit, and all the other pioneers, if you use the data or algorithms

[xkcd]: http://xkcd.com/936/
[xkcd-generator]: http://passphra.se/
[ppg]: https://github.com/mysmallidea/pronounceable-password-generator
[tvv]: http://www.multicians.org/thvv/tvv-home.html?1
[gpw-js]: http://www.multicians.org/thvv/gpw-js.html
[gpw-java]: http://www.multicians.org/thvv/gpw.html
[gpw-c]: http://www.multicians.org/thvv/tvvtools.html
[gpw-ios]: http://www.multicians.org/thvv/gpwapp/index.html

