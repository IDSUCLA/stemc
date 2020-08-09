##***<u>Lesson 10: We’re So Random</u>***

###**Objective:**
Students will learn how to collect random samples from a population in order to estimate a parameter.

###**Materials:**
1. *Populations & Samples* handout ([LMR_3.5_Populations and Samples](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.5_Populations and Samples.pdf))

2. RStudio

3. Projector for RStudio functions

4. Dotplot titled “Percent of Students Who Have Met Friends Online”

5. *Parameters & Statistics* handout ([LMR_3.6_Parameters and Statistics](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.6_Parameters and Statistics.pdf))

###**Vocabulary:**
population, sample, representative, random sample, parameter, statistic

###**Essential Concepts:**

!!! note "Essential Concepts: "
    Another popular data collection method involves collecting data from a random
    sample of people or objects. Percentages based on random samples tend to ‘center’ on the population
    parameter value.

###**Lesson:**

1. Introduce today’s lesson by displaying the following statement made by the Pew Research Center
in their August 2015 report titled *Teens, Technology & Friendships*:

    “For today’s teens, friendships can start digitally: 57% of teens have met new friends
    online. The margin of error is plus or minus 3.7 percentage points. Social media and
    online gameplay are the most common digital venues for meeting friends.”

    **<u>Note:</u>** The data for this report were collected via interviews of 1,060 teenagers between the ages
    of 13 and 17.

2. Discuss the results of the Pew poll with the following prompting questions:

    100. The report says that 57% of teens have met new friends online. Since the report was
    based on a sample of 1,060 teens, how many of the teens reported that they have met
    friends online? <span style="color:grey">***0.57(1060) = 604.2. This means that approximately 604 teens in the
    sample have met friends online.***</span>

    100. Do you think 57% of students in our class have met friends online? Why or why not?
    <span style="color:grey">***Answers will vary by class. The discussion should include points about how
    similar and different samples can be. The sample of students in the Pew poll may
    not represent the students in our class.***</span>

    100. What percent of students in our class have met friends online while a teenager?
    <span style="color:grey">***Answers will vary by class. Calculate the percentage by dividing the number of
    students who have met friends online by the total number of students who came to
    class today.***</span>

    100. What if [absent person] were in class today? Would that change our percentage? What
    effect would it have on the percentage if [absent person] answered “yes?” What effect
    would it have if [absent person] answered “no?” <span style="color:grey">***Answers will vary by class. If a
    student who was absent for today’s lesson had actually come to class, we would
    have a different sample of students. It would change the percentage because our
    sample size now includes 1 more person. If the person answered “yes,” the values
    in the numerator and denominator of the percentage would change. If the person
    answered “no,” the value in the denominator would change. (Students should
    calculate these values.)***</span>
    
    100. If we were able to interview every single teenager in the United States, would exactly
    57% of them say they have met friends online? <span style="color:grey">***Probably not because there are many
    more teenagers in the US than the 1,060 they interviewed. It would be unlikely for a
    group of 1,060 teenagers to exactly represent all teenagers in the entire country.***</span>
    
    100. Why do you think the Pew Research Center only interviewed 1,060 teenagers, and not all
    teenagers in the US? <span style="color:grey">***It would be impossible to talk to all teenagers in the US in a
    short period of time, or even a fairly long period of time.***</span>

3. Introduce students to the terms **population** and **sample**. Explain that a population consists of all
of the people we want to learn something about. A sample consists of people (or objects) that are
selected *from* the population. In pairs, ask students to discuss and record answers to the
following two questions:

    100. What was the population of interest to the researchers for the Pew poll above? <span style="color:grey">***All
    teenagers in the US right now.***</span>

    100. Based on your answer in (a), what characteristics should people have in order to be
    included in a sample for this poll? <span style="color:grey">***People would need to be in the US and be between
    the ages of 13 and 17. People could be from many states, but we would not want to
    sample only people from California, or only people from Los Angeles. It would be
    impossible to survey every single person in the US; this is why we create a random***</span>
    **representative** <span style="color:grey">***sample of the population.***</span>

    **<u>Note:</u>** Steer the discussion so that students see that a sample has to be “like” or “similar to” or
    “representative of” the population.

4. Select pairs to share their responses to the questions and let students revise their responses.

5. Distribute the *Populations & Samples* handout ([LMR_3.5](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.5_Populations and Samples.pdf)), which contains survey results from
other Pew Research Center reports. Give students time to determine the population and sample
for each scenario, and then have them verify their results with a partner.
<div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://stemc.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.5_Populations and Samples.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_3.5](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.5_Populations and Samples.pdf)</div>

6. State that we want to know the percentage of students in our class that have made friends online,
but we don’t want to ask every single student. Instead, we would like to ask only 10 students and
then make some guesses about our class from those 10. Ask:

    100. What is the population of interest? <span style="color:grey">***The students in our classroom.***</span>

    100. How can we select 10 students to be part of our sample? <span style="color:grey">***Answers will vary by class.
    There may be a variety of suggestions; here are some examples of what may be
    given: (1) put every student’s name in a hat and pick out 10; (2) select the 10
    students sitting closest to the teacher’s desk; (3) have 10 students volunteer to be
    in the sample.***</span>

