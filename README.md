# Modern-Optimization-For-Feature-Selection
Used NSGA-II and Genetic Algorithms for feature selection

In this project, I decided to take the approach in using NSGA-II and a Genetic Algorithm to perform feature selection. I used the telco customer churn data from IBM Sample Data Sets. 

I started off creating a simple ML model using Gradient Boosting Machine and a Random Forest. GBM and Random Forest both achieved 83% accuracy, Random Forest had a slightly higher accuracy. this consisted of using all 20 variables in the dataset.

To implement the Genetic Algorithm and NSGA-II. I created dummy variables that split every feature into having its own column. e.g. a column for yes and a column for no. 

The Genetic Algorithm proposed using only 8 variables, The accuracy rate for both algorithms using the new proposed feature set was 77%. A slight decrease from using all 20 variables. 

The NSGA-II however performed very well, using 15 variables the accuracy rate of the Random forest increased to 85%. GBM achieved 83% using only 16 variables. 


