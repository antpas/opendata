Usage: The following datasets are licensed under a [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/).

The following datasets contain post and reaction timestamp of messages created on Facebook and Twitter between November 9, 2014 and February 9, 2015 along with a hash of the message_id and timezone of the user.
The timestamps are in UTC format and are represented in milliseconds.

The dataset contains posts created by registered users of Klout.com on Facebook and timestamp of comments by users on the posts and posts that received at least one comment.

The Twitter data set contains timestamp of tweets created by registered users of Klout.com on Twitter and the retweet timestamp.

The dataset has 51,582,026 and 64,647,460 messages and 62,860,464 and 65,414,715 action timestamps
for Facebook and Twitter respectively.

**File format:** The files are compressed and tab-separated and has the following format:

    message_id_hash message_timestamp message_creator_timezone action_timestamp

Example Entry:

    1659703015246365873     1418918268000   Central European Time   1418948569000

[Facebook DataSet](http://opendata.klout.com/user_content_open_set/user_content_open_fb.tar.gz)

[Twitter DataSet](http://opendata.klout.com/user_content_open_set/user_content_open_tw.tar.gz)
