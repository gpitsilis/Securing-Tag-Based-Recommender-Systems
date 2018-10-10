# SecuringTagBasedRecSys
Code and Data associated with RecSys'18 paper:

<i>
<b>
Georgios Pitsilis, Heri Ramampiaro, and Helge Langseth. 2018. "Securing Tag-based recommender systems against profile injection attacks: A comparative study", In Proceedings of Late-Breaking Results track part of the Twelfth ACM Conference on Recommender Systems (RecSys’18) Vancouver, BC, Canada, October 2-7, 2018.
</b>
</i>

<p>
As far as the datasets is concerned, for the purpose of the experiment described in the above mentioned paper, we generated the following 5 sets, each one corresponding to an experiment run. Each set contains one pair of files.

Each delicious_train_X.csv file contains the bogus data generated for the particular experiment run (where X is a number denoting the experiment run, and it ranges from 1 to 5). In the same way, every delicious_small_X.csv file contains the selected legitimate data used for the same experiment run.
The number of records in every delicious_train_X.csv file is the 30% of the number of records of the adjucent delicous_small_X.csv file. That is because we chose to train the classifiers with 30% bogus data, over the original legitimate data.


The structure of the files:


The code will published soon.
