# Background
[Malcolm Fraser](https://en.wikipedia.org/wiki/Malcolm_Fraser) was an Australian federal politician for over 30 years including a term as Prime Minister.

His electorate, [Wannon, is over 1000km from Canberra](https://en.wikipedia.org/wiki/Division_of_Wannon#/media/File:Division_of_Wannon_2019.png), and at the time travel between the two was time consuming and difficult.

To stay in contact with his electorate, he regularly pre-recorded radio spots to tape and those tapes would be transported to the two radio stations in his electorate. The text from those talks was kept in an archive. [The University of Melbourne have digitised the collection](https://archives.unimelb.edu.au/explore/collections/malcolmfraser/about) into PDFs, and run OCR on them to generate text files.

The result is a rich corpus - a politician talking to the issues of the day over thiry years as his career progresses from local member to Government Minister to Prime Minister.

This is a perfect introductory data set for an introduction to using Python for liguistic analysis.

# Preparation

We use [spaCy](https://spacy.io/usage) for this project. It's installation will depend on your computer. For Ubuntu users, this process will work:

```
$ python3 -m venv ~/.venvs/spacy
$ source ~/.venvs/spacy/bin/activate
$ pip install spacy jupyter --user
```

You can then launch a jupyter instance from within the directory you downloaded this repository into.

```
$ jupyter notebook
```
