# tissue-resident-microbiota-fap
This repository provides the microbial network analysis code and datasets for the study "The tissue-resident microbiota of the tumor microenvironment in familial adenomatous polyposis". 


## **Code**

- notebooks/FAP_microbial_network_SparCC.ipynb:

    - To visualize co-occurrence and co-exclusion patterns among ASVs in a specific group.
    
- notebooks/CRC_metabolic_pathway_ridge_plot.ipynb:

    - to visualize differences in abundances between two groups using ridge plots.

    
## **Data**

- data/Maaslin2_age_effect_tumor_site.csv: Taxa associated with age in the FAP and sporadic CRC groups identified using MaAsLin2.

- data/Escherichia_coli_34_ASVs_sequences.txt: Sequences data proving that the *E*. *coli* 16S rRNA sequences variants are distinct from the pro-carcinogenic *pks*<sup>+</sup> *E*. *coli* HM229 strain.



## License & Copyright

- Code License (LICENSE): All data in the code/ directory are licensed under the MIT LICENSE.

- Data License (LICENSE-data.txt): All data in the data/ directory are licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0).

- Third party software used (their licenses):

    - tidyverse (MIT + file LICENSE)
    
    - tidygraph (MIT + file LICENSE)
    
    - ggrepel (GPL-3 | file LICENSE)
    
    - vegan (GPL-2)
    
    - visNetwork (MIT + file LICENSE)
    
    - igraph (GPL (>= 2))
    
    - scales (MIT + file LICENSE)
    
    - ggraph (MIT + file LICENSE)
    
    - ggridges (GPL-2 | file LICENSE)
    
    
Copyright (c) 2025 Hanseol Kim
