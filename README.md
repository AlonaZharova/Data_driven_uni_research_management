# Data-driven support for policy and decision-making in university research management: A case study from Germany

A digital companion to the research paper 

```
Alona Zharova, Wolfgang Karl Härdle and Stefan Lessmann
Data-driven support for policy and decision-making in university research management: 
A case study from Germany.
SFB 649 Discussion Paper 2017-028

```
A previous version of the paper is available at: [SFB 649 Discussion Papers](http://sfb649.wiwi.hu-berlin.de/papers/pdf/SFB649DP2017-028.pdf)

![research_model](/research_model.png)

## Summary

The management of universities requires data on teaching and research performance. While teaching quality can be measured via student performance and teacher evaluation programs, the connection between research output and its antecedents is much harder to check, test, and understand. To inform research governance and policy-making at universities, we clarify the relationship between grant money and research performance. We examine the interdependence structure between third-party expenses, publications, citations, and academic age. To describe the relationship between these factors, we analyze individual-level data from a sample of professorships and a Scopus database from 2001 to 2015. Using estimates from a panel vector autoregressive model with exogenous variables, impulse response functions, and forecast error variance decomposition, we show that decision-making based on the university-level data is inappropriate and does not reflect the behavior of individual faculties. Our results quantify the difference between the quality and quantity of research output, a better understanding of which is important to design incentive schemes and promotion programs. The paper also proposes a visualization of the cooperation between faculties and research interdisciplinarity via the co-authorship structure among publications. We discuss the implications for policy and decision-making and make recommendations for university research management.

**Keywords:**  operational research in organization theory, decision analysis, project management, panel vector autoregressive model with exogenous variables (PVARX).

**JEL classification:** M10, C32, C55.

## Data

Due to the data privacy reasons we are unfortunately not allowed to publish the data used in this paper. However, we do provide the aggregated numbers to reproduce each of the visualizations. Each folder in this repo contains all the data that is needed to run the codes.

## Project structure
````
├── README.txt                                                  # this readme file
|
├── DMFchord                                                    # Plots a chord diagram 
│   ├──  DMFchord.R
│   ├──  DMFchord.csv
│   ├──  DMFchordCol.csv
│   ├──  DMFchordPubRF_HUunits_wTMCA_en.png
│   ├──  DMFchordPubRF_fakcoop_HUunits_wTMCA_en.png
│   ├──  Metainfo.txt
│   ├──  README.md 
|
├── DMFpubProVol                                                # Plots a time series plot
│   ├──  DMFpubProPubVol.R
│   ├──  DMFpubProPubVol_cit.Rdata
│   ├──  DMFpubProPubVol_pub.Rdata
│   ├──  DMFpubPropubVol_cit_relToResearch.png
│   ├──  DMFpubPropubVol_pub_relToResearch.png
│   ├──  Metainfo.txt
│   ├──  README.md
│   ├──  huLeg.Rdata 
|
├── DMFsankey                                                   # Plots a sankey-plot
│   ├──  DMFsankey.R
│   ├──  DMFsankey.csv
│   ├──  DMFsankeycoop_HUunits_full_en.png
│   ├──  Metainfo.txt
│   ├──  README.md 
|
├── DMFtsmtpe                                                   # Plots the TPE per researcher 
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
