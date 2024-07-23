# Pan-Iberian Language Archival Resource (PILAR)

This repository contains the PILAR corpora, produced as part of the R+D+i poject [Lightweight neural translation technologies for low-resource languages (LiLowLa)](https://transducens.dlsi.ua.es/lilowla/) (PID2021-127999NB-I00) funded by the Spanish Ministry
of Science and Innovation (MCIN), the Spanish Research Agency (AEI/10.13039/501100011033) and the European Regional Development Fund A way to make Europe. 

PILAR contains a collection of low-resource language corpora from the Iberian Peninsula. These corpora have been generated from various monolingual and parallel resources to facilitate research and development in the field of Romance languages.

## Included Languages

PILAR includes corpora for the following languages:

- [Aragonese](https://github.com/transducens/PILAR/tree/main/aragonese)
- [Aranese](https://github.com/transducens/PILAR/tree/main/aranese)
- [Asturian](https://github.com/transducens/PILAR/tree/main/asturian)
- [Balearic](https://github.com/transducens/PILAR/tree/main/balearic)
- [Valencian](https://github.com/transducens/PILAR/tree/main/valencian)

## Structure

Each language corpus is organized into its respective folder within the repository. Additionally, each language folder contains its own README file providing details about the resources used to create the corpus.

In addition, [FLORES+.zip](https://github.com/transducens/PILAR/blob/main/FLORES%2B.zip) file contains translations of the dev and devtest sets of [FLORES+](https://github.com/openlanguagedata/flores) into Aragonese, Aranese, and Asturian. Although FLORES+ already includes an Asturian version, the version published in this repository has been revised. The file also contains the corresponding original Spanish side of FLORES+.

As in the original FLORES+ repository, the files are provided compressed (password: `multilingual machine translation`) to prevent them from being automatically crawled and added to training datasets.

## License
These data are released under this licensing scheme:
 * We do not own any of the text from which these data has been extracted.
 * We license the actual packaging of these parallel data under the Creative
   Commons CC0 license ("no rights reserved").

## Citing this work

If you use this dataset as part of your developments, please cite it as follows:

```
@misc{PILAR,
  editor = {Galiano-Jiménez, Aarón and Sánchez-Martínez, Felipe and Pérez-Ortiz, Juan Antonio},
  title = {PILAR},
  url = {https://github.com/transducens/PILAR},
  year = {2024}
}
```

A `CITATION.cff` file is also included in this repository.
