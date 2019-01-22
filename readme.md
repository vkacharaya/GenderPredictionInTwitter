# Gender Prediction In Twitter

Social Media Platforms tries to complete user registration as fast as possible. This might be a boon to the users but not for companies who needs to target people for marketing and advertising based on Gender. In this project, we have used character-based n-gram for usernames along with word-based n-gram for description as well as tweets to train the model. We have also utilized favorites, retweet count, side bar colors and link colors for determining gender. We achieved an accuracy of 72.68% after ensembling using majority votes technique. 

*****************************************************************************************************************

Please change "test_file_ds" and "is_test " value to the test data set which will be imported in the format as 

	test_file_ds = pd.read_csv("file_path", encoding = "latin-1" )

 	is_test = True

in CELL 2 in the notebook file

*****************************************************************************************************************
and revert back "is_test = False" and "test_file_ds = None" for normal execution