7. Inform students that, in general, we want samples to “look like” the population. One way to get a
representative sample like this is to take a **random sample**. Ask the students:

    100. Would the selection techniques we came up with in Step 6 result in random samples of
    our class. <span style="color:grey">***Answers will vary by class. Using the examples from Step 6: (1) putting
    each student’s name in a hat and then picking out 10 would be a random sample
    as long as each piece of paper is the same size; (2) selecting the 10 students
    sitting closest to the teacher’s desk would not be a random sample because those
    students might not represent the whole class; (3) if 10 students volunteer, we
    would not have a random sample because those students selected themselves to
    be part of the group and may not represent everyone in the class.***</span>

8. Next, assign each student in the class a number by having them count off from 1 to *N* (*N* being
the total number of students in the class). Show students that we can use RStudio to create
random samples with the following function:

    **> sample(1:N, size = 10, replace = FALSE)**

    **<u>Note:</u>** we use **replace = FALSE** because we only want each student to be selected once.

9. Using the results given in the output of RStudio, ask the students whose numbers were chosen to
stand. Inform them that they are “in” the sample. Then, determine what percent of the sample
(these 10 students) have made friends online. How does this percentage compare to the overall
class percentage we found in Step 2(c)? <span style="color:grey">***Answers will vary by class.***</span>

10. Create a dotplot on the board titled “Percent of Students Who Have Met Friends Online.” Record
the sample percentage from Step 8 on this dotplot.

11. Have the students return to their seats so that we can select a new sample. Before we do this,
ask:

    100. What do you predict the percentage to be for the next sample of 10 students? <span style="color:grey">***Answers
    will vary by class. They might say the expected percentage will be close to the
    class’s overall percentage.***</span>

12. Using RStudio, create a new sample, calculate the percentage of those 10 students who have
met friends online, and record the value in the dotplot.

13. Repeat Step 11 for a few more rounds (at least 5 samples should be taken). Be sure that the
students give a prediction before finding each new sample.

14. Display the following questions. Refer to the dotplot of sample percentages. Ask students to
discuss the questions in teams:

    100. What do you notice about the sample percentages? What is the “typical” value? <span style="color:grey">***Answers
    will vary by class. The typical value should be close to the class’s overall percent
    calculated in Step 2(c) since it is the population percent.***</span>

    100. What is the smallest value? What is the biggest value? <span style="color:grey">***Answers will vary by class.
    There might be a lot of variability in the dotplot based on the selected samples.
    Most sample percentages will be within 30% of the population value, so that really
    gives a wide variety of possible sample values.***</span>

    100. If we took a larger sample – maybe of size 15 or 20 – would there be more or less
    variability in the dotplot? <span style="color:grey">***There will be less variability because adding more people
    gets us closer to the population size. Be sure to point out that if the sample were
    exactly the same as the population, then there would be no variability in the plot.***</span>

15. Select teams at random to share their responses to the questions above with the whole class.
The rest of the teams should be in full agreement with the responses before moving on to the
next question.

16. Explain that the population percentage (the percentage of all students in the class who met
friends online) we have been using is called a **parameter**. A parameter is any number that
summarizes a population. So, our class has been the population, and the percentage of students
that have met friends online is the parameter.

17. Similarly, the term **statistics** is used for numbers that summarize a sample. Ask students what
sample statistics they have seen today? <span style="color:grey">***Each value we included in the dotplot is a statistic.***</span>

18. Be sure to point out that there can be multiple values for a sample statistic (i.e. “We had 5 sample
percentages in our dotplot.”), but there is always only one parameter value.

19. Using these new definitions, ask students to consider the original Pew poll data, which found that
57% of teens have met friends online. Ask the students:

    100. Is 57% a parameter or statistic? <span style="color:grey">***This is a statistic because it is based on a sample.
    Remind them that the population was ALL US teenagers and the sample included
    1,060 teens.***</span>

    100. What is the population parameter then? <span style="color:grey">***We don’t know! We would have to interview
    every teenager in the US to determine the parameter, and that is not possible.***</span>

20. Conclude the lesson by telling the students: although we cannot determine the actual population
parameter for the percent of teens that have made friends online, we can estimate it using
random samples.

###**Class Scribes:**
One team of students will give a brief talk to discuss what they think the 3 most important topics of the
day were.

###<p style="background: black; color: white; text-align: center;">**Homework**</p>
Students should complete the *Parameters & Statistics* handout ([LMR_3.6](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.6_Parameters and Statistics.pdf)) for homework.

**<u>Note:</u>** Page 2 of the handout is an answer key for teacher reference only!
<div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://stemc.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.6_Parameters and Statistics.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe>
<br>[LMR_3.6](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.6_Parameters and Statistics.pdf)</div> 


