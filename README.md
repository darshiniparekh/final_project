# final_project
#load the data
objective : loading dataset clean it for further tests 
this section loads the csv file in to dataframe , it converts 'Unspecified' in to NAs , fills missing values with mean and  categorizes ages into groups

##checking normality
objective:checking normality via visulizing age distrubution , alcohol consumption frequency and body mass index 
This section checks the normality of different variables by creating  histograms and Q-Q plot to visually assess the normality of age_years,alchohol  consumption and bmi. 
Q-Q plots line is very linear to the exis which suggests non normel distrubution of BMI , age distrubution is normally distrubuted 

###t test
Objective: Perform a t-test to compare mean ages between two alcohol consumption groups and visualize the results.
Hypothesis:
Null Hypothesis (H0): There is no difference in the mean age between groups who consume alcohol and those who do not.
Alternative Hypothesis (H1): There is a difference in the mean age between these two groups.
this section conducts t-test to see if there is difference  in mean age between alcohol-consuming and non-consuming groups are statistically significant.
t-test results indicate a statistically significant difference in the mean age between groups that consume alcohol and those that do not, with non-drinkers being younger on average than drinkers

####correlation test 
objective: Assess the relationship between age and and body mass index 
This section computes the Pearson correlation between age and BMI, providing a statistical measure of their linear relationship. The scatter plot with a regression line visually aids in understanding the nature of this relationship, highlighting trends or patterns.
correlation test results shows no significant correlation between age and BMI, indicating that age does not predict BMI in this dataset

#####anova test
Objective: Perform ANOVA to compare body mass index across multiple age groups 
Hypothesis:
Null Hypothesis (H0): body mass index means are the same across all age groups.
Alternative Hypothesis (H1): At least one age group has a different mean body mass index.
this section utilizes ANOVA to investigate if there are any significant differences in body mass index across various age categories
The ANOVA test on age grouped by categories suggests no significant variance in BMI across different age groups, leading us to retain the null hypothesis that age groups do not differ significantly in terms of BMI. 

######pcoa 
Objective: Conduct PCoA to explore microbial diversity
This section sets up an OTU table, integrates it with sample metadata into a phyloseq object, and computes Bray-Curtis distances. A PCoA is then performed to visualize differences in microbial communities across samples
The PCoA results simply illustrate the first two principal coordinates that summarize variations in a microbial community dataset grouped by.

ps: I have attch the screenshot of the commit to git but it was not apparing so had to do it with via upload , also I have used data provided on canvas and converted it in to csv file as it is bigger then 25 mb could not uplode it here , I have attch knetted file with all the results and code 
