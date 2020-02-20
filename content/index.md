# Cambridge Keydata

This page is for working group "Keydata Project" at Cambridge University.


## Modeling usage differences

* [Word usage differences in Labour vs Tory manifestos](https://public.tableau.com/views/WordusagedifferencesinLabourvsTorymanifestos/QualitativevsQuantitativeDistancesperwordinmanifestos?:display_count=y&publish=yes&:origin=viz_share_link)


## Network graphs (Feb 19)

### Network structure statistics

These are using the model trained on the Tory and Labour manifestos themselves.

#### Number of subgraphs ("islands")

![num_subgraphs](%assets_url%/network_data/top100_manifestomodel/plot.num_subgraphs.png)

#### Number of edges

![num_edges](%assets_url%/network_data/top100_manifestomodel/plot.num_edges.png)

#### Density

![density](%assets_url%/network_data/top100_manifestomodel/plot.density.png)

#### Clustering coefficient

![clustering_coefficient_global](%assets_url%/network_data/top100_manifestomodel/plot.clustering_coefficient_global.png)


### New networks using word2vec model trained on manifestos themselves


| Party | Year | Node sizing | Graphs |
| ----- | ---- | ----------- | ------ |
| Labour | 1964 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1964_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1964_G2.html)] |
| Labour | 1964 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1964_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1964_G2_BC.html)] |
| Labour | 1966 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1966_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1966_G2.html)] |
| Labour | 1966 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1966_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1966_G2_BC.html)] |
| Labour | 1970 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1970_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1970_G2.html)] |
| Labour | 1970 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1970_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1970_G2_BC.html)] |
| Labour | 1974 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1974_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1974_G2.html)] |
| Labour | 1974 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1974_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1974_G2_BC.html)] |
| Labour | 1979 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1979_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1979_G2.html)] |
| Labour | 1979 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1979_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1979_G2_BC.html)] |
| Labour | 1983 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1983_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1983_G2.html)] |
| Labour | 1983 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1983_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1983_G2_BC.html)] |
| Labour | 1987 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1987_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1987_G2.html)] |
| Labour | 1987 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1987_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1987_G2_BC.html)] |
| Labour | 1992 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1992_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1992_G2.html)] |
| Labour | 1992 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1992_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1992_G2_BC.html)] |
| Labour | 1997 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1997_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1997_G2.html)] |
| Labour | 1997 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1997_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_1997_G2_BC.html)] |
| Labour | 2001 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2001_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2001_G2.html)] |
| Labour | 2001 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2001_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2001_G2_BC.html)] |
| Labour | 2005 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2005_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2005_G2.html)] |
| Labour | 2005 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2005_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2005_G2_BC.html)] |
| Labour | 2015 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2015_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2015_G2.html)] |
| Labour | 2015 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2015_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2015_G2_BC.html)] |
| Labour | 2017 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2017_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2017_G2.html)] |
| Labour | 2017 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2017_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Labour_2017_G2_BC.html)] |
| Tory | 1964 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1964_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1964_G2.html)] |
| Tory | 1964 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1964_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1964_G2_BC.html)] |
| Tory | 1966 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1966_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1966_G2.html)] |
| Tory | 1966 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1966_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1966_G2_BC.html)] |
| Tory | 1970 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1970_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1970_G2.html)] |
| Tory | 1970 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1970_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1970_G2_BC.html)] |
| Tory | 1974 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1974_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1974_G2.html)] |
| Tory | 1974 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1974_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1974_G2_BC.html)] |
| Tory | 1979 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1979_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1979_G2.html)] |
| Tory | 1979 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1979_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1979_G2_BC.html)] |
| Tory | 1983 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1983_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1983_G2.html)] |
| Tory | 1983 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1983_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1983_G2_BC.html)] |
| Tory | 1987 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1987_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1987_G2.html)] |
| Tory | 1987 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1987_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1987_G2_BC.html)] |
| Tory | 1992 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1992_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1992_G2.html)] |
| Tory | 1992 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1992_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1992_G2_BC.html)] |
| Tory | 1997 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1997_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1997_G2.html)] |
| Tory | 1997 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1997_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_1997_G2_BC.html)] |
| Tory | 2001 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2001_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2001_G2.html)] |
| Tory | 2001 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2001_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2001_G2_BC.html)] |
| Tory | 2005 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2005_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2005_G2.html)] |
| Tory | 2005 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2005_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2005_G2_BC.html)] |
| Tory | 2015 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2015_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2015_G2.html)] |
| Tory | 2015 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2015_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2015_G2_BC.html)] |
| Tory | 2017 | Frequency | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2017_G1.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2017_G2.html)] |
| Tory | 2017 | Betweenness Centrality | [[G1](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2017_G1_BC.html)] [[G2](%assets_url%/network_data/top100_manifestomodel/graph_Tory_2017_G2_BC.html)] |


## Network graphs

Network graphs for experiment on using semantic vectors to find underlying semantic topography of a text.

