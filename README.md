# Welcome to R: Building Phylogenetic Trees with ggtree

In this workshop you will learn how to work with phylogenetic trees programatically using R, particularly using the package [ggtree](https://yulab-smu.top/treedata-book/index.html)


---

<img src="images/multitree.png" alt="tree with heatmaps" width=1000>


## Workshop overview


### Day 1: 100% of what you need to know to make basic trees in R

- Reading in different phylogenetic tree file types

- Plotting trees


### Day 2: Neatly associating trees with complementary data

- Using metadata to subset and highlight features of a tree 

- Plot trees alongside heatmaps


### Day 3: Incorporating trees with quantitative data

- Adding ancestral state reconstruction data to trees

- Comparing and visualizing different tree topologies

- Plotting trees with bar plots


## Session files

There are three R Markdown (.rmd) files for each day of the workshop. 

There are also three R Markdown files containing the answers to each of the day's exercises. 

Each day has a knitted R Markdown .html file that can be used as a reference. Exercise code is left unrun.


## Running workshop code

There are a couple of ways to run this workshop.

### Option 1 (local):

Click on the green Code button and choose Download Zip, unzip the folder on your computer, open the appropriate R Markdown file. 

Please make sure that you have all packages installed! The `install.packages()` command for each package is included in the first code cell of each R Markdown file.

### Option 2 (cloud):

[Click here to run a version of this workshop through your browser using **binder**](https://mybinder.org/v2/gh/fomightez/r_phylogenetics_worshop/main?urlpath=rstudio)

**Many thanks to Wayne ([@Fomightez](https://twitter.com/Fomightez)) for putting this together!**

[Repo fork for binder version](https://github.com/fomightez/r_phylogenetics_worshop)

[Check out Wayne's bioinformatics portal containg other useful bioinformatics tools and pipelines here!](http://fomightez.github.io/)



## Parts of a tree

Here are some useful terms to know when working with trees. The `ggtree()` equiavalents are highlighted in maroon.

<img src="images/tree_parts.png" alt="different terms used to describe a tree" width=1000>


## Reductase gene metadata

The metadata used throughout the workshop for reference.

<img src="images/reductase_metadata.png" alt="metadata for reductase genes" width=1000>

---


**If you liked this workshop, consider taking a look at my [Biopython workshop!](https://github.com/agmcfarland/biopython_workshop)**


## Acknowledgements and references 

Please follow me on twitter! [@alexmcfarland_](https://twitter.com/alexmcfarland_)

[Northwestern University Information Technology Research Computing Services](https://github.com/nuitrcs)

Special thanks to [Colby Witherup Wood](https://github.com/aGitHasNoName) for their assistance

Many thanks to [Wayne Decatur](https://github.com/fomightez) for adapting the code for binder

G Yu. Using ggtree to visualize data on tree-like structures. Current Protocols in Bioinformatics, 2020, 69:e96. doi: 10.1002/cpbi.96.

Paradis E, Schliep K (2019). “ape 5.0: an environment for modern phylogenetics and evolutionary analyses in R.” Bioinformatics, 35, 526-528.

G Yu*, TTY Lam, H Zhu, Y Guan*. Two methods for mapping and visualizing associated data on phylogeny using ggtree. Molecular Biology and Evolution, 2018, 35(2):3041-3043. doi: 10.1093/molbev/msy194.

G Yu, DK Smith, H Zhu, Y Guan, TTY Lam*. ggtree: an R package for visualization and annotation of phylogenetic trees with their covariates and other associated data. Methods in Ecology and Evolution. 2017, 8(1):28-36. doi: 10.1111/2041-210X.12628.
