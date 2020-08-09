##***<u>Lesson 14: How Confident Are You?</u>***

###**Objective:**
Students will learn about informal confidence intervals and estimates for the margin of error.

###**Materials:**
1. Dotplot titled “Mean Word Length, Random Sample, Size = 10” – from [Lesson 11](lesson11.md)

###**Vocabulary:**
margin of error, bootstrapping

###**Essential Concepts:**

!!! note "Essential Concepts: "
    The margin of error expresses our uncertainty in an estimate. The estimate, plus or
    minus the margin of error, gives us an interval in which we are very confident the true value lies.

###**Lesson:**
1. In this lesson, students will learn about confidence intervals in more detail.

2. Display the dotplot the class created during [Lesson 11](lesson11.md) (The Gettysburg Address) titled “Mean
Word Length, Random Sample, Size = 10.”

3. Have students recall that each dot represents one student’s calculation of the mean word length
of a sample of 10 randomly selected words from the Gettysburg Address.

4. Also remind them that the population parameter, which is the mean word length of all words in the
speech, was 4.22. There should already be a vertical line on the dotplot to indicate this value, but
if it is not present, please add it during this step. Ask:

    100. What vocabulary word was used to describe each of the sample means we each created
    during [Lesson 11](lesson11.md)? <span style="color:grey">***The sample statistic. Every dot on the graph represents one
    sample statistic, more specifically each dot corresponds to a different sample
    mean.***</span>

    100. How many of us got exactly the right value? <span style="color:grey">***Probably none.***</span>

    100. Thinking back on The Confidence Game we played yesterday, what approach could we
    do so that 90% of us would be correct? <span style="color:grey">***We could give an interval.***</span>

5. Show students that they can give an interval in the form:

    **Your sample statistic plus or minus AMOUNT**

6. Ask them to calculate what their AMOUNT must be so that their interval includes the parameter
value. Ask them to write this as an interval.

7. Choose one student to illustrate what is to be done. Ask them for their AMOUNT. On the dotplot,
find their value, and use bars to go out plus and minus the AMOUNT. Confirm that it includes the
parameter value.

    **<u>For example:</u>** The purple dot represents a sample mean of 3.5. The AMOUNT we have
    chosen for this particular case is 0.8, so the lower bracket is 0.8 below the sample mean,
    and the upper bracket is 0.8 above the sample mean. Notice that the population
    parameter is included within the brackets.

    <img src="../../img/31407.png" />

8. Now, convert this to an interval of the form [lowest value, highest value] by subtracting the
amount from the sample statistic to get the lowest value, and adding to get the highest.

9. Inform students that this AMOUNT is called the **margin of error**. Explain that the students all now
have different margins of error because in this unusual 'game' they know the population value.
But in real life we do not, and so we have to choose one single margin of error that will work 90%
of the time.

10. Ask the students what margin of error they should use so that 90% of the estimates will have a
'successful' interval. You might want to tell them how many estimates that is for your class. A
ballpark figure for the margin of error is 1.3.

11. Explain: If we were to start all over, we could imagine picking one of these sample statistics at
random.

    100. What's the probability that the sample statistic plus or minus the margin of error would
    include the parameter value? <span style="color:grey">***90%.***</span>

12. Because of this, we call these 'confidence intervals.' When we report an interval, for example 2.7
to 4.3, we say "We are 90% confident that the population parameter value is between 2.7 and
4.3." This is another way of saying "We don't know what the exact true value is, but we're
confident it is somewhere in this interval."

13. Remind students of the Pew Poll they discussed during [Lesson 10](lesson10.md). For reference, the Pew
Research Center made the following statement in their August 2015 report titled *Teens,
Technology & Friendships:* **Pew Poll**

    “For today’s teens, friendships can start digitally: 57% of teens have met new friends
    online. The margin of error is plus or minus 3.7 percentage points. Social media and
    online gameplay are the most common digital venues for meeting friends.”

    **<u>Note:</u>** The data for this report were collected via interviews of 1,060 teenagers between the ages
    of 13 and 17.

14. Now that students have learned about the margin of error, have them write an *Exit Slip* about
what the margin of error means in context of the Pew Poll.

15. Conclusions and takeaways:

    100. Estimates that are based on random samples vary.

    100. We can measure this variation.

    100. The margin of error can tell us how much estimates vary.

    100. We can use the estimate from our random sample, along with the margin of error, to give
    us a range of plausible values for the population parameter. This is called a confidence
    interval.

16. If time allows, introduce students to the idea of **bootstrapping**, which is where we take random
samples of really large samples. For example, if we were looking at Twitter data, it would be
almost impossible to compile every single tweet that exists in the population. Instead, we might
be able to access 500,000 tweets, which is a very large sample. From this sample, we could
create smaller random samples of size 100 and make inferences about the overall population of
tweets from these samples. This will be discussed further in [Lab 3D](lab3d.md).

###**Class Scribes:**
One team of students will give a brief talk to discuss what they think the 3 most important topics of the
day were.

###<p style="background: black; color: white; text-align: center;">**Next Day**</p>
[<u>***LAB 3D: Are You Sure about That?***</u>](lab3d.md)

Complete [Lab 3D](lab3d.md) prior to the [Let’s Build a Survey! Practicum](practicum2.md).