All graphs built so far on the 1990s Google Books word2vec model. The number of "synonyms" in each case is 10. The top 100 nouns from each text were taken.

### Labour vs. Tory (2019)

| Text | Node sizing |
| ---- | ----------- |
| Labour manifesto [[G1](%assets_url%/networks/graph_labour_manifesto_G1.html)] [[G2](%assets_url%/networks/graph_labour_manifesto_G2.html)] | Frequency |
| Tory manifesto [[G1](%assets_url%/networks/graph_tory_manifesto_G1.html)] [[G2](%assets_url%/networks/graph_tory_manifesto_G2.html)] | Frequency |


### Labour (1964-2017) vs. Tory (1964-2019)

| Text | Node sizing |
| ---- | ----------- |
| Labour manifestos [[G1](%assets_url%/network_data/top100_manymanifesto/graph_labour_manifestos_G1.html)] [[G2](%assets_url%/network_data/top100_manymanifesto/graph_labour_manifestos_G2.html)] | Frequency |
| Tory manifestos [[G1](%assets_url%/network_data/top100_manymanifesto/graph_tory_manifestos_G1.html)] [[G2](%assets_url%/network_data/top100_manymanifesto/graph_tory_manifestos_G2.html)] | Frequency |
| Labour manifestos [[G1](%assets_url%/network_data/top100_manymanifesto_betweenness/graph_labour_manifestos_G1.html)] [[G2](%assets_url%/network_data/top100_manymanifesto_betweenness/graph_labour_manifestos_G2.html)] | Betweenness Centrality |
| Tory manifestos [[G1](%assets_url%/network_data/top100_manymanifesto_betweenness/graph_tory_manifestos_G1.html)] [[G2](%assets_url%/network_data/top100_manymanifesto_betweenness/graph_tory_manifestos_G2.html)] | Betweenness Centrality |

### Labour (1964-1997) vs. Labour (2001-2017)

| Text | Node sizing |
| ---- | ----------- |
| Labour manifestos (1964-1997) [[G1](%assets_url%/network_data/top100_historical/graph_labour_manifestos_C20_G1.html)] [[G2](%assets_url%/network_data/top100_historical/graph_labour_manifestos_C20_G2.html)] | Frequency |
| Labour manifestos (2001-2017) [[G1](%assets_url%/network_data/top100_historical/graph_labour_manifestos_C21_G1.html)] [[G2](%assets_url%/network_data/top100_historical/graph_labour_manifestos_C21_G2.html)] | Frequency |
| Labour manifestos (1964-1997) [[G1](%assets_url%/network_data/top100_historical_betweenness/graph_labour_manifestos_C20_G1.html)] [[G2](%assets_url%/network_data/top100_historical_betweenness/graph_labour_manifestos_C20_G2.html)] | Betweenness Centrality |
| Labour manifestos (2001-2017) [[G1](%assets_url%/network_data/top100_historical_betweenness/graph_labour_manifestos_C21_G1.html)] [[G2](%assets_url%/network_data/top100_historical_betweenness/graph_labour_manifestos_C21_G2.html)] | Betweenness Centrality |


### Tory (1964-1997) vs. Tory (2001-2017)

| Text | Node sizing |
| ---- | ----------- |
| Tory manifestos (1964-1997) [[G1](%assets_url%/network_data/top100_historical/graph_tory_manifestos_C20_G1.html)] [[G2](%assets_url%/network_data/top100_historical/graph_tory_manifestos_C20_G2.html)] | Frequency |
| Tory manifestos (2001-2017) [[G1](%assets_url%/network_data/top100_historical/graph_tory_manifestos_C21_G1.html)] [[G2](%assets_url%/network_data/top100_historical/graph_tory_manifestos_C21_G2.html)] | Frequency |
| Tory manifestos (1964-1997) [[G1](%assets_url%/network_data/top100_historical_betweenness/graph_tory_manifestos_C20_G1.html)] [[G2](%assets_url%/network_data/top100_historical_betweenness/graph_tory_manifestos_C20_G2.html)] | Betweenness Centrality |
| Tory manifestos (2001-2017) [[G1](%assets_url%/network_data/top100_historical_betweenness/graph_tory_manifestos_C21_G1.html)] [[G2](%assets_url%/network_data/top100_historical_betweenness/graph_tory_manifestos_C21_G2.html)] | Betweenness Centrality |

## Meeting Notes

### Meeting 1

See [here](https://www.dropbox.com/s/c8jmgddu3ekktj1/KeydataIntroMeeting.pptx?dl=1) for a copy of the powerpoint shown in the first meeting.

### Meeting 2

See [here](https://www.dropbox.com/s/pmm5bysdddvmkvf/keydata-meeting-2.pptx?dl=1) for a copy of the powerpoint shown in the second meeting.

### Etc

* [Blackstones](%assets_url%/network_data/etc/graph_blackstone_G2.html)
	* [Full text](%assets_url%/network_data/etc/Blackstone.Laws_of_England.txt)
