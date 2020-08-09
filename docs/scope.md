#Scope and Sequence

##**<u>Unit 1</u>**
This unit will introduce the idea of “data,” fundamental to the rest of the course. While most people think
of data simply as a spreadsheet or a table of numbers, almost anything can be considered data, including
images, text, GPS coordinates, and much more. Our world has become increasingly data-centric, and we
are constantly generating data, whether we know it or not. From posts on Facebook, to shopping records
created when you swipe your credit card, to driving over sensors embedded in highway on-ramps, we
leave behind a stream of data wherever we go. These data are used to generate stories about our world,
whether it is for political forecasting, marketing, scientific research, or even Netflix recommendations.
Traditional statistics courses consist of understanding data from only a small subset of data generation
processes, namely those collected through random sampling or random assignment in scientific
experiments. This unit exposes students to a wider world of data, and will help students see how to make
sense of these ubiquitous data types.

This unit will motivate the idea that data and data products (charts, graphs, statistics) can be analyzed
and evaluated just like other arguments, such as those used by journalists. We want to know how the
evidence was collected, what the perspective or bias of the creator might be, and look behind the scenes
to the process used to create the product. Even the way data are represented embeds within it decisions
on the part of the data creator.

Using the techniques of descriptive statistics, students will begin learning how to construct multiple views
of data in an attempt to uncover new insights about the world. This will require the introduction of the
computational tool R through the interface of RStudio. Standard graphical displays like histograms and
scatterplots will be introduced in RStudio, as well as measures of center and spread.

###**<u>Focus Statistics CCSS-M</u>**
S-ID 1. Represent data with plots on the real number line (dotplots, histograms, and boxplots).

S-ID 2: Use statistics appropriate to the shape of the data distribution to compare center (median,
mean) of two or more different data sets (measures of spread will be studied in Unit 2).

S-ID 3: Interpret differences in shape, center, and spread in the context of the data sets,
accounting for possible effects of extreme data points (outliers).

S-ID 5. Summarize categorical data for two categories in two-way frequency tables. Interpret
relative frequencies in the context of the data (joint, marginal, and conditional relative
frequencies). Recognize possible associations and trends in the data.

S-ID 6. Represent data on two quantitative variables on a scatterplot, and describe how the
variables are related.

S-IC 6. Evaluate reports based on data.\*
\*This standard is woven throughout the course. It is a recurring standard for every unit.

###**<u>Focus Standards for Mathematical Practices</u>**

SMP-3. Construct viable arguments and critique the reasoning of others.

SMP-5. Use appropriate tools strategically.

###<u>Upon completion of Unit 1, students will be able to:</u>

* Give examples of where they leave data traces.

* Understand that rows and columns are a form of data structure.

* Explain why the relationship between the variables might exist, or, if there is no relationship, why
that might be so.

* Construct and interpret a frequency table.

* Critically read reports from media sources to evaluate their claims.

* Read plots (identify the name of the plot, interpret the axes, look for trends, identify confounding
factors).

* Calculate conditional and marginal probabilities using frequency tables.

* Provide a real-world explanation for why the conditional or independent probabilities make sense,
using critical thinking skills and background knowledge.

* Communicate their evaluations in written or verbal form using different types of media.

* Load data into RStudio.

* Create basic plots in RStudio.

* Create frequency tables in RStudio.

##**<u>Unit 2</u>**
This unit deepens the informal reasoning skills developed in Unit 1 by enriching students' technical
vocabulary and developing more precise analytical tools. Most importantly, this unit introduces the formal
concept of probability as a tool for understanding that sometimes patterns observed in data are not "real."
Traditional courses attempt to develop this understanding through the development of abstract
mathematical probability concepts, but IDS creates enduring understanding by teaching students to
design and implement simulations using pseudo-random number generators. This activity also develops
computational thinking by teaching students about some basic programming structures. Then, the use of
models will come to the foreground. Students will be introduced to linear models - the most common form
of modeling in introductory statistics classes - which will serve as the foundation to learn more complex
modeling techniques that use the computer technology available to them later in the course, including
smoothing techniques and tree-based models.

###**<u>Focus Statistics CCSS-M</u>**
S-ID 2: Use statistics appropriate to the shape of the data distribution to compare center (median,
mean) and spread (interquartile range, standard deviation) of two or more different data
sets.

S-ID 3: Interpret differences in shape, center, and spread in the context of the data sets,
accounting for possible effects of extreme data points (outliers).

S-ID 4. Use the mean and standard deviation of a data set to fit it to a normal distribution and to
estimate population percentages. Understand that there are data sets for which such a
procedure is not appropriate. Use calculators, spreadsheets, and tables to estimate areas
under the normal curve.

S-IC 2. Decide if a specified model is consistent with results from a given data-generating
process, e.g., using simulation.

S-IC 6. Evaluate reports based on data.\*
\*This standard is woven throughout the course. It is a recurring standard for every unit.

S-CP 2. Understand that two events A and B are independent if the probability of A and B
occurring together is the product of their probabilities, and use this characterization to
determine if they are independent.

S-CP 9. (+) Use permutations to perform [informal] inference.
\*This standard will be addressed in the context of data science.

###**<u>Focus SMPs</u>**
SMP-4. Model with mathematics.

SMP-5. Use appropriate tools strategically.

###<u>Upon completion of Unit 2, students will be able to:</u>
* Create a boxplot by calculating the five-number summary, upper and lower fences, and
determining outliers.

