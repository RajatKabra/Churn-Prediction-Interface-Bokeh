# Churn-Prediction-Interface-Bokeh

Churn

In the code, change the file location in line 47 and line 101 and the code should be working. There is no other change required in the entire code.

Execution Instrutions:
1. From anaconda prompt or cmd, go to the folde and run 
bokeh serve --show code.py

This should run the code and it will open in browser.


Features:
Its a machine learning model in which I have used random forest.
The interface would give user option to tune the machine learning model by changing the model's maximum depth, test size, the features used by model and the criterion.  The changes made would be reflected in the graph.
When hovered over any of the bar, it would give an exact count of the bar.
The model could be scrolled, panned, zoomed (box zoom or wheen zoom) from the widgets given on the side. A few widgets are not in working state.
All of the functionality related to graph can be achieved using the widget bar.
I have also introduced a play button which when clicked will run a loop which will test the model using depth 1-50 in a loop untill and unless the user clicks the pause button. The user can change the test size during this play.
The accuracy of the mode, is displayed at the  top of the graph.
when not using the play button, please use the submit parameter button to run any changes made to the parameters.
Model is really useful for students who want to learn how the parameter tuning can affect the machine learning model.

The model has all the basic and advanced functionality and uses design patterns discussed in class. Please let me know if you face any issues with the code or with output. I would try to resolve the problem or will give you a demo on my own laptop.


References:
https://github.com/bokeh
