# Concordance of the *Mūlakārikā*s of Bhartṛhari's *Vākyapadīya*, Brahmakāṇḍa

This repository contains the data used to generate my table of
correspondences of the *mūlakārikā*s of the first chapter of Bhartṛhari's
*Vākyapadīya*. See [this file](https://hal.archives-ouvertes.fr/hal-02172588)
for details on each edition and for the table itself.

The data is available in [CSV](https://en.wikipedia.org/wiki/Comma-separated_values) format. There is one file per edition, three in total. Each file defines five fields, as follows:

| # | Field name  | Description                                                |
|---|-------------|------------------------------------------------------------|
| 0 | id          | The number of the stanza in Rau's edition. This value can be used as identifier.  |
| 1 | number      | The number of the stanza in this edition (a positive integer). For Rau's edition, this holds the same value as the "id" field. |
| 2 | location    | Whether, in this edition, the stanza is located in the *mūla* text or in the *vṛtti*. If it is located in the *mūla* text, holds the integer 0, otherwise 1. For Rau's edition, this field always holds the value 0. |
| 3 | start-page  | Number of the page on which the *kārikā* starts (a positive integer).           |
| 4 | end-page    | Number of the page on which the *kārikā* ends. If the *kārikā* fits on a single page, holds the same value as the "start-page" field. |


