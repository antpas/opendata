### Usage ###
The following datasets are licensed under a FIGURE OUT LICENCE OR DISCLAIMER

### Wikipedia Dense Annotations ###

### Entity Mention ###

Example of single document JSON:
```
{
	"tokens": [{
		"raw_form": "Vlade"
	}, {
		"raw_form": "Divac"
	}, {
		"raw_form": "is"
	}, {
		"raw_form": "a"
	}, {
		"raw_form": "retired"
	}, {
		"raw_form": "Serbian"
	}, {
		"raw_form": "NBA"
	}, {
		"raw_form": "player",
		"break": "SENTENCE"
	}],
	"entities": [{
		"id_str": "01vpr3",
		"type": "PERSON",
		"start_position": 0,
		"end_position": 1,
		"raw_form": "Vlade Divac"
	}, {
		"id_str": "077qn",
		"type": "LOCATION",
		"start_position": 5,
		"end_position": 5,
		"raw_form": "Serbian"
	}, {
		"id_str": "05jvx",
		"type": "ORGANIZATION",
		"start_position": 6,
		"end_position": 6,
		"raw_form": "NBA"
	}],
	"id": "wiki_page_id:en:322505:01vpr3:Vlade_Divac"
}
```

### Entity Cooccurrences ###

### Word2Vec Glove ###

### Citing ###


If you use the dataset, please cite:
```
author, author, author
Title Title 
Proceedings of Blap Blop 2017.
```

BibTex:
```
@inproceedings{Spasojevic:wiki_annotation,
 author = {...},
 title = {...},
 booktitle = {...},
 series = {...},
 year = {2017}
}
```
