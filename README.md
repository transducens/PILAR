# Pan-Iberian Language Archival Resource (PILAR)

This repository contains the PILAR corpora, produced as part of the R+D+i project [Lightweight neural translation technologies for low-resource languages (LiLowLa)](https://transducens.dlsi.ua.es/lilowla/) (PID2021-127999NB-I00) funded by the Spanish Ministry
of Science and Innovation (MCIN), the Spanish Research Agency (AEI/10.13039/501100011033) and the European Regional Development Fund A way to make Europe. The project LiLowLa has been carried out by researchers of the Transducens research group at Universitat d'Alacant, Spain.

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

## FLORES+ 

The file [FLORES+.zip](https://github.com/transducens/PILAR/blob/main/FLORES%2B.zip) file contains translations of the dev and devtest sets of [FLORES+](https://github.com/openlanguagedata/flores) into Aragonese, Aranese, and Asturian. Although FLORES+ already includes an Asturian version, the version published in this repository has been revised. The file also contains the corresponding original Spanish side of FLORES+. Both dev and devtests sentences have been reviewed by the respective language academies to ensure that they follow the current standard orthographic conventions. We thank the support and help in the translation of the FLORES+ sentences from Academia Aragonesa de la Lengua (Instituto de l’Aragonés), Academia de la Llingua Asturiana and Institut d’Estudis Aranesi.

As in the original FLORES+ repository, the files are provided compressed (password: `multilingual machine translation`) to prevent them from being automatically crawled and added to training datasets.

It is important to note that the method used to create the FLORES+ Asturian dataset differs from the one used for Aragonese and Aranese. The Asturian sentences were originally obtained by Meta via professional translation from English and then we asked the academia to revise it, whereas the Aragonese and Aranese sentences were first machine translated from the Spanish sentences using Apertium and then manually post-edited by specialists proficient in these languages and finally revised by the academias. The post-editions were supervised by the R+D+i project PID2021-124663OB-I00 ("TAN-IBE: Neural Machine Translation for the Romance languages of the Iberian Peninsula") developed at Universitat Oberta de Catalunya, Spain.

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
