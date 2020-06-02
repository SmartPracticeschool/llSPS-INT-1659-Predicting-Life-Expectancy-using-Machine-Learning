# llSPS-INT-1659-Predicting-Life-Expectancy-using-Machine-Learning
Predicting Life Expectancy using Machine Learning

PROJECT SUMMARY:

Design a Regression model to predict life expectancy ratio of a given country based on some features provided such as year, 
GDP(gross domestic product), education, alcohol intake of people in the country, expenditure on healthcare system and some 
specific disease related deaths that happened in the country.

The required dataset is inside Life Expectancy data.csv file. Here I have used an Extra Tree Regression method to fit and 
predict the data. I have used Watson studio with machine learning instance for model building and deployment.

Important:-
These credentials are provided inside service credentials tabs of machine learning instance.
Path to get that:- Go To dashboard->Resource list->cloud Foundry services->machine learning ** ->service credentials->copy and paste
wml_credentials={
  "apikey": "********************",
  "instance_id": "********************",
  "url": "https://eu-gb.ml.cloud.ibm.com"
}

You can copy and paste the details of flows.json or simply download and import in your node-red app.

For webpage: https://node-red-mzmya.eu-gb.mybluemix.net/ui/#!/0?socketid=-4Q_qIerFXMQst8eAAAe
