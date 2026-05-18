# Programming Project #2 - Booklet Page Order

## Project Templates
Our programming projects are programming language agnostic, so feel free to use any of these stylesheets of the langauge of your choice: 
- [C++ Stylesheet](https://gist.github.com/profe/20e3d4c30c7eb8db6f702a29b40b1c8d)
- [Java Stylesheet](https://gist.github.com/profe/32aeaa629e62815043c91733399276e7)
- [Python Stylesheet](https://gist.github.com/profe/e236ebead2ed0c7bf1a07477676399e4)

## Project Instructions

The reprographic center at Swamp County High School is a sorry collection of mimeographs and aging photocopiers. Just recently, it acquired a new laser printer that can print duplex (on both sides of the paper) and 2-up (two half-size pages on one side of a sheet of paper). To show off the new capabilities, the school wants to print this year’s graduation program as a booklet rather than a bunch of 8.5 by 11 inch single-sided papers stapled together. A booklet is stack of 8.5 by 11 inch papers folded in half along the 5.5 inch midline, then stapled along the fold to make a simple
spine.

Mr. Hack, the journalism teacher and a capable editor, was unable to determine the page print order necessary to produce a booklet from a document with sequentially ordered pages. He turned to your team, the webmasters for the school’s underground website, to produce a program to reorder the pages for proper printing. Given the number of sequential pages in a document, produce the required number of sheets and proper page reordering for proper printing as a 2-up duplex booklet.

Input to your program will be a list of document sizes (in total pages), one per line, terminated by end-of-file. Each page count will appear as a positive integer beginning in the first column.

Output is one (potentially fairly long) line for each input line, describing the number of sheets needed and the necessary page reordering. For each document size, print the number of sheets of paper required in a booklet, followed by a colon, then the page numbers to print on each separate sheet of paper. For each sheet, print a space followed by four comma-separated page numbers, where a page number of zero indicates a blank page. The laser printer prints pages in A,B,C,D order as indicated on the diagram at the end of this problem (see figure 1). Order the sheets such that laying the sheets down with the first two pages (6,3 in the seven-page sample) showing, then the next sheet’s pages showing (0,1 in the seven-page sample) produce a stack of papers with page 1 on the facing (right hand) page, ready
to be stapled from the top.

A recent donation of very lightweight paper combined with a heavy duty stapler has made it possible to staple up to 50 sheets of paper together.


## Output Format

Sample Input:
```
7
5
2
```

Sample Output:
```
2: 6,3,4,5 0,1,2,7
2: 0,3,4,5 0,1,2,0
1: 0,1,2,0
```

## Submission Instructions
**Submit** "ready for grading" along with which language you used (C++, Java, Python) in the text box on Canvas when you are done with the project. Copy paste your code in the text box or upload a pdf.
