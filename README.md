# SecuringTagBasedRecSys
<p>
Code and Data associated with RecSys'18 paper:
<br>
<i>
<b>
Georgios Pitsilis, Heri Ramampiaro, and Helge Langseth. 2018. "Securing Tag-based recommender systems against profile injection attacks: A comparative study", In Proceedings of Late-Breaking Results track part of the Twelfth ACM Conference on Recommender Systems (RecSys’18) Vancouver, BC, Canada, October 2-7, 2018.
</b>
</i>
</p>

<p>
As far as the datasets is concerned, for the purpose of the experiment described in the above mentioned paper, we generated the following 5 sets, each one corresponding to an experiment run. Each set contains one pair of files.
</p>

Each delicious_over_train_X.csv file contains the bogus data generated to simulate the overload attack for the particular experiment run (where X is a number denoting the experiment run, and it ranges from 1 to 5). In the same way, every delicious_small_X.csv file contains the selected legitimate data used for the same experiment run.
Similarly, each delicious_piggy_train_X.csv file contains the bogus data generated to simulate the piggyback attack for the X experiment run.

Each delicious_nnnnn_train_X.csv file has size in terms of number of records that equals to the 30% of the size of the adjacent delicous_small_X.csv file. That is because, in the experiment we trained the classifiers with bogus and legitimate data taht were mixed with ratio 30/100.

<p>
The content in the data files is structured as follows:
<br>
<b>
product_ID &lt space &gt username &lt space &gt tag_1,tag_2,..., tag_n
</b>
</p>

The code used in the experiments described in the paper will be published soon.
