# Hachidaishu Part of Speech dataset
## Hilofumi Yamamoto, Ph.D. (Tokyo Institute of Technology)

### Data offset

Example: \# 1 Kokinshu
```
10001 年/名/とし の/格助/の 内/名/うち に/格助/に 春/名/はる は/係助/は き/カ変-用:来:く/き に/完-用:ぬ:ぬ/に けり/過-終:けり:けり/けり 一とせ/名/ひととせ を/＊助/を こそ/名/こぞ と/格助/と や/係助/や いは/ハ四-未:言ふ:いふ/いは ん/推-終体:む:む/む ことし/名/ことし と/格助/と や/係助/や いは/ハ四-未:言ふ:いふ/いは ん/推-終体:む:む/む 
``` 
### A line a poem: tokens are separated by spaces; and a token consists of pos elements separated by slashes.

- 1st column "10001" contains two elements: the first digit is an anthology ID and the rest is a poem ID;
  - the anthology ID: 1..Kokinshu, 2..Gosenshu, 3..Shuishu, 4..Goshuishu, 5..Kin'yoshu, 6..Shikashu, 7..Senzaishu, and 8..Shinkokinshu.
  - the poem ID is the same as in the database "Nijuichidaishu."
- 2nd column and the followings are the information of each token.
  - noun, particle, such as tokens not having conjugations: text/POS/reading.
  - verb, adjectives, such as tokens having conjugations: text/POS:lemma-kanji:lemma-reading/reading.

## Reference
1. Yamamoto, Hilofumi (2007) 
  POS tagger for Classical Japanese Poems 
  The Study of Japanese Linguistics 
  Vol. 3, No. 3, pp. 33-39
  The Society of Japanese Linguistics 

1. Yamamoto, Hilofumi (2007) 
  Thesaurus of Japanese Poetic Vocabulary Based on the Semantic Classifications Chart,
  The 13th Annual Symposium for Database of the Humanities, 
  1-8, 
  The Association for Database of the Humanities,
  Osaka.

1. Yamamoto, Hilofumi (2009) 
  Thesaurus for the Hachidaishu (ca. 905-1205) with the classification codes based on semantic principles,
  Nihongo no Kenkyu / Studies in the Japanese Language,
  46-52,
  Society for Japanese Linguistics,
  5, 1, 
  ISSN1349-5119.

1. Yamamoto, Hilofumi (2021)
  Hachidaishu vocabulary dataset,
  Zenodo,
  version 1.0.1,
  <https://doi.org/10.5281/zenodo.4744170>

1. Yamazaki, Makoto and Kashino, Wakako and Uchiyama, Kiyoko and Sunaoka, Kazuko, and Tajima, Ikudo and Yamamoto, Hilofumi and Han, Yoo-Sik and Seol, Geun-Su (2014)
  Bunruigoihyo zouhokaiteiban" e no anotashion: kihongi no kettei (in Japanese),
  Keiryo Kokugo gakkai dai 58 kai taikai yokoshu,
  pp. 7--12.
  
1. [国文学研究資料館二十一代集](http://kotenseki.nijl.ac.jp/biblio/200007092)

1. [二十一代集 DOI: 10.20730/200007092](http://codh.rois.ac.jp/pmjt/book/200007092/): ROIS-DS人文学オープンデータ共同利用センター 新日本古典籍総合データベース（200007093）



<!--
@dataset{yamamoto_hilofumi_2021_4735848,
  author       = {Yamamoto, Hilofumi},
  title        = {Hachidaishu vocabulary dataset},
  month        = may,
  year         = 2021,
  publisher    = {Zenodo},
  version      = {1.0.0},
  doi          = {10.5281/zenodo.4735848},
  url          = {https://doi.org/10.5281/zenodo.4735848}
}

@Article{yamagen2009ae,
  author = 	 {Yamamoto, Hilofumi},
  title = 	 {Thesaurus for the Hachidaishu (ca.\,905--1205) with the classification codes based on semantic principles},
  journal =      {Nihongo no Kenkyu / {S}tudies in the Japanese Language},
  pages = 	 {46--52},
  OPTpublisher = {Society for Japanese Linguistics},
  year = 	 {2009},
  volume = 	 {5},
  number = 	 {1},
  OPTedition = 	 {ISSN1349-5119},
  OPTmonth = 	 {},
  OPTnote = 	 {},
  OPTannote = 	 {},
  OPTlocation =  {},
  OPTmemo = 	 {}
}

@InCollection{yamagen2007de,
  author = 	 {Yamamoto, Hilofumi},
  title = 	 {Thesaurus of Japanese Poetic Vocabulary Based on the Semantic
      Classifications Chart},
  year = 	 {2007},
  booktitle = 	 {The 13th Annual Symposium for Database of the Humanities}, 
  pages = 	 {1--8},
  publisher =    {The Association for Database of the Humanities},
  address = 	 {Osaka},
  OPTedition = 	 {},
  OPTmonth = 	 {2007.12},
  OPTmemo = 	 {}
}
-->
