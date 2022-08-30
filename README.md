# Neural_Network_Charity_Analysis

1.	Overview of the analysis: The purpose of the analysis is to determine the success different organizations who receive funding from Alphebet Soup will have in order to help with investment choices. 
2.	Results: 
o	Data Preprocessing
	Is successful was the targeted column of this analysis. This indicated that the prediction was on target.  
	All columns aside from the targeted one
	EIN and name were dropped from the analysis due to the lack of impact they would have on the results. 
o	Compiling, Training, and Evaluating the Model
	This model had two hidden layers and 80 neurons and utilized a relu model for activation.
	The model unfortunately failed to reach the targeted goal. 
268/268 - 0s - loss: 0.6976 - accuracy: 0.6964 - 228ms/epoch - 852us/step
Loss: 0.6976160407066345, Accuracy: 0.6964431405067444
	What steps did you take to try and increase model performance?
The output shape was changed in this test sample; however, the accuracy went down but the speed was increased. More layers were added along with an increase in parameter number parameters. 
268/268 - 0s - loss: 0.6853 - accuracy: 0.5335 - 214ms/epoch - 799us/step
Loss: 0.6853068470954895, Accuracy: 0.533527672290802

The activation function was changed which resulted in the speed increasing, but a significant decrease in accuracy. 

268/268 - 0s - loss: 5.1897 - accuracy: 0.4707 - 210ms/epoch - 785us/step
Loss: 5.189687252044678, Accuracy: 0.47067055106163025

3.	Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
Based on the above results demonstrate that the activation model can change the overall results of the model. While improving speed as well you also run the risk of losing accuracy in results. This also helped to demonstrate the power of the relu model, because it resulted in the highest accuracy. 
