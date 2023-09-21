# EDH Ctagged Inscriptions

## What is this dataset?
This dataset includes the XML files for mainly Latin inscriptions. All inscription data is based on [the Epigraphic Database Heidelberg](https://edh.ub.uni-heidelberg.de/), one of the most well-known databases in the Roman studies, by downloading all the XML files it provided in Creative Commons Licence BY-SA. 
However, we made slight additional editings to that in order to enable more sophisticated and granular use of epigraphic text data. The modifications are as follows:

- put \<c\> to each single characters in the text
- use \<sourceDoc\> as a text container instead of original \<body\>
- replace \<lb\> empty tag with \<line\>

As modifications are all processed automatically using Python, there must be some small problems in the files (and maybe huge ones too). 

## What the advantage?
As each character in the texts is now marked with \<c\> and given xml:id, we can now refer it as a web data resource with respective URI. 