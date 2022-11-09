[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/

# Links til undervisningen
## Kod dig selv
https://knitty.com/ISSUEspring04/FEATgeekcode.html
## Evaluering
Hjælp os med at blive bedre og skarpere - https://www.survey-xact.dk/LinkCollector?key=ECMA55GAU51N


# Strik og Kod

Dette repositorie indeholder materialet fra workshoppen Strik og Kod fra AU Library, Det Kgl. Bibliotek.  

Workshoppen handler om at trække paralellerne mellem strikning og kodning. "Kodning" forståes i denne sammenhæng som kodebaseret databehandling og lægger sig derfor inden for feltet data science. Som følge af workshoppens afsæt på Arts vil det nærmere blive et text mining eksempel. I text mining er man interesseret i at udtrække informationer af store mængder tekst - hvilket netop interesserer de fleste humanister.

Ingen kageopskrift uden et billede af kagen som noget af det første. Det samme gør sig gældende her. Det endelige resultat af S_K.Rmd(S_K_arbejdsbog.Rmd bruges live til workshops) er visualiseringen herunder, der viser hvilke ord, der bruges før forskellige ord om strikning. I grafen kan vi se at der går en pil fra "bomulds" og peger mod "strikkegarn", hvilket betyder, at det har optrådt som "bomulds garn". Jo mere markant pilen er jo flere forekomster har der været. Således kan vi altså se at et meget hyppigt forekommende ordpar er "di strikt", hvilken tydeligvis er en fejllæsning af ordet "distrikt". Dette handler om at vores data er maskingenkendt, hvilket ikke altid går lige godt.  

Er du interesseret? Så download S_K.Rmd og kør den chunk for chunk i din desktop R-studio. Alternativt kan du oprette dig hos [Rstudio Cloud](https://rstudio.cloud) og oprette et nyt projekt med linket til dette github repositorie.  

![](strikke_bigrams.png)

# Nyttige links/læsninger under og efter workshoppen
## Under: 
* [The Knitter’s Geek Code](https://knitty.com/ISSUEspring04/FEATgeekcode.html)
* [Strik & Kod Notebook lavet af Max](http://hax.odsbjerg.dk/SK_handson_notesbog.html)
* [Evaluering af kurset](https://www.survey-xact.dk/LinkCollector?key=ECMA55GAU51N)
## Efter: 
### Til inspiration
* [Knit, purl and upload: new technologies, digital mediations and the experience of leisure](https://www.tandfonline.com/doi/full/10.1080/02614367.2012.723730)
* [Knitting Ourselves Into Being: the Case of Labour and Hip Domesticity on the Social Network Ravelry.com](https://www.semanticscholar.org/paper/Knitting-Ourselves-Into-Being%3A-the-Case-of-Labour-Hellstrom/2ac8f26e4f98ece3a2dea5c608589393da48acf1) 
* [Secure Your Home IoT with the CryptoCrochetKey](https://criticalcode.recipes/contributions/secure-your-home-iot-with-the-cryptocrochetkey) 
* [Random Stripe Generator, eksporter i HTML](http://www.biscuitsandjam.com/stripe_maker.php)
* [Mariko Kosaka: Knitting for Javascripters](https://www.youtube.com/watch?v=X1Cc1vrvjdY&t=3s)
* [Code Academy: Learn to Code for Free](https://www.codecademy.com/)
* [R-Ladies: global organisation med fokus på kønsdiversitet i R-fællesskaber – Følg dem på Twitter her ](https://twitter.com/rladiesaarhus)
* [Tekst mining-kursus med Max her på AUL](https://library.au.dk/arrangementer)
### Kom igang med din egen tekstmining
* [Tidy Text Mining with R](https://www.tidytextmining.com)
* [Importer dine egne tekstfiler!](https://github.com/maxodsbjerg/ImportingTextFiles)
* [Danish Newspaper API](http://labs.statsbiblioteket.dk/labsapi/api//api-docs?url=/labsapi/api/openapi.yaml)
* [Cheatsheet til Mediestream-søgning](https://gist.github.com/maxodsbjerg/e2dd484d3c9dcaa9c422a861d6a93f6e#file-denspanskesyge-md)

## References 
Csardi, Gabor, and Tamas Nepusz. 2006. “The Igraph Software Package for Complex Network Research.” *InterJournal* Complex Systems: 1695. https://igraph.org.
Fellows, Ian. 2018. *Wordcloud: Word Clouds*. https://cran.r-project.org/web/packages/wordcloud/index.html.
Silge, Julia, and David Robinson. 2016. “Tidytext: Text Mining and Analysis Using Tidy Data Principles in r.” *JOSS* 1 (3). https://doi.org/10.21105/joss.00037.
Wickham, Hadley, Mara Averick, Jennifer Bryan, Winston Chang, Lucy D’Agostino McGowan, Romain François, Garrett Grolemund, et al. 2019. “Welcome to the tidyverse.” *Journal of Open Source Software* 4 (43): 1686. https://doi.org/10.21105/joss.01686.
