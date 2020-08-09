##***<u>End of Unit Design Project and Oral Presentation: Water Usage</u>***

###**Objective:**
Students will apply their learning of the third and fourth units of the curriculum by completing an end of
unit design project.

###**Materials:**
1. Computers

2. *IDS Unit 4 – Project and Oral Presentation* ([LMR_U4_Design Project](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 4_v_5.0/LMR_U4_Design Project.pdf))

<center>**End of Unit 4 Project and Oral Presentation: Water Usage**</center>

At the beginning of this unit, you explored a 2010 data set from the Los Angeles Department of Water and
Power (DWP). You also created a Participatory Sensing campaign to investigate water usage around
your community.

For this assignment, you will use both data sets to apply what you have learned in [unit 4](../unit4/overview.md) and to answer
the research question from the beginning of the unit:

**How can we help city officials use Participatory Sensing to find out how water is being used
around your neighborhood?**

Your assignment is as follows:

1. You and a partner will predict water usage for the moth of June using a subset of the dwp_2010
data set, which is called dwp_student.

    * Load the dwp_student data set.

    * Using this data, create two data sets: training and testing. Name these data sets
    student_train and student_test.

    * Create the best prediction model that you can based on your training data. Remember to
    set.seed(123) when creating your own training and testing data.

    * You’re building this model with data from July 2010 to May 2011. You will use your model
    to predict water usage for June 2011.

    * After you settle on a specific model, submit your model (code) to your teacher. If you
    created any new variables, submit the code you used to create them as well.

    * ***What do the variables included in your prediction model say about how Angelenos
    use water?***

    * You will evaluate the prediction accuracy based on a separate set of data. Your teacher
    will give you another data set. Use this data set to evaluate your prediction. The pair with
    the smallest prediction error based on mean squared error (MSE), is the winner.

2. Using your Participatory Sensing data, explain how water is being used in your neighborhood.
Make sure you use evidence from your PS data analysis. Be sure to answer the research
question and your statistical questions.

Create a 5-minute presentation comprising 4 to 5 slides that explains your model, the predicted value for
June 2011 water consumption, and the findings using your campaign data. Be sure to include detailed
explanation of how you and your partner decided to create your prediction model, and how it performed
on the test data set your teacher provided in your presentation. Each person must participate in the
presentation. In addition to the presentation, submit a 2-4 page, double-spaced summary of your analysis
including plots/graphs.

**<u>Note to teacher about the testing data set:</u>** The data set you will provide for students to test their
prediction models is called **dwp_teacher**. It is recommended that you provide the data set’s name upon
students’ submission of the code for their prediction models.