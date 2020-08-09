##***<u>Lesson 13: Combination of Variables</u>***

###**Objective:**
Students will learn that we can make better predictions by including more variables. Then they will wrestle
with how the information should be combined.

###**Materials:**
1. *Advertising Plots Part 2* handout ([LMR_4.13_Advertising Plots 2](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 4_v_5.0/LMR_4.13_Advertising Plots 2.pdf)) from [Lesson 12](lesson12.md)

###**Essential Concepts:**

!!! note "Essential Concepts: " 
    If multiple predictors are associated with the response variable, a better predictive model
    will be produced, as measured by the mean absolute error.

###**Lesson:**
1. Display the plots and statements from the previous day:

    <img src="../../img/41212.png" />    

    <div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://stemc.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 4_v_5.0/LMR_4.13_Advertising Plots 2.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_4.13](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 4_v_5.0/LMR_4.13_Advertising Plots 2.pdf)</div>

    100. Combining multiple variables (e.g., money spent on TV and Newspaper ads, TV and
    Radio ads, TV, Radio, and Newspaper ads, etc.) into one model will lead to worse
    predictions because the variables that make poor predictions will contaminate those that
    make good predictions.

    100. Combining multiple variables (e.g., TV and Newspaper ads, TV and Radio ads, TV,
    Radio, and Newspaper ads, etc.) into one model will lead to better predictions because
    the model can use more information to make predictions.

2. Ask the students to share out their opinions in an Active Debate (see [Unit 2](../unit2/overview.md) [Lesson 6](lesson6.md) as an
example).

3. Next, inform teams that they will have 2 minutes to come up with as many combinations of ads
(variables) as they can think of (e.g., TV + Newspaper ads, TV+ Radio ads, TV + Radio +
Newspaper ads, etc.)

4. After 2 minutes, list all the different combinations by conducting a Whip Around and eliciting a
combination from each team.

5. By a show of hands, ask students to select which combination or single model will be the best
predictor for the number of items sold by the retailer.

6. Then inform students that we will determine which of the statements is true by comparing the
mean absolute error (MAE) of single models (like the ones we showed in the previous lesson) vs.
combined models. But first, use the line of best fit for the combined variables:

    <center><img src="https://latex.codecogs.com/gif.latex?\widehat{sales}=0.045449(tv)&plus;0.186570(radio)-0.004952(newspaper)&plus;3.029878" title="\widehat{sales}=0.045449(tv)+0.186570(radio)-0.004952(newspaper)+3.029878" /></center>

    **Note:** The function that produced the line of best fit using RStudio was

    lm(Sales ~ TV + Radio + Newspaper, data= retail)

    100. Use this equation to predict the amount of sales for the same market they circled in the
    previous lesson. <span style="color:grey">***Students’ calculation should yield the predicted value in (b), below.***</span>
    
        **<u>Note:</u>** Remind students that they need to substitute the values as they appear in the x-axis
        of the plots without converting to thousands of dollars. For example, the circled
        market spent about 10 thousand dollars on newspaper ads, so students should substitute
        10 instead of the expanded value in the equation.

        <img src="../../img/41210.png" />

    100. Does the predicted value (10.407)) seem like a plausible number of sales? Why? <span style="color:grey">***It is not
    a plausible number of sales because the prediction is too high. The prediction says
    the retailer will sell about 104,070 units, when the actual sales were about 16,000
    units. Although the model did not make a very good prediction for this market, it is
    not surprising because as [LMR_4.13](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 4_v_5.0/LMR_4.13_Advertising Plots 2.pdf) displays, that market did not fit the overall
    pattern in any of the scatterplots.***</span>

7. Reveal that RStudio calculated the mean absolute error for different combinations plus the single
models, and the results are displayed on the table below. This means that, for example, when
using the TV model to predict number of items sold, our predictions will typically be off by about
2.337808 (in 10,000s) of units or 23,378 units. Then ask students:

    | Model | Mean Absolute Error |
    |--------------------|---------------------|
    | TV | 2.337808 |
    | Radio | 3.565113 |
    | Newspaper | 4.538444 |
    | TV-Radio | 1.160937 |
    | TV-Newspaper | 2.344971 |
    | Radio-Newspaper | 2.93832 |
    | TV-Radio-Newspaper | 1.161068 |

    100. Which model is the best predictor of number of items sold? <span style="color:grey">***Answer: The TV-Radio
    model is the best predictor of number of items sold because it had the least
    amount of error, on average. When using the TV-Radio model to predict number of
    items sold, our predictions will typically be off by 11,609 units.***</span>

    100. Which model was the least reliable in predicting the number of items sold? <span style="color:grey">***Answer: The
    Newspaper model is the least reliable predictor of number of items sold because it
    had the most amount of error, on average. When using the Newspaper model to
    predict number of items sold, our predictions will typically be off by 45,384 units.***</span>

    100. What else do you notice about the models? <span style="color:grey">***Answer: It appears that combining the
    variables into one model is much better than any of the single-variable models.***</span>

8. Inform the students that, in the next lab, they will find out how to create the line of best fit for
models that include many variables.

###**Class Scribes:**
One team of students will give a brief talk to discuss what they think the 3 most important topics of the
day were.

###<p style="background: black; color: white; text-align: center;">**Homework & Next Day**</p>
Ask students to think of a reason or reasons about why it would not be a good idea to make a scatterplot
for models that include more than 3 predictor variables? <span style="color:grey">***The answer is mainly because humans are
limited to seeing things in 3 dimensions. For example, the model that combines all of the variables
together is a 4 dimensional model. What does that look like?***</span>

[<u>***LAB 4E: This Model is Big Enough for All of Us***</u>](lab4e.md)

Complete [Lab 4E](lab4e.md) prior to [Practicum](practicum1.md).