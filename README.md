MoreLikeThis is a dataset that describes whether two movies are good recommendations for each other, i.e., whether they are similar.

The ratings were crowdsourced by Samsung Research Poland as part of the experiment on feature selection in content-based recommender systems. The released dataset accounts for 30% of total collected ratings.

Please cite the corresponding paper if you make use of this dataset (bibtex):

	@inproceedings{Gawinecki2021what, 
		author = {Gawinecki, Maciej and Szmyd, Wojciech and Walas, Marcin and Żuchowicz, Urszula}, 
		title = {What makes a movie good recommendation? Feature selection for Content-Based Filtering}, 
		booktitle = {...}
		year = {...}
	}

The dataset consists of a single file, `ratings.tsv`, with the following columns (tab-separated):

* `movie_1`: title of a first movie
* `year_1`: release year of a first movie
* `movie_2`: title of a second movie
* `year_2`: release year of a second movie
* `rating`: OK, NOT_OK
	
	
