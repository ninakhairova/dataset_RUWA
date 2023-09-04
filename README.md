# RUWA dataset
RUWA (Russian-Ukraine WAr) dataset includes more than 16,500 news articles from several media outlets in Ukraine, Russia, European, Asia, and the USA covering the nine  Russian-Ukraine war events from February 2022 to September 2022.  Table 1 and table 2 show the article distributions by selected news outlets and events. 
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
|Azovstal | | 1817|
| Begining |  |6490|
| Bucha |  |1431|
| Nuclear |Nuclear Plant |3385|
| Prisoners | |583|
| Railway| |1486|
|Sinking|Mosdva Sinking   |184|
|Supermarket|   |441|
|Theatre|Mariupol Theatre|761|

## Dataset columns
| Name | Discription |
| --------- | --------- |
| src |  |
| desc |   |
| title |   |
| ref |   |
| Date | publication date |
| Site| Site of an article |
|Event|Event name     |
|KW|   key words|
|Content_cleared|Content after preprocessing|

## Copyright
To not violate the copyright of the articles, we do not share them in their original format, but we include a link to the original article.

## Preprocessing
The preprocessing of the articles includes:
- removing stop words by NLTK;
- removing stop words by SpaCy";
- removing all kinds of sentences representation; 
- removing all symbols except the English alphabet, digits, and hyphens.
- removing all words shorter than 3 letters;
- conversion to lower case;
- stemming all words;
- transferring all date representation into ISO-format


## License
CC BY-NC-SA 4.00


 
