##***<u>Lesson 10: Marbles, Marbles…</u>***

###**Objective:**
Students will understand that random events vary, so that the percentage predicted by a probability isn't
exact, but varies. Students practice converting percentages to proportions.

###**Materials:**
1. For each student team: 50 marbles – 20 of one color, and 30 of another color

    **<u>Note:</u>** Marbles can be substituted for other materials, such as small blocks, as long as they are
    the same size.

###**Vocabulary:**
proportion, percentage, event, with replacement, without replacement

###**Essential Concepts:**

!!! note "Essential Concepts: "
    There are two ways of sampling data that model real-life sampling situations: with
    and without replacement. Larger samples tend to be closer to the "true" probability.

###**Lesson:**
1. Remind students that, during the previous two lessons, they learned how to estimate probabilities
for a population with the help of simulations to create sample data. Both lessons had nice, prepackaged
functions already available in RStudio, which made the simulations fairly quick and
easy – in [Lesson 8](lesson8.md), the **rflip()** function was used to simulate flipping a coin; and in [Lesson 9](lesson9.md),
the **roll_die()** function was used to simulate rolling one of two dice.

2. But what if we don’t have a nice function to perform a simulation for us? Can we create our own
method? Yes! We will actually learn to create a simulation from scratch during [Lab 2C](lab2c.md).

3. Ask students:

    100. If you have a bag of 50 marbles, where 20 of them are blue and 30 of them are red, what
    is the probability of drawing a red marble? <span style="color:grey">***30/50 or 60%.***</span>

4. Select a student to answer the question. Ask the class if they agree or disagree. If they agree,
ask them to raise their hand. If there are students who disagree, lead a class discussion until a
consensus is reached.

5. Ask students to share their strategies on how to convert the **proportion** into a **percentage**. As
strategies are being shared, students should take notes in their DS journals. Review how to turn
fractions into percentages, if necessary.

6. Ask students:

    100. What if we actually drew out one marble, recorded its color, then replaced it back in the
    bag, and did this 10 times? <span style="color:grey">***Answers will vary by class.***</span>

    100. Would the percentage of red marbles in this sample necessarily be exactly the same as
    the probability? Identify that each time a marble is drawn, we are creating an **event**.
    <span style="color:grey">***Answers will vary by class.***</span>

7. Distribute the bags of marbles to each team. Ask each team to:

    100. Shake the bag of marbles.

    100. Draw one marble out of the bag.

    100. Record the marble’s color in their DS journal.

    100. Replace the marble back into the bag. Inform them that this is called sampling **with
    replacement**. Ask them to consider what “with replacement” means and discuss with the
    class. <span style="color:grey">***“With replacement” means that after you select a marble from the bag, you
    have to put it back into the bag (replace it) before you select another marble.***</span>

    They should draw 10 marbles from the bag and record the observed colors.

8. Do a *Whip Around* to find out how many times each team drew a red marble out of their 10 draws.
Have them calculate the corresponding sample proportions. For example, if one team drew 7 red
marbles out of their 10 draws, their sample proportion is 7/10 = 0.70 (which is the sample as a
sample percentage of 70%).

9. Ask students why the proportions are perhaps different from each other and from the “true”
probability of drawing a red marble?

10. Have the student teams continue drawing marbles, one at a time and with replacement, until they
have 50 events recorded. Discuss the following questions:

    100. How many times did they draw a red marble out of these 50? <span style="color:grey">***Answers will vary by
    class.***</span>

    100. What’s the corresponding sample proportion? Is it closer to the true probability than when
    you only drew 10 marbles? <span style="color:grey">***Answers will vary by class. But, they should notice that,
    as the sample size increases, the sample proportion gets closer to the true
    population proportion.***</span>

11. Engage students in a discussion about how the sample size affects the sample proportion. They
should see that as they draw more marbles, their sample probability gets closer and closer to the
true probability. If we were to continue drawing marbles forever, in the long run, our sample
proportion should equal our true probability.

12. Have students consider what it might mean to sample **without replacement**. How would they do
that with their bag of marbles? <span style="color:grey">***“Without replacement” means that after you select a marble
from the bag, you never put it back into the bag (do not replace it). Instead, you simply
select another marble from the bag immediately. Students should recognize that, by not
replacing the marble each time, the probabilities will change. This means each draw from
the marble bag is NOT independent from another draw because removing one marble
impacts the next event.***</span>

13. *Exit Slip*: Based on this lesson, ask students to describe a sample, an event, and replacement.

###**Class Scribes:**
One team of students will give a brief talk to discuss what they think the 3 most important topics of the
day were.

###<p style="background: black; color: white; text-align: center;">**Next Day**</p>
[<u>***LAB 2C: Which Song Plays Next?***</u>](lab2c.md)

Complete [Lab 2C](lab2c.md) prior to [Lesson 11](lesson11.md).