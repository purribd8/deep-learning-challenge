# deep-learning-challenge

For this part of the assignment, you’ll write a report on the performance of the deep learning model you created for Alphabet Soup.

The report should contain the following:

--- Overview of the analysis: Explain the purpose of this analysis. ---

The purpose of this analysis to build a neural network that can predict if  applicants will be successful if funded by Alphabet Soup


Results: Using bulleted lists to support your answers, address the following questions:

Data Preprocessing

--- What variable(s) are the target(s) for your model? ---

There is only one target variable which is IS_Sucessful. This will show if applicants are predicted to be successful if funded.

--- What variable(s) are the features for your model? ---

Feature variables consist of application type, affiliation, classification, use case, organization, income amount, special considerations, and ask amount

--- What variable(s) should be removed from the input data because they are neither targets nor features? ---
EIN number, status

Compiling, Training, and Evaluating the Model

--- How many neurons, layers, and activation functions did you select for your neural network model, and why? ---

For the input layer 8 neurons to cover the amount of features and 1 outer layer as that is all that is needed for this kind of data. Layers were changed around to test what combinations might be best.

--- Were you able to achieve the target model performance? ---

No

--- What steps did you take in your attempts to increase model performance? ---

Many steps were taken. The changing of bins bout increasing the amount of bins and decreasing them to see model reaction. Initally I also tried adding the NAME column however this proved to much data to be processed and would crash each time I tried to run it. I also increased and decreased the amount of neurons per layer and also the number of layers as well. Epochs were also increased and decreased. I tried 30,40,50, 100, 200, and 500 epochs

--- Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.---

Overall result showed the models having similar accuracies even when trying to opptimize. There were 2 attempts that I did that yielded over 60% in accuracy. Both included times where binning was done but also minimally. I believe that allowed the model to have more data available to make stronger predictions. Also increasing the epoch to 200 seemed to be most effective as that yielded the best accuracy compared to all other attempts at about 65 percent. Any epoch I selected over or under 200 generally came back with around 52 percent accuracy. 
