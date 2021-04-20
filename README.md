# Generating the publication list
When you update the list of publications you need to first generate an HTML representaion of the pubs.bib file, then paste it into the pubs.html file.

The HTML is generated using bibtex2html:
```[wseymour@nuttyMac haisep]$ bibtex2html -nokeys -nobibsource -nodoc -noheader -nf url PDF -o pubs-intermediate pubs.bib```
