Assignment 21 Report

Analysis Overview: Elaborate on the purpose of this analysis.

Results: Utilizing lists and visuals to support your responses, address the following inquiries:

Data Preparation

Which variables serve as the target(s) for your model?
The target variable corresponds to the 'IS_SUCCESSFUL' column in application_df.
Which variables function as the features for your model?
The feature variables encompass all columns in application_df, excluding the 'IS_SUCCESSFUL' column.
Which variables should be eliminated from the input data because they neither serve as targets nor features?
The 'EIN' and 'NAME' columns were discarded as they do not serve as targets or features in the dataset.

Model Compilation, Training, and Evaluation

How many neurons, layers, and activation functions were chosen for your neural network model, and why?
In the initial attempt, I used 8 hidden nodes for layer 1 and 5 for layer 2. These selections were arbitrary and intended for subsequent refinement.
Were you able to achieve the desired model performance?
I did not attain the target model accuracy of 75%.
What strategies did you employ in your efforts to enhance model performance?
I incorporated additional layers, removed more columns, added extra hidden nodes, and experimented with different activation functions in an endeavor to improve model accuracy.

Summary: Recapitulate the overall outcomes of the deep learning model. Offer a recommendation on how a different model could address this classification problem, and elucidate your suggestion.

In summary, the deep learning model achieved an accuracy of approximately 73% in predicting the classification problem. Employing a model with stronger alignment between input and output variables is likely to lead to higher predictive accuracy. This might involve conducting more comprehensive data cleaning at the outset and experimenting with various activation functions, iterating until improved accuracy is attained.
 
