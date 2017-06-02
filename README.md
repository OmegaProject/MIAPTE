# MIAPTE
We are proposing a minimum information reporting guideline we term Minimum Information About Particle Tracking Experiments (MIAPTE) that we hope will facilitate the sharing and dissemination of results obtained from Multiple Particle Tracking (MPT) experiments. For our purposes, MPT is defined as described by Chenouard et al. 2014 (http://www.nature.com/doifinder/10.1038/nmeth.2808).  For a brief explanation of the problem you can refer to this nice tutorial page available from Thierry Savin (http://web.mit.edu/savin/Public/.Tutorial_v1.2/Introduction.html).  MIAPTE conforms to the criteria posited by Taylor et al. 2008 (https://www.nature.com/nbt/journal/v26/n8/pdf/nbt.1411.pdf) and currently maintained by the Minimum Information for Biological and Biomedical Investigations (MIBBI) foundry (https://biosharing.org/collection/MIBBI). MIAPTE can also be seen as an extension of the OME-XML data model in that elements, attributes and types defined in that model are re-used here when appropriate to avoid "reinventing the wheel".
The MIAPTE model is intended with different categories of users in mind:

1) Scientists that have produced or are in the course of producing new results and are hoping to make such results available (via deposition to public repositories or via publication) in a way that can be interpreted unequivocally by both humans and machines. This would for example allow results to be re analyzed and merged with other compatible data to produce more complete datasets. For this class of users MIAPTE simply provides a series of data descriptors to define data entries and the analysis workflow in an unified manner.
    
2) Scientists that want to evaluate, replicate and re-analyze results published by others. For this class of users MIAPTE provides descriptors that define the analysis procedures manner that facilitates its reproduction. It also provides data structures that allows to easily retrieve all pieces of information required to access the data in a machine-readable manner.
    
3) Developers who want to take advantage of MIAPTE and the schema that comes with it to produce tools that are capable to inter-operate with the tools produced by the OMEGA project.

MIAPTE is structured in two sub-sections:

1) MIAPTE - Section 1 contains elements, attributes and data structures describing the results of particle tracking, namely: particles, links, segments and trajectories.
2) MIAPTE - Section 2 contains details about the algorithmic procedure utilized to produce and analyze trajectories as well as the results of trajectory analysis.

In June 2016 we deposited MIAPTEv01 to biosharing.org (https://biosharing.org/bsg-s000671). The current version of the model should be intended as a Request for Comments (https://en.wikipedia.org/wiki/Request_for_Comments) type of publication. 
Any member of the scientific or developer community is encouraged to help us refine, modify, extend, improve the model by providing comments, suggestions and criticisms.
