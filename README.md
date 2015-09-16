# emnlp15-dim4auc

This repository contains the code used to perform the classification experiments described in section 4.2 of the paper:

Judith Eckle-Kohler, Roland Kluge and Iryna Gurevych. On the Role of Discourse Markers for Discriminating Claims and Premises in Argumentative Discourse. In: Proceedings of the 2015 Conference on Empirical Methods in Natural Language Processing (EMNLP), p. 2249-2255, September 2015.

For more information see also: https://www.ukp.tu-darmstadt.de/data/argumentation-mining/argument-annotated-news-articles/

## Package structure
  * the package `experiment` contains the runnable classification experiments which make use of the [DKPro TC](https://dkpro.github.io/dkpro-tc/) framework.
  * the package `explore` contains code used for the extraction of data-driven features from the [German Tiger corpus](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/tiger.html). It makes use of [DKPro Core](https://dkpro.github.io/dkpro-core/). 


## Howto
  * to obtain the annotated dataset, please contact eckle-kohler@ukp.informatik.tu-darmstadt.de or the primary contact of the argumentation mining group at [UKP](https://www.ukp.tu-darmstadt.de/ukp-home/), see https://www.ukp.tu-darmstadt.de/research/research-areas/argumentation-mining
  * runnable classification experiments are in the package `experiment`; in order to run them, you have to modify the paths to corpus data and results data according to your system and environment
 
  



