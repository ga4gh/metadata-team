## GA4GH "Metadata" Testing & Discussions

As of the 5th GA4GH plenary (Orlando, 2017-10-15), the metadata development (schema & discussions) has found a new homme:

* [ga4gh-metadata Github repository](https://github.com/ga4gh-metadata/)
* the associated [website](https://ga4gh-metadata.github.io/ga4gh-metadata/)

This repository has been retired.





Previous Notes:
---------------

* [Test datasets as "ready for MongoDB" collections](https://github.com/mbauprogenetixdis/arraymap2ga4gh/), based on the cancer genome data collection from [arraymap.org](http://arraymap.org)
* This is an actively maintained implementation of the current and some forward looking (i.e. with a reasonable PR/plan) schema features. It should be possible to get the collections, load them into an e.g. MongoDB instance, and the test methods against these. This implementation study is part of [Elixir's human data projects](http://elixir-europe.org).

The metadata-team project is a communication and "playground" area for exchanging data and ideas regarding everything metadata<sup>*</sup>. The main envisioned usage for now is to add (PR) documents examplifying data annotation usage scenarios.

The standard usage would be to create a fork of the repositry, and then to add/edit the respective documents. For example files, the preference would be to create dummy cases as <document>.json files.

For further information, please consult the [GA4GH.DWG.MTT wiki](https://github.com/ga4gh/metadata-team/wiki).


(<sup>*</sup>Everything but the sequence<sup>TM</sup>)
