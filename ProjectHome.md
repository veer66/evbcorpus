# EVBCorpus is an English-Vietnamese Bilingual Corpus #
The EVBCopus contains over 10,000,000 words (10 million) from 15 bilingual books, 100 parallel English-Vietnamese / Vietnamese-English texts, 250 parallel law and ordinance texts, and 1,000 news articles. The composition, annotation, encoding and availability of the corpus are meant to facilitate developments of language technology and studies in bilingual terminology extraction, primarily for the English-Vietnamese-English language pair.

## English-Vietnamese Bilingual Corpus (EVBCorpus) ##
The building EVBCorpus process includes four main steps: (1) collect data and align bitext at the paragraph level; (2) align bitext at the sentence level, (3) linguistic analysis and tagging; (4) annotate and correct corpus with toolkits. As result, the EVBCopus was aligned at the sentence level; and a part of this corpus containing 1,000 news articles was aligned semi-automatically at the word level.

If you are interested in the corpus, please email to **hungnq(at)uit.edu.vn** to have more details.

Details of data sources of EVBCorpus:
| **Source** | **Document** | **Paragraph** | **Sentence** | **Word** |
|:-----------|:-------------|:--------------|:-------------|:---------|
| En-Vn Books | 15           | 13,980        | 80,323       | 1,375,492|
| En-Vn Fictions | 100          | 192,723       | 491,703      | 6,307,613 |
| En-Vn Laws | 250          | 86,803        | 98,102       | 1,912,055  |
| En-Vn News | 1,000        | 24,523        | 45,531       | 740,534  |
| **Total**  | **1,365**    | **318,029**   | **715,659**  | **10,431,592** |

## English-Vietnamese Word Alignment Corpus (EVWACorpus) ##
The EVWACorpus contains 1,000 news articles with 45,531 sentence pairs and 740,534 words which are aligned manually at the word level between English and Vietnamese sentence.
Details of the EVWACorpus:
|  | **English** | **Vietnamese** |
|:-|:------------|:---------------|
| Files | 1,000       | 1,000          |
| Sentences | 45,531      | 45,531         |
| Words | 740,534     | 832,441        |
| Sure Alignments | 447,906     | 447,906        |
| Possible Alignments | 560,215     | 560,215        |
| Words in Alignments | 654,060     | 768,031        |

## English-Vietnamese Chunker Corpus (EVChkCorpus) ##
The EVChkCorpus contains 1,000 news articles with 45,531 sentence pairs. It is tagged 5 raw chunker tags in both English and Vietnamese text.
Details of the EVChkCorpus:
|  | |**English** | **Vietnamese** |
|:-|:|:-----------|:---------------|
| NP | Noun Phrase | 212,500    | 209,824        |
| VP | Verb Phrase | 90,784     | 123,600        |
| PP | Preposition Phrase | 79,853     | 70,457         |
| ADVP | Adjective Phrase | 18,318     |                |
| ADJP | Adverb Phrase | 8,367      | 15,104         |

## English-Vietnamese Named Entities Corpus (EVNECorpus) ##
The EVNECorpus contains 1,000 news articles with 45,531 sentence pairs. It is tagged named entities in both English and Vietnamese text.
Details of the EVNECorpus:
|  | |**English** | **Vietnamese** |
|:-|:|:-----------|:---------------|
| LOC | Location | 10,115     | 10,006         |
| PER | Person | 6,869      | 6,741          |
| ORG | Oganization | 7,837      | 7,549          |
| PCT | Percentage | 1,107      | 921            |
| MON | Money | 898        | 823            |
| TIM | Time | 4,244      | 4,100          |
| **Total** |  | 35,879     | 34,732         |

#### The canonical publication for the EVBCorpus is: ####
Quoc Hung Ngo, Werner Winiwarter, and Bartholomaus Wloka, (2013). **"EVBCorpus - A Multi-Layer English-Vietnamese Bilingual Corpus for Studying Tasks in Comparative Linguistics"**, In Proceedings of the 11th Workshop on Asian Language Resources (11th ALR within the IJCNLP2013), pp. 1-9. Asian Federation of Natural Language Processing, 2013.

Quoc-Hung Ngo, Werner Winiwarter, (2012). **"Building an English-Vietnamese Bilingual Corpus for Machine Translation"**, International Conference on Asian Language Processing 2012 (IALP 2012), pp. 157-160. IEEE Computer Society, 2012.

#### The canonical publication for the EVNECorpus is: ####
Quoc Hung Ngo, Dinh Dien, and Werner Winiwarter, (2014). **"Building English-Vietnamese Named Entity Corpus with Aligned Bilingual News Articles"**, The 5th Workshop on South and Southeast Asian Natural Languages Processing (5th SSANLP within the COLING2014). Association for Computational Linguistics, 2014 (accepted).

#### The canonical publication for the annotation tool is: ####
Quoc-Hung Ngo, Werner Winiwarter (2012). **"A Visualizing Annotation Tool for Semi-Automatically Building a Bilingual Corpus"**,  In Proceedings of the 5th Workshop on Building and Using Comparable Corpora, LREC2012 Workshop, pages 67-74. Association for Computational Linguistics, 2012.

#### The canonical publication for the GetWebContent tool is: ####
Quoc-Hung Ngo, Dinh Dien, Werner Winiwarter, (2012). **"Automatic Searching for English-Vietnamese Documents on the Internet"**, The 3rd Workshop on South and Southeast Asian Natural Languages Processing (3rd SSANLP within the COLING2012), pp. 211-220. Association for Computational Linguistics, 2012.

**(C,R) Quoc-Hung Ngo, 2013**