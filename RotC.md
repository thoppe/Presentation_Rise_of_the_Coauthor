{"theme":"beige.css"}

# Rise of
# the Coauthor
<div class="footnote">_(a very meta journal-club)_</div>


*[Travis Hoppe](http://thoppe.github.io/)*, Dan Appella
[(deck source)](https://github.com/thoppe/Rise-of-the-Coauthor)

====

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

For each journal, every table of contents was downloaded, 
this gave title and authorship information for each paper.

Filtered for editorials, corrections, errata, book reviews, ...
Approximately 2.4K TOC and 655K papers.

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

LARGE project collaborations, removed from study.

[Finishing the euchromatic sequence of the human genome](http://www.nature.com/nature/journal/v431/n7011/full/nature03001.html)

[A Particle Consistent with the Higgs Boson Observed with the ATLAS Detector at the Large Hadron Collider](http://www.sciencemag.org/content/278/5344/1765.full)

[Characterization of the Martian Surface Deposits by the Mars Pathfinder Rover, Sojourner](http://www.sciencemag.org/content/278/5344/1765.full)

====

# Authorship distribution

In most cases the _distribution_ of authorship follows a Poisson;
the mean is approximately the variance.

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
### Bibliographics via Thomson-Reuters

[Common metrics](http://libguides.jcu.edu.au/content.php?pid=276452&sid=2587740) for scientific impact:

Total citations
Impact factor / Article influence
Eigenfactor (similar to Google's page-rank)

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

====* !(img/JBC_absolute_word_popularity_stack.png 80% slide)
====* !(img/NATURE_scaled_coauthor_average.png 80% slide)
====
## Title length
Number of significant words in the title, some are quite verbose.

====+
<div class="footnote">
[.alpha.- and .beta.-Carboxylic groups as primary ligating groups in promoting amide deprotonation. Solid-state behavior of N-tosylalaninate-copper(II) complexes: crystal and molecular structures of bis(N-tosyl-.beta.-alaninato) bis(imidazole)copper(II), polymeric (N-tosyl-.alpha.-alaninato) diaquacopper(II) monohydrate, and dipiperidinium bis(N-tosyl-.alpha.-alaninato) cuprate(II) monohydrate complexes](http://pubs.acs.org/doi/abs/10.1021/ja00291a043)
</div>
====+
<div class="footnote">[Prospective study of cytotoxic T lymphocyte responses to influenza and antibodies to human T lymphotropic virus-III in homosexual men. Selective loss of an influenza-specific, human leukocyte antigen-restricted cytotoxic T lymphocyte response in human T lymphotropic virus-III positive individuals with symptoms of acquired immunodeficiency syndrome and in a patient with acquired immunodeficiency syndrome](http://www.ncbi.nlm.nih.gov/pubmed/2997287)
</div>

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

Some metrics: science budgets, big data, nationalities of postdoctoral students, number of international collaborations, ...

====*
## NIH Funding
!(img/NIH_funding1.png)[(http://www.americanprogress.org/issues/economy/report/2014/03/25/86369/erosion-of-funding-for-the-national-institutes-of-health-threatens-u-s-leadership-in-biomedical-research/] <<height:500px>>
 
====*
### Growth of Data
!(img/NCBI_usage.png)[http://www.nlm.nih.gov/about/2015CJ.html] <<height:250px>>
!(img/Hard_drive_capacity_over_time.png)[http://en.wikipedia.org/wiki/Moore's_law] <<height:250px>>
!(img/arvix-subs.png)[http://arxiv.org/help/stats/2013_by_area/index] <<height:250px>>
!(img/pdb-all-growth.png)[http://blog.wellcome.ac.uk/2014/05/14/protein-data-bank-releases-100000th-structure/] <<height:250px>>

====*

## International growth
!(img/non_us_postdocs.jpg)[http://nsf.gov]  <<height:500px>>
!(img/international_trend.gif) <<height:500px>>

====

# Authorship Growth
### Can it continue unabated? Discuss!

+ More money $\rightarrow$ larger science?
+ Grants favor international collaborations?
+ [White bull](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC1734216/) effect?
+ Diluted second authors?


+ Is this a bad thing? What is lost?

====

# Thanks, you.







