# Training #
## Training and Test dataset, Cross Validation ## 
To mesaure the performence of an algorithm on the problem that is trying to be solved. The algotithm needs to be tested. The easiest way to test is to have a training dataset and a dataset that is used for testing. The first dataset will how the algorithm is trained. what it uses to find relacthips within the dataset. These will then be vaildated against the dataset set. Compareing the output from the algorithm against the actul results shows how acruete the algorithm is. 
	spliting up a dataset 70/30 with 30% being used for testing is a popular way to traing datasets. keeping 30% aside ensures that the training is not comprmised by being exposed to the soloution it trying to solve.
Cross validation is another method used to train an algorithm. In this method rather doing a random cut of 70/30 or 80/20 in the dataset. the whole dataset is used to for both training and testing. First the dataset is cut up into equal sized chunkscalled folds. the model is then trainied on all but one fold, the fold not used then has the model tested against it. once complete the fold not used for training will be put back into the training folds and another fold is taking out to be used as the test fold. Typical folds of 3, 5, 7 and 10 will be used but it will vary depending on the size of the dataset in use. 


---------------
|train | test |
| 1 + 2 | 3 |
| 1 + 3 | 2 |
| 2 + 3 | 1 |
-------------



# supervisted and unsupervisted  #

In supervisted learning the dataset being used to train the model will be labeled with the outcomes expected. This allows the model to be reviewed to see how acureate it is. while unsuperviited learning will not have the outcomes expected in the dataset. This makes it much more diffiecult to review. there isn't a better one to use as they both how be used for different reasons.  
	Supervisted leaning can be split up into to catagorys classification and Regression. Classification as the name may suggest is used for problems where the output can be put in a catagory. Classification is normally used to solved problems where the data needs to be sorted into groups that manually may not be possiable to do quickly. Consider a hosiptal with a number of pataints. Using data from previous cases a model could learn how to group each pataint based of how severe there issue is. 
Regression is used to predict what the value outcome will be. In the serinco the model is being trained to give a prediction on future outcomes such as house prices in a location or crop yields for next season. 
	In Unsupervisted learning  the outcome isn't know before so a model can't be trained to give the outcome of and event with any great degree of acturcy. Instead unsuperviited learning is used to find assictione or clusers in a dataset which otherwise wouldn't have been noticed. 
	Assictione is often used to spot trends within data. This is often used in retail where a store will be able to see what products simllar customers bought and target them with items. 
	clustering is finding the groups within data that are the same. This may involve see what data is closer to each other and grouping that together. This can be diffcult to train as it isn't know before how many groups there are or what each group will be. What may seem like a small change in the model could change the outcome dramctly and data that previouly looked sorted is now complete wrong.  
