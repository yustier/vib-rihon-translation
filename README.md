# vib-rihon-translation
Translation of [Vib-Rihon](https://archive.org/details/vib-rihon-scans)  
[ビブリホン](https://archive.org/details/vib-rihon-scans)の翻訳

Translation is mostly done through DeepL, tweaked by hand

## Format
YAML file contains...
- `name`: The name of the book
- `description`: The description of the book
- `pages[n].title`: Each page's title (if there isn't, assigned unique ID)
- `pages[n].contents[m]`: Each page's content (each list element roughly corresponds to a paragraph)
- Sometimes contain comments about the translation or the content

## Editions
|Language                |File                                      |Version   |Remarks |
|:-----------------------|:-----------------------------------------|:---------|:-------|
|Japanese                |[vibrihon.ja_JP.yaml](vibrihon.ja_JP.yaml)|2023-08-14|Original|
|English                 |[vibrihon.en_GB.yaml](vibrihon.en_GB.yaml)|2023-08-14|        |
