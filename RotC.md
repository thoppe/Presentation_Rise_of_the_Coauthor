{"theme":"beige.css"}

# Rise of
# the Coauthor

*[Travis Hoppe](http://thoppe.github.io/)*, Dan Appella

[(deck source)](https://github.com/thoppe/Rise-of-the-Coauthor)

====*

Motivation:
Author count histogram for a single issue of JBC
!(img/minton_coauthor.jpg)

====

### Is science really changing?

====+
<br>
# _YES!_

NIH budgets, PDB submissions,  number of postdoctoral/doctoral students, number of international collaborations, ...

====*
## NIH Funding

!(img/NIH_funding1.png) <<height:280px>>
!(img/NIH_funding2.png) <<height:280px>>

[Source: (CAP) Erosion of Funding for the NIH ...](http://www.americanprogress.org/issues/economy/report/2014/03/25/86369/erosion-of-funding-for-the-national-institutes-of-health-threatens-u-s-leadership-in-biomedical-research/)
 
====*
## Growth of Data
Submissions to PDB

!(img/EM_pdb.jpg) <<height:250px>>
!(img/NMR_pdb.jpg) <<height:250px>>
[Electron Microscopy](http://www.nature.com/nsmb/journal/v19/n12/full/nsmb.2426.html?WT.ec_id=NSMB-201212), [NMR](http://www.wwpdb.org/news/news_2013.html)

====*

## Growth of Temporaries
!(img/postdoc_growth.jpg)  <<height:400px>>

[Source: (NIH) Office of Extramural Research](http://www.americanprogress.org/issues/economy/report/2014/03/25/86369/erosion-of-funding-for-the-national-institutes-of-health-threatens-u-s-leadership-in-biomedical-research)


====*

## International groups
!(img/international_trend.gif) <<height:600px>>

====

## Editorial

Purpose of this talk is to examine the trends of 

*journal article authorship*

and any other interesting facts from the front-end of a journal.

====*

## Methods

Journal studied: Science, Nature, Cell, JCI, PNAS, JACS, JBC.

For every journal, every table of contents was downloaded. 
This gives titles and authorship information for every paper.

Filtered for editorials, corrections, errata, book reviews, ...

====*

## Limitations

Why not examine the _abstracts_, or the _articles_ themselves?

+ Legal issues (c.f. [Aaron Swartz](http://en.wikipedia.org/wiki/United_States_v._Aaron_Swartz))
+ Time/complexity issues
+ Publicly available data


====

## Consortia

LARGE project collaborations

Removed from study

Examples:

Genome (link)
Mars Rover (link)
Etc (link)

====* !(img/seq/total1.png 70% fade)
====* !(img/seq/total2.png 70% fade)
====* !(img/seq/total3.png 70% fade)
====* !(img/seq/total4.png 70% fade)
====* !(img/seq/total5.png 70% fade)

====*
## Extrapolate?
!(img/ProjectionTable.png)

====*
## Correlated to growth?
!(img/growth_plots.png) <<height:600px>>

====*

## Single Authorship

_a prori_ not the same trend as mean authorship...

====* !(img/seq/single1.png 70% fade)
====* !(img/seq/single2.png 70% fade)

====
## Lexicographical analysis

Look for _significant_ keywords in the titles

+ Remove *stop words*:

e.g. [the,first,has]

+ Apply *stemming*, *lemmatization*:

(acids, acidic) $\rightarrow$ acid

Identify a canonical representative set for related words

====*

NATURE 1935
    spectrum        4.24
    structure       3.15
    neutron         3.01
    radioactivity   2.74

NATURE 1951
    acid            7.32
    chromatography  2.76
    structure       2.68
    cell            2.20

NATURE 2013
    cell            12.59
    structure       5.87
    protein         5.13
    human           5.01

====

## Title length

Longest title:

Shortest title:


====*

## Verbosity Saturates
!(img/title_length.png) <<height:600px>>

====
# Reasons?

+ More money == More science?
+ New science requires international collaborations, e.g. all the low hanging fruit is gone
+ White bull effect?
+ Diluted second authors?

Is this a bad thing? What is lost?









