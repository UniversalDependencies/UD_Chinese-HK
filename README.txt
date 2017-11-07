# Summary

The Chinese-HK UD treebank was manually annotated by Herman H. M. Leung and Tak-sum Wong at City University of Hong Kong, directly using the subtitles from two films shooted by students from the School of Creative Media. The data is in Tradiaitonal Chinese.

# Introduction

ORIGIN

#send_id = 1 to 100
Title: Missing days / 小時光 (first 100 sentences)
Source: https://www.youtube.com/watch?v=1qSMiw0vhzU
Duration: 30 minutes

#send_id = 101 to 209
Title: Tempo in Temple / 廟眾樂樂 (first 109 sentences)
Source: https://www.youtube.com/watch?v=8e8Lqd6grTE	
Duration: 16 minutes

DATA

Since there are only 1871 tokens, only the test set is provided.

BASIC STATISTICS

Tree count:  209
Word count:  1871
Token count: 1871
Dep. relations: 41 of which 10 language specific
POS tags: 17
Category=value feature pairs: 0

POS TAGGING

When determining the POS, one usually considers both the "morphological evidence", i.e., the linguistic form of the word, as well as the "distributional evidence", i.e., its syntactic use in the sentence. Usually, these two kinds of evidence should agree; in some cases, however, the POS of some word is tentatively alterned to fullfil the special purpose of the author.

Take an example in English, consider the word "pen" in the sentence "I pen a letter".  Morphological evidence suggests the word "pen" should be tagged as an noun (NN), reflecting its normal usage. Distributional evidence suggests it should be tagged as a verb, since this word is in a typical position of verb in a SVO language.

When these two kinds of evidence contradict one another, the morphological evidence prevails.

# Acknowledgments

This work was partially supported by a grant from the PROCORE-France/Hong Kong Joint Research Scheme sponsored by the Research Grants Council and the Consulate General of France in Hong Kong (Reference No.: F-CityU107/15 and N 35322RG); and by two Strategic Research Grants (Project No. 7004494 and No. 7004736) from City University of Hong Kong.

# References

When using this treebank, please cite at least one paper from the following references:
Tak-sum WONG, Kim GERDES, Herman LEUNG, and John LEE. "Quantitative Comparative Syntax on the Cantonese-Mandarin Parallel Dependency Treebank" Proceedings of the Fourth International Conference on Dependency Linguistics, pp. 266−275, Pisa, Italy, September 2017.
Herman LEUNG, Rafaël POIRET, Tak-sum WONG, Xinying ChEN, Kim GERDES and John LEE. "Developing Universal Dependencies for Mandarin Chinese" Proceedings of the 12th Workshop on Asian Language Resources, pp. 20−29, Osaka, Japan, December 2016.\

=== Machine-readable metadata =================================================
Documentation status: partial
Data source: manual
Data available since: UD v2.1
License: CC BY-SA 4.0
Includes text: yes
Genre: subtitle
Lemmas: not available
UPOS: manual native
XPOS: not available
Features: not available
Relations: manual native
Contributors: Gerdes, Kim; Lee, John; Leung, Herman; Wong, Tak-sum
contributing: elsewhere
Contact: tswong-c@my.cityu.edu.hk; jsylee@cityu.edu.hk
===============================================================================
