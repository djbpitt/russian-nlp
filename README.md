# russian-nlp

## About

Playground for Russian NLP packages.

Tested under Python 3.9.9 Anaconda miniforge Apple arm (M1)

## MyStem

Install <https://pypi.org/project/pymystem3/>. Installing the latest
version, as described on that page, errors out, but the current stable
version works as advertised. 

**Notes:**

1. It is not necessary to install MyStem separately; the wrapper package fetches it. If desired, though, a command-line executable for *MyStem* can be downloading from 
<https://download.cdn.yandex.net/mystem/mystem-3.1-macosx.tar.gz>. Untar
with `tar -xvf mystem-3.1-macosx.tar.gz`, which unpacks an executable
called `mystem`. Remove quarantine with
`xattr -d com.apple.quarantine mystem` and run from the command
line.
1. Downloading the command-line executable failed on 2022-03-12 from the link on the main MyStem page (<https://yandex.ru/dev/mystem/>), but worked from the direct link above.
1. The executable is for Apple Intel, but works under M1.

## spaCy

There are three Russian models (small, medium, large), all trained on
news data. Install spaCy (<https://spacy.io/>) and then the Russian
models (<https://spacy.io/models/ru>).

See also spaCy + Stanza (formerly StanfordNLP) <https://github.com/explosion/spacy-stanza>, a wrapper for using Stanford models (<https://stanfordnlp.github.io/stanfordnlp/>) from inside spaCy.

## Slovnet

Slovnet (<https://github.com/natasha/slovnet>) is part of the Natasha 
project (<https://github.com/natasha>).

----

## Links to other resources

* Red Hen Lab Russian NLP <https://www.redhenlab.org/home/the-cognitive-core-research-topics-in-red-hen/the-barnyard/russian-nlp>
* Stanford RussianNLP for literature and history <https://russiannlp.sites.stanford.edu/resources>
* Iuliia Volkova’s Russian NLP links <https://github.com/xnuinside/russian-language-nlp>
* Tatiana Shavrina’s #xhaustive list of open-source corpora for Russian <https://tatianashavrina.github.io/2018/08/30/datasets/>

