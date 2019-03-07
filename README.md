## HATESPEECH DATA FROM TWITTER AND WHISPER

1. This repository contains data from * Mainack Mondal, Leandro Araujo Silva and Fabricio Benevenuto. 2017. "A Measurement Study of Hate Speech in Social Media." HT'17. You can read the paper [here](https://homepages.dcc.ufmg.br/~fabricio/download/HT2017-hatespeech.pdf)
1. *If you have any questions about this data feel free to contact Dr. Mainack Mondal (email id in the paper pdf).*
1. This is data on hatepspeech collected from social media sites Twitter and Whisper on 2014 - 2015. 
1. The dataset contains total 20,705 hate posts from Twitter and 7,604 hate posts from  Whisper,

1. **Please cite our paper in any published work that uses any of these resources.**

~~~
@inproceedings{mondal2017,
 author = {Mainack Mondal and Leandro A. A. Silva and Fabricio Benevenuto},
 title = {A Measurement Study of Hate Speech in Social Media},
 booktitle = {Proceedings of the 28th ACM Conference on Hypertext and Social Media},
 series = {HT '17},
 year = {2017},## HATESPEECH DATA FROM TWITTER AND WHISPER

1. This repository contains data from * Mainack Mondal, Leandro Araujo Silva and Fabricio Benevenuto. 2017. "A Measurement Study of Hate Speech in Social Media." HT'17. You can read the paper [here](https://homepages.dcc.ufmg.br/~fabricio/download/HT2017-hatespeech.pdf)
1. *If you have any questions about this data feel free to contact Dr. Mainack Mondal (email id in the paper pdf).*
1. This is data on hatepspeech collected from social media sites Twitter and Whisper on 2014 - 2015. 
1. The dataset contains total 20,705 hate posts from Twitter and 7,604 hate posts from  Whisper,

1. **Please cite our paper in any published work that uses any of these resources.**

~~~
@inproceedings{mondal2017,
 author = {Mainack Mondal and Leandro A. A. Silva and Fabricio Benevenuto},
 title = {A Measurement Study of Hate Speech in Social Media},
 booktitle = {Proceedings of the 28th ACM Conference on Hypertext and Social Media},
 series = {HT '17},
 year = {2017},
 location = {Prague, Czech Republic},
 publisher = {ACM}
}
~~~ 

## WARNING

1. This dataset contain swear words and hateful language that users posted while expressing hate.
1. The csv file contains unicode characters.


## Description of Twitter data

* Our Twitter dataset including 20,705 tweets are in the csv file **hatespeech_twitter_released_hypertext_2017.csv**

* There are three columns: 

	1. **Tweet id**: Unfortunately Twitter does not allow developers to share the full tweet json object, but only the tweet id. You need to refetch the tweet object using these tweet ids. Note that some tweets might be unavailable due to account deletion, tweet deletion or account suspension between 2015 (when the data was collected) and now. 

	1. **Hate targets extracted from the tweet text**: Groups of people extracted from the tweet text who are the subject of hate in the tweet. E.g., for a hypothetical tweet "I strongly hate/dislike black people", "black people" is the hate target.

	1. **Hate categories assigned by us**: We manually labeled each hate_target into one of our hate categories and put the manual label in this column. For a comprehensive list of the hate categories, check our paper.

## Description of Whisper data

1. Whisper is an anonymous social media site.

1. Our Whisper dataset including 7,604 posts are in the csv file **hatespeech_whisper_released_hypertext_2017.csv**
1. There are eight columns: 
	1. **Serial**: An incremental serial assigned to each post by us. 
	1. **text**:The user generated text of the post.
	1. **unix timestamp (milliseconds)**: time when the post was uploaded
	1. **whisper_assigned_categories**: Whisper automatically assigns categories to the text. This column contains a comma separated list of those categories for each post. A blank value means no category was assigned.
	1. **country**: Country from which the post was made. 
	1. **region**: Region (e.g., US state or city) from which the post was made. 
	1. **Hate targets extracted from the whisper text**: Groups of people extracted from the whisper text who are the subject of hate in the whisper. E.g., for a hypothetical whisper "I strongly hate/dislike black people", "black people" is the hate target.
	1. **Hate categories assigned by us**: We manually labeled each hate_target into one of our hate categories and put the manual label in this column. For a comprehensive list of the hate categories, check our paper.	


##### Release date: 7th March, 2019
##### authors: Mainack Mondal and Leandro A. A. Silva and Fabricio Benevenuto

 location = {Prague, Czech Republic},
 publisher = {ACM}
}
~~~




## WARNING

1. This dataset contain swear words and hateful language that users posted while expressing hate.
1. The csv file contains unicode characters.


## Description of Twitter data

* Our Twitter dataset including 20,705 tweets are in the csv file **hatespeech_twitter_released_hypertext_2017.csv**

* There are three columns: 

	1. **Tweet id**: Unfortunately Twitter does not allow developers to share the full tweet json object, but only the tweet id. You need to refetch the tweet object using these tweet ids. Note that some tweets might be unavailable due to account deletion, tweet deletion or account suspension between 2015 (when the data was collected) and now. 

	1. **Hate targets extracted from the tweet text**: Groups of people extracted from the tweet text who are the subject of hate in the tweet. E.g., for a hypothetical tweet "I strongly hate/dislike black people", "black people" is the hate target.

	1. **Hate categories assigned by us**: We manually labeled each hate_target into one of our hate categories and put the manual label in this column. For a comprehensive list of the hate categories, check our paper.

## Description of Whisper data

1. Whisper is an anonymous social media site.

1. Our Whisper dataset including 7,604 posts are in the csv file **hatespeech_whisper_released_hypertext_2017.csv**
1. There are eight columns: 
	1. **Serial**: An incremental serial assigned to each post by us. 
	1. **text**:The user generated text of the post.
	1. **unix timestamp (milliseconds)**: time when the post was uploaded
	1. **whisper_assigned_categories**: Whisper automatically assigns categories to the text. This column contains a comma separated list of those categories for each post. A blank value means no category was assigned.
	1. **country**: Country from which the post was made. 
	1. **region**: Region (e.g., US state or city) from which the post was made. 
	1. **Hate targets extracted from the whisper text**: Groups of people extracted from the whisper text who are the subject of hate in the whisper. E.g., for a hypothetical whisper "I strongly hate/dislike black people", "black people" is the hate target.
	1. **Hate categories assigned by us**: We manually labeled each hate_target into one of our hate categories and put the manual label in this column. For a comprehensive list of the hate categories, check our paper.	


##### Release date: 7th March, 2019
##### authors: Mainack Mondal and Leandro A. A. Silva and Fabricio Benevenuto
