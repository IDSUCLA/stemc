##***<u>Lesson 4: How Far is it from Typical?</u>***

###**Objective:**
Students will understand that the mean of the absolute deviations (MAD) is a way to assess the degree of
variation in the data from the mean and adjusts for differences in the number of points in the data set (*n*).
The MAD measures the total distance between all the data values from the mean and divides it by the
number of observations in the data set.

###**Materials:**
1. Masking tape (or painter’s tape) – approximately 4-5 feet long – one for each student team

2. *How Far Apart?* handout ([LMR_2.6_How Far Apart](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.6_How Far Apart.pdf)) – will be used again in [Lesson 17](lesson17.md)

3. Exported, printed, and reproduced class’s *Personality Color* survey data

###**Vocabulary:**
measures of variability (spread), deviation, mean of absolute deviations (MAD)

###**Essential Concepts:**

!!! note "Essential Concepts: "
    MAD measures the variability in a sample of data - the larger the value, the greater
    the variability. More precisely, the MAD is the typical distance of observations from the mean. There are
    other measures of spread as well, notably the standard deviation and the interquartile range (IQR).

###**Lesson:**
1. Remind students that they learned about 2 different measures of center during the previous 2
lessons: the mean and the median. Have the students recall when it is appropriate to use each
value based on the shape of the distribution.

    100. Mean – use with symmetric distributions.

    100. Median – use with skewed distributions or when there are outliers.

2. Inform the students that, during today’s lesson, they will learn about **measures of variability** –
also known as measures of **spread**. These values show us how much the quantitative data varies
from the center of a distribution. Similar to measures of center, we will use two different measures
of spread: (1) the mean of absolute deviations (MAD), and (2) the interquartile range (IQR).
    
    **<u>Note:</u>** IQR will be discussed in detail during [Lesson 5](lesson5.md).

3. Introduce the term **deviation**. Using *Think*, *Pair*, *Share*, ask students what they think this word
means and how it could relate to variability. <span style="color:grey">***A deviation is the act of departing from an
established course or accepted standard. Common synonyms include departure, detour,
difference, digression, divergence, fluctuation, inconsistency, modification, shift, etc.***</span>

4. On the classroom floor next to each student team, place a 4-5 foot long piece of masking tape (or
painter’s tape). Then, propose the following scenario:

    Your team has been invited to guest star at the circus! You have been asked to perform
    as part of the tightrope act – a routine that requires tremendous focus and balance to
    walk across a tightly pulled rope that is suspended high in the air. In order to practice
    your balancing skills, the circus has provided your team with a line of tape that will
    represent the tightrope.

5. Have the students consider the piece of tape (aka the rope) to be the “typical” path they must
take to finish the circus act. Since they do not want to fall from the suspended tightrope while
performing at the actual circus, they will need to practice walking directly on the middle of the line
at all times. If they *deviate* from the line, they will no longer be walking the “typical” path, and will
likely fall.

6. Each team should select one student to be their starting performer.

7. In teams of 4, one student is the performer, two are measuring the distance of the deviation (one
on each side of the tape), and one is the recorder.

8. Place a ruler perpendicular to the “rope” and measure the distance, in centimeters, from the path
to the center of the back of their heel as the student walks and attempts to balance across the
“rope.”

9. The performer will walk the tightrope by looking straight up to the sky – first they look to place a
foot on the line, then walk naturally while looking up to the sky, and repeating one step at a time
for 4 steps, measuring after each step. Any time the performer missteps, this is considered a
variation from the typical value. *You can have students take turns so everyone gets a chance to
balance, walk, and to measure, depending on time in your class.*

10. Now that the students have an idea about what it means to deviate from something they consider
“typical,” they can start looking at distributions to see how data points vary from their typical value.

11. Inform students that they were observing deviations from typical while calculating actual
differences between the rope and the performer’s steps. When data are quantified with numbers,
we can then calculate how far away each value is from the center.

12. One such calculation that is popular among data scientists is the mean of absolute deviations
(MAD). Ask students to consider the components of the MAD in math terms, and brainstorm what
the MAD value might represent.

    <span style="color:grey">***mean – an average***</span>

    <span style="color:grey">***absolute – in mathematics, we talk about absolute value, the positive difference
    between 2 numerical values***</span>

    <span style="color:grey">***deviation – as discussed earlier in the lesson, deviation represents how much
    things vary***</span>

13. Using the 3 concepts in Step 10, explain that the MAD measures the absolute distance of each
data point from the mean, and then finds the average of all those distances.

14. Display the formula for the MAD distribution for the whole class to see.
<center><img src="https://latex.codecogs.com/gif.latex?MAD=\frac{ &space;\sum_{x=1}^{n}&space;|x_i-\bar{x}|}{n}" title="MAD=\frac{ \sum_{x=1}^{n} |x_i-\bar{x}|}{n}" /></center>

