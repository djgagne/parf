The [Random Forests](http://www.stat.berkeley.edu/~breiman/RandomForests/cc_home.htm) algorithm is one of the best among the known classification algorithms, able to classify big quantities of data with great accuracy. Also, this algorithm is inherently parallelisable.

Originally, the algorithm was written in the programming language Fortran 77, which is obsolete and does not provide many of the capabilities of modern programming languages; also, the original code is not an example of "clear" programming, so it is very hard to employ in education. Within this project the program is adapted to Fortran 90. In contrast to Fortran 77, Fortran 90 is a structured programming language, legible — to researchers as well as to students.

The creator of the algorithm, Berkeley professor emeritus Leo Breiman, expressed a big interest in this idea in our correspondence. He has confirmed that noone has yet worked on a parallel implementation of his algorithm, and promised his support and help. Leo Breiman is one of the pioneers in the fields of machine learning and data mining, and a co-author of the first significant programs (CART – Classification and Regression Trees) in that field.

The most up-to-date version of PARF's source code can be checked out by SVN (go to the _Source_ tab). Snapshots of the SVN repository are created occasionaly, and available from the _Downloads_ tab for convenience.

To make an executable, a Fortran 90 compiler is required. The currently supported compilers are: [Intel Fortran](http://www.intel.com/cd/software/products/asmo-na/eng/282048.htm) (free on Linux for academic use), [Portland Group Fortran](http://www.pgroup.com/products/workpgi.htm) (commercial) and [GNU g95](http://www.g95.org/) (free).

For an efficient Java implementation of the Random Forest algorithm that integrates into the [Weka](http://www.cs.waikato.ac.nz/ml/weka/) environment, see [FastRandomForest](http://fast-random-forest.googlecode.com).

_RF_ and _Random Forests_ are registered trademarks of Leo Breiman and Adele Cutler.

PARF was developed in the [Centre for Informatics and Computing](http://www.irb.hr/en/cir/) and [Division of Electronics](http://www.irb.hr/en/str/zel/) of [Rudjer Boskovic Institute](http://www.irb.hr/), with the financial support of Ministry of Science, Technology and Sports of Croatia, i-Project 2004-111.

Authors: Goran Topić and Tomislav Šmuc.

![http://www.irb.hr/en/research/projects/it/2004/2004-111/images./2.jpg](http://www.irb.hr/en/research/projects/it/2004/2004-111/images./2.jpg)