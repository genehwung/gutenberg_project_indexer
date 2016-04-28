## Synopsis

This is a toy project, it indexes Gutenberg project using the standard tf-idf, and query using cosine-distance. The indexing files are less than 500 MBs compressed, 3GB uncompressed. This is a toy project of me for learning tf-idf, not production code in any level.

## Example
Run 'query_main.py' to query:

![alt tag](https://raw.githubusercontent.com/genehwung/gutenberg_indexer/capture.png)


## Motivation

I cam across the Gutenberg-tar project where all the files are in txt format, making it very easy to process. The size is adequately big for an information retrieval project. 

## Installation

If you want to try indexing yourself, download the text file from http://www.gutenberg-tar.com/. Extract them at any folder and assign 'target_path' (in indexer.py) accordingly.


