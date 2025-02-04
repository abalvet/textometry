# textometry
A simple standalone textometry/lexicometry applet, inspired by platforms such as TXM [https://txm.gitpages.huma-num.fr/textometrie/], Hyperbase [https://hyperbase.unice.fr/], among others.
This applet is intended as a simple turn-key solution to compare texts from different authors, genres, periods, topics, etc.
The specificity analysis is inspired by P. Lafon's proposal, and thus relies on the hypergeometric distribution law, and not the normal distribution (as in R Stylo). In this applet, a simplified version of the hypergeometric distribution is implemented. Moreover, tokenization rules are extremely simple, and are French-specific (although they also work for English, Spanish, etc.). Therefore, results and scores as compared to TXM and Hyperbase **will** differ (specificity scores). Nevertheless, users will still be able to retrieve subsets of Corpus A / Corpus B specific tokens: specificity ranges will be slightly different between TXM and this applet, but the overall specific tokens will still be identified.

Feel free to use this applet to get a feeling of the specificity analysis, then move on to TXM and Hyperbase for more robust results.

As said before, tokenization rules are extremely simple, developers are advised to modify these to suit their specific needs.