* Explain what “standard deviation” means in context.

* Explain why the measures of central tendency and spread may or may not be accurate
descriptions of the data from which they came.

* Use permutations of data to solve problems.

* Read/interpret a normal curve/distribution.

* Explain where the normal distribution came from.

* Describe situations where the normal distribution may model the phenomena, and others where it
may not.

* Simulate normal distribution.

* Simulate from a model.

* Compare real data to simulation.

* Determine if model and data appear consistent.

* Merge data by columns/rows, and verify that merging is successful.

* Learn for() loops and apply() functions in RStudio.

* Create functions.

##**<u>Unit 3</u>**
Unit 3 focuses on data collection methods, including traditional methods of designed experiments and
observational studies and surveys. It introduces students to sampling error and bias, which cause
problems in analysis made from survey data. Participatory Sensing is presented as another method of
data collection, and students learn to design Participatory Sensing campaigns that will allow them to
address particular statistical questions. Participatory Sensing is a unique data collection method because
it uses sensors. Furthermore, this method emphasizes the involvement of citizens and community groups
in the process of sensing and documenting where they live, work, and play. Triggers play an important
role in the Participatory Sensing data collection process. The response to the triggers may or may not be
the same each time. Data takes on a variety of forms online and requires a different style of
representation. Students enhance computing skills by learning about modern data structures, and by
learning to "scrape" data stored in XML format.

###**<u>Focus Statistics CCSS-M</u>**
S-IC 1. Understand statistics as a process for making inferences about population parameters
based on a random sample from that population.

S-IC 3. Recognize the purposes of and differences among sample surveys, experiments, and
observational studies; explain how randomization relates to each.

S-IC 6. Evaluate reports based on data.\*
\*This standard is woven throughout the course. It is a recurring standard for every unit.

###**<u>Focus SMPs</u>**
SMP-1. Make sense of problems and persevere in solving them.

SMP-4. Model with mathematics.

SMP-8. Look for and express regularity in repeated reasoning.

###<u>Upon completion of Unit 3, students will be able to:</u>
* Provide a loose definition of “statistics” in their own words.

* Compare and contrast population vs. sample.

* Compare and contrast parameter vs. statistic.

* Explain the difference between special data structures, particularly as they relate to inference.

* Exploit special data structures for re-randomization analysis.

* Explain situations where one measure of central tendency or spread may be more appropriate than
others.

* Read/interpret boxplots (In-depth look into samples size and their relationship to the population
parameters).

* Identify reports that use special data structures (census, survey, observational study, and randomized
experiment).

* Do data scraping.

* Use HTML and XML formats.

* Use RStudio to re-randomize data.

* Compute measures of central tendency and spread in RStudio.

##**<u>Unit 4</u>**
This unit will develop modeling skills, beginning with learning to fit and interpret least squares regression
lines and learning to use regression to make predictions. Students will learn to evaluate the success of
these predictions and so compare models for their predictive accuracy. Modern algorithmic approaches to
regression are presented, and students will strengthen algorithmic thinking skills by understanding how
and why these algorithms help data scientists make accurate predictions from data. Students engage in a
complete modeling experience in which they apply the skills and concepts learned in the previous units.
The modeling experience is designed to make students’ thinking visible and audible by encouraging them
to be metacognitive about the process of inventing and testing a model, ask questions as they go through
the process, and recognize the iterative nature of modeling.

###**<u>Focus Statistics Standards</u>**
S-IC 2. Decide if a specified model is consistent with results from a given data-generating
process, e.g., using simulation.

S-ID 6. Represent data on two quantitative variables on a scatter plot, and describe how the
variables are related.

<ul style="list-style-type:none">
	<li>
    a. Fit a function to the data; use functions fitted to data to solve problems in the context
    of the data. <i>Use given functions or choose a function suggested by the context.
    Emphasize linear models.</i>
    </li>
	<li>
    b. Informally assess the fit of a function by plotting and analyzing residuals.
    </li>
	<li>
    c. Fit a linear function for a scatter plot that suggests a linear association.
    </li>
</ul>

S-ID 7. Interpret the slope (rate of change) and the intercept (constant term) of a linear model in
the context of the data.

S-ID 8. Compute (using technology) and interpret the correlation coefficient of a linear fit.

S-IC 6. Evaluate reports based on data.\*
\*This standard is woven throughout the course. It is a recurring standard for every unit.

###**<u>Focus SMPs</u>**
SMP-2. Reason abstractly and quantitatively.

SMP-4. Model with mathematics.

SMP-7. Look for and make use of structure.

###<u>Upon completion of Unit 4, students will be able to:</u>
* Describe how well the linear model fits the data (or does not).

* Provide a real-world explanation of why the model may or may not fit, using critical thinking skills and
background knowledge.

* Interpret the slope and intercept on a plot.

* Compute the correlation coefficient using RStudio.

* Interpret linear models in reports, including the correlation coefficient.

* Determine if a trend is “real” or if it could have arisen from randomness.

* Use critical thinking skills to explain why a trend may or may not make sense.

* Fit a regression line.

* Extract the slope, intercept, correlation coefficient, coefficient of determination, and residuals using
RStudio.

* Use RStudio to predict y given an x value.

* Explore what happens to the line and the response variable if we multiply (divide) or add (subtract) a
constant from the predictor.

* Design and execute their own Participatory Sensing Campaigns.

* Use RStudio to compute permutations and combinations.

* Create Classification and Regression Tree (CART) models.

* Understand non-linear models.

