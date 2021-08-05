MoreLikeThis is a dataset that describes whether two movies are good recommendations for each other, i.e., whether they are similar.

The ratings were crowdsourced by Samsung Research Poland as part of the experiment on feature selection in content-based recommender systems. The released dataset accounts for 30% of total collected ratings.

Please cite the corresponding paper if you make use of this dataset (bibtex):

	@inproceedings{Gawinecki2021what, 
		author = {Gawinecki, Maciej and Szmyd, Wojciech and Walas, Marcin and Żuchowicz, Urszula}, 
		title = {What makes a movie good recommendation? Feature selection for Content-Based Filtering}, 
		booktitle = {...}
		year = {...}
	}

The dataset consists of a file, [`ratings.tsv`](ratings.tsv), with the following columns (tab-separated):

* `movie_1`: title of a first movie
* `year_1`: release year of a first movie
* `movie_2`: title of a second movie
* `year_2`: release year of a second movie
* `rating`: OK, NOT_OK

The [`evaluation_set.tsv`](evaluation_set.tsv) file contains movies that were used as an input to recommender system for evaluation purposes.
Movie titles, and their release year are listed in tab-separated format, i.e.

* first column - title of a movie
* second column - release year

The [`sample_movie.json`](sample_movie.json) contains one entry of our Movies Dataset. The movie plot and summary sections come from [Wikipedia](https://en.wikipedia.org/wiki/Green_Book_(film)) and are redistributed under [Creative Commons Attribution-ShareAlike 3.0 Unported License](https://creativecommons.org/licenses/by-sa/3.0/legalcode).
