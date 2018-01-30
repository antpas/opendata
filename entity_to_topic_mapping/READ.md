### Usage ###
The following datasets are licensed under a [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/).

### Download ###

[Klout Topic Ontology - 2018-01-01](dataset/entity_topic_ground_truth_20180101.csv) 

### File Format ###

The data is encoded as UTF-8 text in tab-separated format. The columns in the dataset are defined as:

* entityId (string)
* entityDisplayName (string)
* topicId (signed int64)
* topicDisplayName (string)
* label ('0', or '1')

Entity id is WikidData ID so for example **Apple inc** has Q312 that one can look up here [https://wikidata.org/wiki/Q312](https://wikidata.org/wiki/Q312).
The topic id's refer to Klout Topic Id's - for more info check paper [Klout Topics for Modeling Interests and Expertise of Users Across Social Networks](https://arxiv.org/pdf/1710.09824.pdf), 
or opendata page [https://github.com/klout/opendata/tree/master/klout_topic_ontology](https://github.com/klout/opendata/tree/master/klout_topic_ontology).

### Example ###

|entityId|entityDisplayName|topicId|topicDisplayName|label| 
|:----|------------------------------|:---:|------------------------------|---|
| **Q312**| Apple Inc|	9219221220892056455| Consumer Electronics| 1 |
| **Q312**| Apple Inc|	5432819378070905100| Food| 0 |


### Citing ###

If you use the dataset, please cite:
```
Klout, 
Klout Topic Ontology, 
https://github.com/opendata, 
07 08, 2015
```

BibTex:
```
@inproceedings{klout:entity_to_topic,
 author = {Preeti Bhargava, Nemanja Spasojevic, Sarah Ellinger, Adithya Rao, Abhinand Menon, Saul Fuhrmann, Guoning Hu}
 title = {Assigning Topics to Entities for Semantically Annotation and Categorization Text},
 howpublished = "\url{https://github.com/klout/opendata}",
 edition = "TBD"
}
```
