Aragonese monolingual crawled corpus
==========================================================================================================

## About this corpus
This package contains Aragonese corpus crawled from different websites:
* https://estricalla.blogspot.com/?m=1
* https://bomboloniar.blogspot.com/?m=1
* http://blog.estauaragones.org/blog/
* https://www.consello.org/blog/
* https://www.europapress.es/
* http://academiadelaragones.org/index.htm

Work carried out within the project "Lightweight neural translation technologies for low-resource languages", funded by he Spanish Ministry of Science and Innovation (MCIN), the Spanish Research Agency and European Regional Development Fund A way to make Europe.


## Versions
Two versions of the crawled corpus are available. [crawled.gz](crawled.gz) is the result of applying a language identifier trained on Spanish, Catalan, Aranese, Aragonese, Occitan and Asturian (available soon). Contains 140.000 sentences from the original 3.000.000 crawled.
[crawled_filtered.gz](crawled_filtered.gz) was obtained by applying the [LangID](https://github.com/saffsd/langid.py) identifier to [crawled.gz](crawled.gz) and discarding the sentences identified as Spanish. Contains 25.000 sentences.


## License
These data are released under this licensing scheme:
 * We do not own any of the text from which these data has been extracted.
 * We license the actual packaging of these parallel data under the Creative
   Commons CC0 license ("no rights reserved").

## Notice and take down policy
Notice: Should you consider that our data contains material that is owned by
you and should therefore not be reproduced here, please:

 * Clearly identify yourself, with detailed contact data such as an address,
   telephone number or email address at which you can be contacted.
 * Clearly identify the copyrighted work claimed to be infringed.
 * Clearly identify the material that is claimed to be infringing and
   information reasonably sufficient to allow us to locate the material. 
 * And contact aaron.galiano@ua.es

Take down: We will comply to legitimate requests by removing the affected
sources from the next release of the corpus.