15. Discuss what each symbol in the formula means and how we use it to perform the calculation. <span style="color:grey">***x<sub>i</sub>
represents each individual data point, x̄ represents the mean value, and n represents
the total number of observations. The symbol Σ represents the summation – this tells us
to add up all the absolute distances from each point to the mean.***</span>

16. To practice using this formula with actual data, students will calculate and compare the MAD
values for 2 distributions.

17. Distribute the *How Far Apart?* handout ([LMR_2.6](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.6_How Far Apart.pdf)), which contains 2 of the dot plots - plots (a)
and (c) from the *Where is the Middle?* handout ([LMR_2.5](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.5_Where is the Middle.pdf)) used in [Lesson 3](lesson3.md). As before, the dot
plots depict the number of candies eaten by a group of 17 high school students on different days
of the week. The means are also given.
<div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://stemc.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.6_How Far Apart.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_2.6](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 2_v_5.0/LMR_2.6_How Far Apart.pdf)</div>

    <span style="color:grey">**The calculations for each plot are shown below for the teacher’s reference.**</span>

    <u><span style="color:grey">***MAD for plot (a)***</span></u>

    <img src="https://latex.codecogs.com/gif.latex?\begin{align*}&space;MAD&space;&=&space;\frac{1|0-2|&plus;5|1-2|&plus;6|2-2|&plus;3|3-2|&plus;2|4-2|}{17}&space;\\&space;&=&space;\frac{1(2)&plus;5(1)&plus;6(0)&plus;3(1)&plus;2(2)}{17}\\&space;&=&space;\frac{2&plus;5&plus;0&plus;3&plus;4}{17}\\&space;&=&space;\frac{14}{17}\\&space;&\approx&space;0.8235&space;\end{align*}" title="\begin{align*} MAD &= \frac{1|0-2|+5|1-2|+6|2-2|+3|3-2|+2|4-2|}{17} \\ &= \frac{1(2)+5(1)+6(0)+3(1)+2(2)}{17}\\ &= \frac{2+5+0+3+4}{17}\\ &= \frac{14}{17}\\ &\approx 0.8235 \end{align*}" />

    <u><span style="color:grey">***MAD for plot (c)***</span></u>

    <img src="https://latex.codecogs.com/gif.latex?\begin{align*}&space;MAD&space;&=&space;\frac{3|0-2.53|&plus;0|1-2.53|&plus;4|2-2.53|&plus;5|3-2.53|&plus;5|4-2.53|}{17}&space;\\&space;&=&space;\frac{3(2.53)&plus;0(1.53)&plus;4(0.53)&plus;5(0.47)&plus;5(1.47)}{17}\\&space;&=&space;\frac{7.59&plus;0&plus;2.12&plus;2.35&plus;7.35}{17}\\&space;&=&space;\frac{19.41}{17}\\&space;&\approx&space;1.1418&space;\end{align*}" title="\begin{align*} MAD &= \frac{3|0-2.53|+0|1-2.53|+4|2-2.53|+5|3-2.53|+5|4-2.53|}{17} \\ &= \frac{3(2.53)+0(1.53)+4(0.53)+5(0.47)+5(1.47)}{17}\\ &= \frac{7.59+0+2.12+2.35+7.35}{17}\\ &= \frac{19.41}{17}\\ &\approx 1.1418 \end{align*}" />

18. Students may work in pairs to complete the handout. After all student pairs have come to an
agreement on their answers, pose the following questions to the class as a whole:
    
    100. Which MAD value did you think would be larger based only on the look/shape of the
    distributions? Why? <span style="color:grey">***Since plot (c) is skewed to the left, it probably has a larger MAD
    because more points will be further away from the mean than in plot (a).***</span>
    
    100. Which MAD value was actually larger when you calculated it? <span style="color:grey">***The MAD value for plot
    (c) was larger (1.1418 > 0.8253).***</span>
    
    100. Did your prediction match the actual calculated values, or were you surprised by the
    results? <span style="color:grey">***Yes. The distribution with the wider spread (more variability) had the larger
    MAD value.***</span>

19. To continue exploring with the class’s Personality Color survey data, student teams should
calculate the MAD value for their <span style="color:blue">***Blue***</span> scores. Does the MAD value seem reasonable based on
the dot plot they created during [Lesson 2](lesson2.md)?

###**Class Scribes:**
One team of students will give a brief talk to discuss what they think the 3 most important topics of the
day were.
###<p style="background: black; color: white; text-align: center;">**Homework & Next Day**</p>
Students should calculate the MAD values for each of the other 3 personality color scores and
compare the values of the 4 color scores.

[<u>***LAB 2A: All About Distributions***</u>](lab2a.md)

Complete [Lab 2A](lab2a.md) prior to [Lesson 5](lesson5.md).