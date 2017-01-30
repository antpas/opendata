### Usage ###
The following datasets are licensed under a FIGURE OUT LICENCE OR DISCLAIMER

### Wikipedia Dense Annotations ###

| Language  | **Version #**  | **Doc #**  | **Sample** | **Full** |
|:----------|---:|-----------:|-----------:|---------:|
| **en**    | v1 | x,xxx  |    [373kb tar.gz ](opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_sample_en_json.tar.gz)   | [2.1GB tar.gz ](opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_en_json.tar.gz)   |
| **es**    | v1 | x,xxx  |    [373kb tar.gz ](opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_sample_es_json.tar.gz)   | [2.1GB tar.gz ](opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_es_json.tar.gz)   |
| **it**    | v1 | x,xxx  |    [373kb tar.gz ](opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_sample_it_json.tar.gz)   | [2.1GB tar.gz ](opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_it_json.tar.gz)   |
| **fr**    | v1 | x,xxx  |    [373kb tar.gz ](opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_sample_fr_json.tar.gz)   | [2.1GB tar.gz ](opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_fr_json.tar.gz)   |
| **de**    | v1 | x,xxx  |    [373kb tar.gz ](opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_sample_de_json.tar.gz)   | [2.1GB tar.gz ](opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_de_json.tar.gz)   |
| **ar**    | v1 | x,xxx  |    [373kb tar.gz ](opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_sample_ar_json.tar.gz)   | [2.1GB tar.gz ](opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_ar_json.tar.gz)   |

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

### Entity Mention ###

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
