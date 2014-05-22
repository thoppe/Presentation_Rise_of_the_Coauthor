{"theme":"beige.css"}

# Rise of
# the Coauthor
<div class="footnote">_(a very meta journal-club)_</div>


*[Travis Hoppe](http://thoppe.github.io/)*, Dan Appella
[(deck source)](https://github.com/thoppe/Rise-of-the-Coauthor)

====*

Motivation:
Author count histogram for a single issue of JBC
!(img/minton_coauthor.jpg)

====*

## Editorial

Purpose of this talk is to examine the trends of 

*journal article authorship*

and other interesting facts from the front-end of a journal.

====*

## Methods

*JCI* (J. Clinical Investigations), *PNAS* (Proc. National Academy of Sciences), *JACS* (J. American Chemical Society), *JBC* (J .Biological Chemistry), *Science*, *Nature*, *Cell*.

For each journal, every table of contents was downloaded.
This gives titles and authorship information for every paper.

Filtered for editorials, corrections, errata, book reviews, ...
Approximately 2.4K TOC, 655K papers for older journals.

====*

## Limitations

Why not examine the _abstracts_, or the _articles_ themselves?

====+
<br>

+ Time/complexity issues

====+

+ Legal issues (c.f. [Aaron Swartz](http://en.wikipedia.org/wiki/United_States_v._Aaron_Swartz))

====+

+ Publicly available data


====

## Consortia

LARGE project collaborations

Removed from study

Examples:

Genome (link)
Mars Rover (link)
Etc (link)

====

# Authorship distribution

In most cases the _distribution_ of authorship follows a Poisson,
hence the mean is approximately the variance.

====* !(img/seq/total1.png 70% fade)
====* !(img/seq/total2.png 70% fade)
====* !(img/seq/total3.png 70% fade)
====* !(img/seq/total4.png 70% fade)
====* !(img/seq/total5.png 70% fade)

====*
## Extrapolate?
Assume linear trend from last 15 years

!(img/ProjectionTable.png)

====

## Correlated to growth?

### Bibliographics, Thomson-Reuters

+ Impact factor 
+ Article influence
+ Eigenfactor (similar to Google's page-rank)
+ Total citations


====*
!(img/growth_plots.png)

====*

## Single Authorship

_a priori_ not the same trend as mean authorship...

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

## Top keywords in an era
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

====* !(img/seq/title1.png 70% fade)
====* !(img/seq/title2.png 70% fade)
====* !(img/seq/title3.png 70% fade)

====

### Is science really changing?

====+
<br>
# _YES!_

NIH budgets, PDB submissions,  number of postdoctoral/doctoral students, number of international collaborations, ...

====*
## NIH Funding
!(img/NIH_funding1.png) <<height:450px>>

[Source: (CAP) Erosion of Funding for the NIH ...](http://www.americanprogress.org/issues/economy/report/2014/03/25/86369/erosion-of-funding-for-the-national-institutes-of-health-threatens-u-s-leadership-in-biomedical-research/)
 
====*
### Growth of Data
!(img/NCBI_usage.png)[www.nlm.nih.gov/about/2015CJ.html] <<height:250px>>
!(img/Hard_drive_capacity_over_time.png)[en.wikipedia.org/wiki/Moore's_law] <<height:250px>>
!(img/arvix-subs.png)[arxiv.org/help/stats/2013_by_area/index] <<height:250px>>
!(img/pdb-all-growth.png)[blog.wellcome.ac.uk/2014/05/14/protein-data-bank-releases-100000th-structure/] <<height:250px>>

====*

## Growth of Temporaries
!(img/postdoc_growth.jpg)  <<height:400px>>

[Source: (NIH) Office of Extramural Research](http://www.americanprogress.org/issues/economy/report/2014/03/25/86369/erosion-of-funding-for-the-national-institutes-of-health-threatens-u-s-leadership-in-biomedical-research)


====*

## International groups
!(img/international_trend.gif) <<height:600px>>

====



# Reasons?

+ More money == More science?
+ New science requires international collaborations, e.g. all the low hanging fruit is gone
+ White bull effect?
+ Diluted second authors?

Is this a bad thing? What is lost?









