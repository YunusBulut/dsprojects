# Categorize each of the variables in the ESS dataset as categorical or continuous, and if continuous as ordinal, interval, or ratio variables. Check your work with your mentor, and discuss what that information might imply for feature engineering with this data.

* Country: Categorical  
* Year: Categorical  
* ID: Categorical
* Total time watching TV avg weekday: Continuous Ratio    
* ppltrust, pplfair, pplhelp, happy: There seems to be some debate over whether these types of survey questions can be considered continuous. After review I would consider them categorical because I don't necessarily believe the average person would view a happiness score of 6 to be "twice as happy" as a happiness score of 3, and I don't think the distances between ratings are objectively comparable.  
* sclmeet  rating: Categorical  
* Gender: Categorical
* Agea: Continuous Ratio
* Partner: Categorical
