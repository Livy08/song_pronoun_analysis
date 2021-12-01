# song_pronoun_analysis

Author: Olivia Zhang

Contact: oliviazhang@college.harvard.edu

This repository contains all progress (code and data) of my song lyric and language usage patterns analysis project, started as an independent class project for Harvard PSY 15, Social Psychology, Fall 2021. Feel free to refer to the project report document, titled "final-project-report-Olivia-Zhang".

General Notes: All song lyrics were taken manually from https://www.azlyrics.com/ word-for-word. Code files are written in Python and were run in Jupyter Notebook via Anaconda for Mac OS.

Content Descriptions:
This repository contains three Jupyter Notebook run files, four .csv format data files, and six folders of song lyric text files, as well as a project report document. 

- There is one .ipynb Jupyter Notebook file per dataset, annotated accordingly.
- Data exports from the run files for analysis are included in .csv format.
- The folder "songs-raw" contains the "exclusive" song dataset of full, unprocessed song lyrics, i.e. songs where the song artist (Taylor Swift) had exactly one co-writer.
- The folder "songs-raw-extended" contains the "extended" dataset of full, unprocessed song lyrics, i.e. in addition to the songs in the "exclusive" dataset there are also songs where the song artist (Taylor Swift) had exactly one co-writer, though excluding instances when the co-writer is featured or duets on the song. 
- The folder "songs-CUT-raw-extended" contains the same songs as in "songs-raw-extended" except each song's lyrics have been cut: Each song was cut to include lyrics up to but not including the second verse to decrease potential confounding factors from pop music structures, such as vocal repetition or instrumentaion for catchiness, sonic effect, etc.
  * if a song opened with the chorus, this chorus was removed
  * if a song had a lyrical intro not the same as the chorus, this was kept
  * if a song intro included lyrics as vocal percussion as instrumentation, e.g. "oh oh oh", "my my my", or "hm mm", these were cut, as their purpose is mainly music structure-driven rather than language communication-driven 
