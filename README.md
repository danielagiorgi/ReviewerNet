# Semantic Browser
This website is a D3.js-based browser on a filtered version of the <a href="http://labs.semanticscholar.org/corpus/">Semantic
Scholar</a> corpus. The user can search for papers and build its own cluster of interesting papers that we call **P**, from which is 
generated **N(P)**</strong>, the neighbors of P, that are the in and out citations. Above the paper graph the one referred 
to the authors is displayed.
> *screenshot soon...*

## Getting started
Often program committee members are required to find reviewers that know well a subject but are not conflicted with the 
authors of the paper under scrutiny. We propose a tool that allow the user to build its topic-based graph searching papers from: 
*ACM Transactions on Graphics*, *Computer Graphics Forum* and *IEEE Transactions on Visualization and Computer Graphics*.
The user can also add authors to the *Conflicting Authors* list, the effect is described in the *author area* section.
In this it is immediately possible to identify all the possible candidate-reviewers.

### Usage
Just visit
> https://hybrs.github.io <br>
> *tested browsers: Chrome, Firefox, Safari* 



## Papers&Authors 
Mouse events that change the visualization are associated both to authors and papers. 

### The paper graph
* x-constrained by year of pubblication;
* personalizable color-map based on the number of in-citations;

### The author area
* ranked by a weighted sum of the number of papers in **P** and **N(P)**
* a rectange under the author's name spans from the oldest to the last year of pubblication.
* name in red indicates conflict with at least one author in the *Conflicting Authors* list;
* name in purple indicates that the author has been added to the *Conflicting Authors* list;

## The toolbox
This area of the page allows the user to personalize the view:
* *MNP*: ---
* *MNoC*: ---
* *Colormap*: ---
* *Stats*: ---
* *Display related authors*: ---