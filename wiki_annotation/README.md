### Usage ###
The following datasets are licensed under a FIGURE OUT LICENCE OR DISCLAIMER

### Wikipedia Dense Annotations ###

| Language  | **Doc #**  | **Sample** | **Full** |
|:----------|-----------:|-----------:|---------:|
| **en**    | x,xxx  |    [373kb tar.gz ](opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_sample_es_json.tar.gz)   | 
[2.1GB tar.gz ](opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_es_json.tar.gz)   |
| **es**    | x,xxx  |   119,435,659   | 119,435,659   |
| **it**    | x,xxx  | 1,192,210,822   | 119,435,659   |
| **fr**    | x,xxx  | 1,192,210,822   | 119,435,659   |
| **de**    | x,xxx  | 1,192,210,822   | 119,435,659   |
| **ar**    | x,xxx  | 1,192,210,822   | 119,435,659   |


| **fr**    | [1K Sample](sample/user_timestamp_open_set_fb.tsv) | [1K Sample](sample/user_timestamp_open_set_tw.tsv) |
| **Download**  | [2.3GB tar.gz ](http://opendata.klout.com/user_timestamp_data/user_timestamp_open_dataset/user_timestamp_open_set_fb.tar.gz) | 24GB tar.gz   [1](http://opendata.klout.com/user_timestamp_data/user_timestamp_open_dataset/user_timestamp_open_set_tw.tar.gz.01)  [2](http://opendata.klout.com/user_timestamp_data/user_timestamp_open_dataset/user_timestamp_open_set_tw.tar.gz.02)    [3](http://opendata.klout.com/user_timestamp_data/user_timestamp_open_dataset/user_timestamp_open_set_tw.tar.gz.03)    [4](http://opendata.klout.com/user_timestamp_data/user_timestamp_open_dataset/user_timestamp_open_set_tw.tar.gz.04) [5](http://opendata.klout.com/user_timestamp_data/user_timestamp_open_dataset/user_timestamp_open_set_tw.tar.gz.05)   [6](http://opendata.klout.com/user_timestamp_data/user_timestamp_open_dataset/user_timestamp_open_set_tw.tar.gz.06)


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
