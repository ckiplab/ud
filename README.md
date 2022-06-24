# Sinica Universal Dependencies Treebank


# Introduction

  The recent surge of interest in using a unified tagset and annotation guideline for treebanks of many languages has led to the speedy growing of the Universal Dependencies (UD) Project (Nivre et al., 2016). The project aims to facilitate the development of parsing technologies, enabling the use of techniques such as cross-lingual transfer. The UD version 2.9 consists of 217 treebanks in 122 languages with contributions from 477 researchers around the world. Apart from developing treebanks by manual parsing or manual correction of automatic parsing, a UD treebank can also be automatically converted from an existing treebank, which uses a different annotation scheme (Arnardóttir et al., 2020). The present work is to convert the Sinica Treebank, in which the thematic relation between a predicate and an argument is marked in addition to grammatical category, to a UD approach treebank. There are already 5 Mandarin Chinese UD corpora on the UD website. However, compared to other major languages, the data size for Chinese is quite small. The Sinica TreeBank has been a major Traditional Chinese Treebank developed in Taiwan and has made contribution to many NLP tasks. We hope to enlarge the usage of the Sinica treebank by converting it to the UD format and also gain some insights along with the conversion to share with the community.
    
## Structure

This directory contains a corpus of sentences annotated using Universal Dependencies annotation.

This corpus is compatible with the CoNLL-U format defined for Universal Dependencies. See:

   http://universaldependencies.github.io/docs/format.html
   
The dependency taxonomy can be found on the Universal Dependencies web site:

   http://www.universaldependencies.org


The Sinica UD Treebank in the CoNLL-U format is：

"Example: The scholar took the money with trembling hands."

| ID | WORD| -- | POS* | POS | -- | UD_POS | HEAD |--|--|UD_DEP|--|
|---|---|---|---|---|---|---|---|---|---|---|---|
| 1 | 書生 | _ | N | Nab | _ | NOUN | 6 |  | _ | nsubj | _ |
| 2 | 用 | _ | P | P39 | _ | ADP | 5 |  | _ | case | _ |
| 3 | 顫抖 | _ | V | VA2 | _ | VERB | 5 |  | _ | acl | _ |
| 4 | 的 | _ | DE | DE | _ | PART | 3 |  | _ | mark_relcl | _ |
| 5 | 手 | _ | N | Nab | _ | NOUN | 6 |  | _ | obl | _ |
| 6 | 接過 | _ | V | VC2 | _ | VERB | 0 |  | _ | root | _ |
| 7 | 銀子 | _ | N | Nab | _ | NOUN | 6 |  | _ | obj | _ |

## Deviations from UD

**Version 0.1 of the Sinica UD treebank**
- Please refer to our paper for detailed instructions.

# Changelog

**2022-06-23 v0.1**

- LICENSE version [CC-BY-NC-SA 4.0 License](http://creativecommons.org/licenses/by-nc-sa/4.0/)

# Citations
You are encouraged to cite this paper if you use the Sinica Universal Dependencies Treebank:

## APA:

Yu-Ming Hsieh, Yueh-Yin Shih, and Wei-Yun Ma. 2022. Converting the Sinica Treebank of Mandarin Chinese to Universal Dependencies. In Proceedings of the Sixteenth Linguistic Annotation Workshop (LAW-XVI) co-located with LREC, June 24. 2022. Marseille, France.

## BibTex

    @inproceedings{hsieh-etal-2022-sud,
        title = {Converting the Sinica Treebank of Mandarin Chinese to Universal Dependencies},
        author = {Hsieh, Yu-Ming and
          Shih, Yueh-Yin and
          Ma, Wei-Yun},
        booktitle = {Proceedings of the Sixteenth Linguistic Annotation Workshop (LAW-XVI) co-located with LREC-2022},
        year = {2022},
        abstract = {This paper describes the conversion of the Sinica Treebank, one of the major Mandarin Chinese treebanks, to Universal Dependencies. The conversion is rule-based and the process involves POS tag mapping, head adjusting in line with the UD scheme and the dependency conversion. Linguistic insights into Mandarin Chinese alongwith the conversion are also discussed. The resulting corpus is the UD Chinese Sinica Treebank which contains more than fifty thousand tree structures according to the UD scheme.},
    }


# Contributers
* <b>Yueh-Yin Shih</b> at [CKIP](https://ckip.iis.sinica.edu.tw).
* [Wei-Yun Ma](https://www.iis.sinica.edu.tw/pages/ma/) at [CKIP](https://ckip.iis.sinica.edu.tw).
* [Yu-Ming Hsieh](https://www.rchss.sinica.edu.tw/people/bio.php?PID=453).

# License/Copyright

Sinica Universal Dependencies Treebank annotations @ 2022 by CKIP. All Rights Reserved.

The annotations and database rights of the Sinica Universal Dependencies Treebank are licensed under a Creative Commons Attribution-ShareAlike 4.0 International License. You should have received a copy of the license along with this work. If not, see <http://creativecommons.org/licenses/by-sa/4.0/>.

[![CC BY-NC-SA 4.0](https://camo.githubusercontent.com/6887feb0136db5156c4f4146e3dd2681d06d9c75/68747470733a2f2f692e6372656174697665636f6d6d6f6e732e6f72672f6c2f62792d6e632d73612f342e302f38387833312e706e67)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

For academic use only, please do not use for profit. If you need to use it for commercial purposes, please contact us for further assistance.

Copyright (c) 2022 [CKIP Lab](https://ckip.iis.sinica.edu.tw) under the [CC-BY-NC-SA 4.0 License](http://creativecommons.org/licenses/by-nc-sa/4.0/). All rights reserved.


