
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



