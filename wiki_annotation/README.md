# DAWT: Densely Annotated Wikipedia Texts across multiple languages #

## Usage ##

The following datasets are licensed under a [Attribution-ShareAlike 3.0 Unported](https://creativecommons.org/licenses/by-nc-sa/4.0/)
same as [Wikipedia Database Dumps](https://dumps.wikimedia.org/).

![CC BY-NC-SA](CC-BY-NC-SA.png)

Files with gpg extensions are encrypted, to obtain obtain the key please:
  * Send an email to **team-relevance@klout.com**.
  * Let us know what academic institution are you affiliated with.
  * Briefly desscribe what and how are you planing to use data.

Example of how to decrypt file is [down below](https://github.com/klout/opendata/tree/master/wiki_annotation#decript-gpg-file).

## Data Set ##

TODO: - add explanation about the data set 


### Wikipedia Dense Annotations ###

| Language  | **Version #**  | **Doc #**  | **Sample** | **Full** |
|:----------|---:|-----------:|-----------:|---------:|
| **en**    | v1 | 5,303,722  |    [725kb tar.gz ](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_sample_en_json.tar.gz)   | [1/4](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_json_en_part_00.tar.gz.gpg), [2/4](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_json_en_part_01.tar.gz.gpg), [3/4](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_json_en_part_02.tar.gz.gpg), [4/4](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_json_en_part_03.tar.gz.gpg) tar.gz.gpg  |
| **es**    | v1 | 2,393,366 |    [373kb tar.gz ](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_sample_es_json.tar.gz)   | [2.1GB tar.gz.gpg ](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_es_json.tar.gz)   |
| **it**    | v1 | 1,467,486  |    [332KB tar.gz ](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_sample_it_json.tar.gz)   | [1.6GB tar.gz.gpg ](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_it_json.tar.gz)   |
| **fr**    | v1 | 1,750,536  |    [429KB tar.gz ](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_sample_fr_json.tar.gz)   | [2.8GB tar.gz.gpg ](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_fr_json.tar.gz)   |
| **de**    | v1 | 1,818,649  |    [454KB tar.gz ](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_sample_de_json.tar.gz)   | [3.7GB tar.gz.gpg ](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_de_json.tar.gz)   |
| **ar**    | v1 | 889,007  |    [297KB tar.gz ](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_sample_ar_json.tar.gz)   | [482MB tar.gz.gpg ](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_ar_json.tar.gz)   |

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

| Language  | **Version #**  | **Pair #**  | **Sample** | **Full** |
|:----------|---:|-----------:|-----------:|---------:|
| **en**    | v1 | x,xxx  |    [TODO](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_sample_en_json.tar.gz)   | [TODO](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_en_json.tar.gz)   |

### Entity Cooccurrences ###

| Language  | **Version #**  | **Pari #**  | **Sample** | **Full** |
|:----------|---:|-----------:|-----------:|---------:|
| **en**    | v1 | x,xxx  |    [TODO](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_sample_en_json.tar.gz)   | [TODO](http://opendata.klout.com/wiki/wiki_annotation/v1/wiki_annotations_en_json.tar.gz)   |


### Word2Vec - [GloVe](http://nlp.stanford.edu/projects/glove/) ###

| Vector Size  | **Version #**  | **Entity #**  | **Full** |
|:----------|---:|-----------:|-----------:|
| **50**    | v1 | 1,612,117  | [316MB tar.gz](http://opendata.klout.com/wiki/word2vec/v1/wiki_entity_all_50_vectors.tar.gz)   | 
| **300**   | v1 | 1,612,117  | [1.7GB tar.gz](http://opendata.klout.com/wiki/word2vec/v1/wiki_entity_all_300_vectors.tar.gz)   | 
| **1000**  | v1 | 1,612,117  | [1.9GB tar.gz 1/3](http://opendata.klout.com/wiki/word2vec/v1/wiki_entity_all_1000_vector_part_1.tar.gz), [1.8GB tar.gz 2/3](http://opendata.klout.com/wiki/word2vec/v1/wiki_entity_all_1000_vector_part_1.tar.gz), [1.6GB tar.gz 3/3](http://opendata.klout.com/wiki/word2vec/v1/wiki_entity_all_1000_vector_part_1.tar.gz)   | 


### Decript GPG File ###

```
# Decript File (assuming key locally abaiable in v1.gpg_key)
gpg --cipher-algo AES256 --passphrase $(cat v1.gpg_key) --output wiki_annotations_sample_es_json.tar.gz --decrypt wiki_annotations_sample_es_json.tar.gz.gpg

# Uncompress File. 
tar xvfz wiki_annotations_sample_es_json.tar.gz
```

### Citing ###


If you use the dataset, please cite:
```
author, author, author
DAWT: Densely Annotated Wikipedia Texts across multiple languages
Proceedings of Blap Blop 2017.
```

BibTex:
```
@inproceedings{Spasojevic:wiki_annotation,
 author = {...},
 title = {DAWT: Densely Annotated Wikipedia Texts across multiple languages},
 booktitle = {...},
 series = {...},
 year = {2017}
}
```

