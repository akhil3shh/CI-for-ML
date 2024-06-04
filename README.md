The project aims to run CI pipelines automatically when push your Git commits and get quick results about your ML model.   

Imagine, you build a Docker file every time when you make changes in your ML model Python file, then send the results with plots and related information directly from the Python script. Github actions can do it and save a lot of time while improving your model.   

Every time you push your commits to your Github branch, a new Docker container with dependencies is being created. Then model training is starting-up, and finally delivering your results. All the workstream processes are defined in a special  Continuous Machine Learning (CML) YAML file.    
   
In this example, a simple Tensorflow Regression model is used and a simple graph made by matplotlib Python library is plotted.   

## Head towards any recent commit of this repository to check the results of this CI pipeline.  
