# ELTE Drama Corpus

The ELTE Drama Corpus is a continuously expanding database developed by the [_Department of Digital Humanities at Eötvös Loránd University_](https://elte-dh.hu/). Currently, the corpus contains 58 Hungarian dramas. Besides the texts, the corpus contains the annotation of structural units and the grammatical features of words in TEI XML format. The dramas of the corpus were written between the 16th and the first half of the 20th century.

## Numeric properties:

- number of dramas: 58
- number of authors: 28
- number of tokens: 893 300
- number of words: 683 918

## TEI Levels

The source of the corpus was the collection of the [_Hungarian Electronic Library_](http://mek.oszk.hu) and the collection of the [_Research Centre for the Humanities, Institute for Literary Studies_](https://szovegtar.iti.mta.hu).

1. The texts were converted into TEI XML format based on the [Text Encoding Initiative](https://tei-c.org/). The TEI XML files contain the annotation of structural units and the metadata of the dramas. The conversion was done manually (level1).
2. Then, we tokenized the dramas and annotated the grammatical features of words by using [e-magyar](https://github.com/nytud/emtsv), an NLP tool chain for Hungarian texts (level2).

# Elements and attributes

## Level1 -- annotation of structural units and adding metadata to texts

- `<castList>` : list of characters
- `<castItem>` : a single entry within `<castList>`, describing a character
- `<castGroup>` : group of several characters
- `<roleDesc>` : description of a character group
- `<role>` : name/description of the dramatic role of a character
- `<roleName>` : name of the character
- `<head>` : title
- `<div>` : act, scene
- `<stage>` : stage direction
- `<sp>` : individual speech of a character
- `@who` : character id
- `<speaker>` : name of the speaking character
- `<p>` : paragraph
- `<lg>` : stanza
- `<l>` : line

## Level2 -- tokenization and annotation of grammatical features of words

- `<s>` : sentence
- `<w>` : word
- `<pc> `: punctuation mark
- `@lemma` : lemma
- `@pos `: part of speech
- `@msd` : morphosyntactic features ([Universal Dependencies](https://universaldependencies.org/))

# Contributors:

- [Gábor Palkó](https://github.com/luhpeg)
- Botond Szemes
- [Tímea Borbála Bajzát](https://github.com/bajzattimi)
- [Zsófia Fellegi](https://github.com/zsofiafellegi)
- [Péter Horváth](https://github.com/horvathpeti99)
- [Balázs Indig](https://github.com/dlazesz)
- Dióssy Anna
- Hegedüs Fanni
- Pantyelejev Natali
- Sziráki Sarolta
- Vida Bence
- Kalmár Balázs

# License

The content of the repository is licensed under the [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) license.
All texts of the corpus are in the public domain.

