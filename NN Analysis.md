NN Analysis

Overview of the analysis: Explain the purpose of this analysis.
I attempted 3 neural network models and even more chnages were made in my binning to try to optimize my models perfomance. 
I binned: Name, application type and classification type. In the first 2 attempts I only used application type and classification type as EIN and Name had been dropped from the df. In my thrid attempt I kept the name and using value counts I adjusted the cutoff multiple times to find a number that showed how many application pername, I tried, 10, 20, 30 and finally 50. 

Results: Using bulleted lists and images to support your answers, address the following questions:

Data Preprocessing

What variable(s) are the target(s) for your model?
My target variable is the "IS_SUCCESSFUL" column because we weant to predict what charity loans were successful.  

What variable(s) are the features for your model?
I have split the data into test and train features so that I can train and test my models accuracy. 

What variable(s) should be removed from the input data because they are neither targets nor features?
Initially I dropped EIN and NAME, however for my thirs optimization attempt I included the name as some places had multiple apllications and I was taught that your name matters, individuls might have a hard time getting a grant but if you have a successful reputation you will have an easier time getting a grant. 

Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
I started with 3 hidden layers and I kept my activiation functions consistent through all 3 iterations of my code. For my second attemt I added another hidden layer and adjusted the nodes. I added my fourth layer because I wanted to try to get to the optimized accuracy number. 

Were you able to achieve the target model performance?
On my thrid code attempt I did achieve optimization. However to do it I adjusted my binning many times. When I chose to keep the name column, I had to rebin my data multiple times, first I tried a cutoff of 10, then I tried 20 which did get to the target model perfomance but I was curious and so I tried a cutoff of 30 and 50, both of these imporved the perfomance although not a huge difference so stopping at a cutoff of 30 probabaly would have been sufficient. 

What steps did you take in your attempts to increase model performance? I added more layers, adjusted node numbers, and finally adjusted my binning. 
Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

If I were going to attempt another model I might try the Amazon Sage Maker model because it is built to streamline the process of traning models.  