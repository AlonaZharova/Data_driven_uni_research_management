# Data-driven support for policy and decision-making in university research management: A case study from Germany

A digital companion to the research paper 

```
Alona Zharova, Wolfgang Karl Härdle and Stefan Lessmann
Data-driven support for policy and decision-making in university research management: 
A case study from Germany.
European Journal of Operational Research, In Press, (2022).
https://doi.org/10.1016/j.ejor.2022.10.016
```

The paper is available at: [Publisher's website](https://doi.org/10.1016/j.ejor.2022.10.016).
A previous version of the preprint is available at: [SFB 649 Discussion Papers](http://sfb649.wiwi.hu-berlin.de/papers/pdf/SFB649DP2017-028.pdf)

![research_model](/research_model.png)

## Summary

The management of universities requires data on teaching and research performance. While teaching quality can be measured via student performance and teacher evaluation programs, the connection between research output and its antecedents is much harder to check, test, and understand. To inform research governance and policy-making at universities, we clarify the relationship between grant money and research performance. We examine the interdependence structure between third-party expenses, publications, citations, and academic age. To describe the relationship between these factors, we analyze individual-level data from a sample of professorships and a Scopus database from 2001 to 2015. Using estimates from a panel vector autoregressive model with exogenous variables, impulse response functions, and forecast error variance decomposition, we show that decision-making based on the university-level data is inappropriate and does not reflect the behavior of individual faculties. Our results quantify the difference between the quality and quantity of research output, a better understanding of which is important to design incentive schemes and promotion programs. The paper also proposes a visualization of the cooperation between faculties and research interdisciplinarity via the co-authorship structure among publications. We discuss the implications for policy and decision-making and make recommendations for university research management.

**Keywords:**  operational research in organization theory, decision analysis, project management, panel vector autoregressive model with exogenous variables (PVARX).

**JEL classification:** M10, C32, C55.

## Data

Due to the data privacy reasons we are unfortunately not allowed to publish the data used in this paper. However, we do provide the aggregated values to reproduce each of the visualizations. Each folder in this repo contains all the data that is needed to run the codes.

## Reproducing results

The repository contains four visualizations in the corresponding folders. Each folder has an R script that produces a visualization, a csv file with data and a resulting plot. To reproduce a visualization, download the corresponding csv file and run the R script.

## Project structure
````
├── README.txt                                                  # this readme file
|
├── DMFchord                                                    # plots a chord diagram 
│   ├──  DMFchord.R
│   ├──  DMFchord.csv
│   ├──  DMFchordCol.csv
│   ├──  DMFchordPubRF_HUunits_wTMCA_en.png
│   ├──  DMFchordPubRF_fakcoop_HUunits_wTMCA_en.png
│   ├──  Metainfo.txt
│   ├──  README.md 
|
├── DMFpubProVol                                                # plots a time series plot
│   ├──  DMFpubProPubVol.R
│   ├──  DMFpubProPubVol_cit.Rdata
│   ├──  DMFpubProPubVol_pub.Rdata
│   ├──  DMFpubPropubVol_cit_relToResearch.png
│   ├──  DMFpubPropubVol_pub_relToResearch.png
│   ├──  Metainfo.txt
│   ├──  README.md
│   ├──  huLeg.Rdata 
|
├── DMFsankey                                                   # plots a sankey-plot
│   ├──  DMFsankey.R
│   ├──  DMFsankey.csv
│   ├──  DMFsankeycoop_HUunits_full_en.png
│   ├──  Metainfo.txt
│   ├──  README.md 
|
├── DMFtsmtpe                                                   # plots the TPE per researcher 
│   ├──  DMFtsmtpe.R
│   ├──  DMFtsmtpe.csv
│   ├──  DMFtsmtpe_adj.csv
│   ├──  DMFtsmtpe_relRes_with_adj.png
│   ├──  Metainfo.txt
│   ├──  README.md 

````


## Acknowledgements

Financial support from the German Research Foundation (DFG) via Collaborative Research Center 649 "Economic Risk" and International Research Training Group 1792 ”High Dimensional Nonstationary Time Series”, Humboldt-Universität zu Berlin, is gratefully acknowledged. We
are very thankful for support from the Vice-President for Research Peter A. Frensch and fruithful discussions with Ingmar Schmidt and Carsten Gerrits from the Research Service Centre of the Humboldt-Universität zu Berlin. The authors also thank Marius Sterling for his excellent research assistance.

## Contact
- Alona Zharova, alona.zharova@hu-berlin.de
