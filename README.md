
# "defoe_visualization" 

This repository contains notebooks to visulaize (and to do further analyses) the results of the queries.   

---

## Visualizations

### Stranger Danger

The Stranger_Danger notebook analyses the results from running "stranger danger" query against the BL books. This query searches for sentences where the words “stranger” and “danger” (maching criteria) appear within the same sentence. And it generates an ouputfile, called stranger_danger.yml, with the results.

* [Stranger Danger Notebook](Stranger_Danger/Stranger_Danger.ipynb)
* [Stranger Danger query results](Stranger_Danger/results/stranger_danger.yml)
* [Normaliser query results](Stranger_Danger/results/Stranger_Danger.yml)


### Diseases

The notebook examinates the presence and rate of occurence of certain disease names in corpus by: 1) looking at the results of the diseaes query, 2) creating graphs it per year, 3) comparing these diseases, and 4) normalising the data, to account for increased publishing activity over time.

* [Diseases Notebook](Diseases/Diseases_1.ipynb)
* [Diseases and normaliser queries results](Diseases/results)


### Female Emigration

These notebooks examinatethe attitudes towards female emigration from Great Britain to the
‘Colonies’ and North America from 1850 to 1914. It uses two digital corpuses - British Library Newspapers (BLN) and Times Digital Archive (TDA). 

* Normalised frequencies of the names of female [emigration societies](https://github.com/alan-turing-institute/defoe/blob/master/queries/emigration_societies.txt):
    * [BLN](https://github.com/alan-turing-institute/defoe_visualization/edit/master/README.mdhttps://github.com/alan-turing-institute/defoe_visualization/blob/master/Female_Emigration/BLN_Parts1-6/Visualization_Frequency_Societies_BLN.ipynb)
    * [TDA](https://github.com/alan-turing-institute/defoe_visualization/blob/master/Female_Emigration/TDA/Visualization_Frequency_Societies_TDA.ipynb)

* Normalised frequencies of specially chosen [taxonomy terms](https://github.com/alan-turing-institute/defoe/blob/master/queries/emigration_taxonomy.txt) relating to female emigration
    * [BLN](https://github.com/alan-turing-institute/defoe_visualization/blob/master/Female_Emigration/BLN_Parts1-6/Visualization_Frequency_Taxonomy_BLN.ipynb)
    * [BLN N-grams](https://github.com/alan-turing-institute/defoe_visualization/blob/master/Female_Emigration/BLN_Parts1-6/Visualization_Frequency_Taxonomy_Ngrams_BLN.ipynb)
    * [TDA](https://github.com/alan-turing-institute/defoe_visualization/blob/master/Female_Emigration/TDA/Visualization_Frequency_Taxonomy_TDA.ipynb)
    * [TDA N-grams](https://github.com/alan-turing-institute/defoe_visualization/blob/master/Female_Emigration/TDA/Visualization_Frequency_Taxonomy_Ngrams_TDA.ipynb)
  




