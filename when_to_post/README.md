### Usage ###
The following datasets are licensed under a [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/).

The dataset contains **sampled anonymized** action and reaction events for posts that were created between October 15, 2014 and February 11, 2015 and received at least one reaction. In order to preserve privacy, timestamps were slightly perturbed and user and post ids were anonymized using custom fingerprint functions. The timestamps are Unix epoch time in milliseconds.

* For Facebook, the dataset contains post and comment event timestamps.
* For Twitter, the dataset contains tweet and retweet event timestamps.


| Count         | **Facebook**  | **Twitter**     |
|:--------------|--------------:|----------------:|
| **Users**     |   1,067,026   |     1,423,445   |
| **Posts**     |  25,937,525   |   119,435,659   |
| **Reactions** | 104,364,591   | 1,192,210,822   |
| **Sample**    | [1K Sample](sample/user_timestamp_open_set_fb.tsv) | [1K Sample](sample/user_timestamp_open_set_tw.tsv) |
| **Download**  | [2.3GB tar.gz ](http://opendata.klout.com/user_timestamp_open_dataset/user_timestamp_open_set_fb.tar.gz) | 24GB tar.gz   [1](http://opendata.klout.com/user_timestamp_open_dataset/user_timestamp_open_set_tw.tar.gz.01)  [2](http://opendata.klout.com/user_timestamp_open_dataset/user_timestamp_open_set_tw.tar.gz.02)    [3](http://opendata.klout.com/user_timestamp_open_dataset/user_timestamp_open_set_tw.tar.gz.03)    [4](http://opendata.klout.com/user_timestamp_open_dataset/user_timestamp_open_set_tw.tar.gz.04) [5](http://opendata.klout.com/user_timestamp_open_dataset/user_timestamp_open_set_tw.tar.gz.05)   [6](http://opendata.klout.com/user_timestamp_open_dataset/user_timestamp_open_set_tw.tar.gz.06)


### File Format ###

The data is encoded as UTF-8 text in tab-separated format and compressed with Gzip. The columns in the dataset are defined as:

* user_id_fingerprint (signed int64)
* actor_id_fingerprint (signed int64)
* post_id_fingerprint (signed int64)
* post_timestamp (Unix epoch time in milliseconds)
* action_timestamp (Unix epoch time in milliseconds)
* user_timezone ([Freebase timezone name](https://www.freebase.com/time/time_zone/time_zone_name_standard) eg. [Central Standard Time)](https://www.freebase.com/m/02fqwt))

### Example ###

[![Example](images/user_timestamp_dataset_example.png)](images/user_timestamp_dataset_example.png)

The dataset is divided into sets grouped by the date of the post creation.


### Citing ###

Paper ([acm](http://dl.acm.org/citation.cfm?id=2783258.2788584), [arxiv](http://arxiv.org/abs/1506.02089)), [Video](https://www.youtube.com/watch?v=RN7z6W_EwqM), [Slides](http://www.slideshare.net/sofrasofra/bids2015-when-to-post-on-social-media-2)

If you use the dataset, please cite:
```
Nemanja Spasojevic, Zhisheng Li, Adithya Rao, Prantik Bhattacharyya, 
When-To-Post on Social Networks, 
Proceedings of ACM Conference on Knowledge Discovery and Data Mining (KDD), 2015.
```

BibTex:
```
@inproceedings{Spasojevic:when-to-post,
 author = {Spasojevic, Nemanja and Li, Zhisheng and Rao, Adithya and Bhattacharyya, Prantik},
 title = {When-To-Post on Social Networks},
 booktitle = {Proc. of ACM Conference on Knowledge Discovery and Data Mining (KDD)},
 series = {KDD '15},
 year = {2015}
}
```
