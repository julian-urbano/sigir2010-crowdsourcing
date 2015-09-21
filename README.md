This archive contains the data gathered for the following paper:

 * J. Urbano, J. Morato, M. Marrero and D. Martín, "[Crowdsourcing Preference Judgments for Evaluation of Music Similarity Tasks](http://julian-urbano.info/wp-content/uploads/012-crowdsourcing-preference-judgments-evaluation-music-similarity-tasks.pdf)", *ACM SIGIR Workshop on Crowdsourcing for Search Evaluation*, 2010.

A [single ZIP file](https://github.com/julian-urbano/sigir2010-crowdsourcing/archive/master.zip) can be downloaded as well.

## Data

* `template/` HIT template (live version available [here](http://julian-urbano.github.io/sigir2010-crowdsourcing/template/)).
* `data/judgments.csv` all the information about the HITs submitted to Mechanical Turk. Some relevant columns are:
 * `Input.query` ID of the query.
 * `Input.docA` ID of the first variation.
 * `Input.docB` ID of the second variation.
 * `Input.time` time needed to listen to all three melodies.
 * `Answer.comment` the comment or suggestion, if any.
 * `Answer.bground` the musical background, if any.
 * `Answer.radio` which of the variations was selected: `a`, `b` or `s` (they are the same).
* `data/MTurk.qrel` the ground truth for all queries. The columns are the literal `MTurk`, the query ID, document ID and group number. 

## License

 * Databases and their contents are distributed under the terms of the [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).

When using this archive, please cite the above paper:

    @inproceedings{Urbano2010:crowdsourcing,
      author = {Urbano, Juli\'{a}n and Morato, Jorge and Marrero, M\'{o}nica and Mart\'{\i}n, Diego},
      booktitle = {ACM SIGIR Workshop on Crowdsourcing for Search Evaluation},
      pages = {9--16},
      title = {{Crowdsourcing Preference Judgments for Evaluation of Music Similarity Tasks}},
      year = {2010}
    }

The MP3 player used in the template is redistributed from [here](http://flash-mp3-player.net/players/).