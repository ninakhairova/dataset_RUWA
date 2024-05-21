# RUWA dataset
RUWA (Russian-Ukraine WAr) dataset includes more than 16,500 links of news articles from several media outlets in Ukraine, Russia, European, Asia, and the USA covering the nine  Russian-Ukraine war events from February 2022 to September 2022.  Table 1 and table 2 show the article distributions by selected news outlets and events. 
##### Distribution dataset articles by outlets

| Sources | Articles |
| --------- | --------- |
| AlJazeera.com |600 |
| BBC.co.uk | 550 |
| Censor.net | 5094 |
| En.News-front.info | 94 |
| MsNBC.com | 506 |
| Reuter.com| 1993 |
|RT.com|940    |
|Ukinform.net|   6749|
|Tass.com|34|

##### Distribution dataset articles by events
| Event | Description |Articles|
| ------ | ------ |------ |
|Azovstal |Russia says Azovstal siege is over, in full control of Mariupol | 1817|
| Begining |NATO officials say Russian attack of Ukraine has begun  |6490|
| Bucha |Ukraine says In a Kyiv Suburb,'They Shot Everyone They Saw.'  |1431|
| Nuclear |Ukraine says  Ukraine Zaporizhzhia nuclear plant under Russian orders |3385|
| Prisoners | |583|
| Railway|Ukraine says dozens killed in Russian rocket attack on Kramatorsk train station |1486|
|Sinking|Russia's top warship explodes, on fire in the Black Sea  |184|
|Supermarket|   |441|
|Theatre|Ukraine says Russia Just Bombed a Theater in Ukraine Where Hundreds Were Sheltering|761|

## Dataset columns
| Name | Description |
| --------- | --------- |
| src | Link to a source |
| desc | Subheading of an article  |
| title |Title of an article   |
| ref | Information related to an article |
| Date | Date of the publication |
| Site| Site of a news outlet|
|Event|Event name     |
|KW|   Key words|

## Copyright
To not violate the copyright of the articles, we do not share them in their original format, but we include a link to the original article.

## Preprocessing
The preprocessing of the articles includes:
- removing stop words by NLTK;
- removing stop words by SpaCy";
- removing all kinds of sentences representation; 
- removing all symbols except the English alphabet, digits, and hyphens.
- removing all words shorter than 3 letters;
- conversion to lowercase;
- stemming all words;
- transferring all date representation into ISO-format

## Attribution and Usage
If you use this dataset in your work, please cite the following article:
[N Khairova, B Ivasiuk, F LO SCUDO, C Comito, A Galassi. "A First Attempt to Detect Misinformation in Russia-Ukraine War News through Text Similarity"// Proceedings of the 4th Conference on Language, Data and Knowledge (LDK), 559-564](https://www.researchgate.net/profile/Andrea-Galassi/publication/375525802_A_First_Attempt_to_Detect_Misinformation_in_Russia-Ukraine_War_News_through_Text_Similarity/links/654df4b0b86a1d521bc8b006/A-First-Attempt-to-Detect-Misinformation-in-Russia-Ukraine-War-News-through-Text-Similarity.pdf) 

BibTeX citation:

@article{ruwa2023,
  author = {Khairova, Nina and Ivasiuk, Bogdan and Lo Scudo, Fabrizio and Comito, Carmela and Galassi, Andrea},
  title = {A First Attempt to Detect Misinformation in Russia-Ukraine War News through Text Similarity},
  journal = {Proceedings of the 4th Conference on Language, Data and Knowledge (LDK)},
  year = {2023},
  pages = {559-564}
}

## License
CC BY-NC-SA 4.00


 
