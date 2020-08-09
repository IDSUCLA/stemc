##***<u>Lesson 8: How Likely Is It?</u>***

###**Objective:**
Students will understand the basic rules of probability. They will learn that previous outcomes do not give
information about future outcomes if the events are independent.

###**Materials:**
1. Video: “Heads” from the movie *Rosencrantz and Guildenstern are Dead* found at:<br>
    [https://www.youtube.com/watch?v=NbInZ5oJ0bc](https://www.youtube.com/watch?v=NbInZ5oJ0bc "https://www.youtube.com/watch?v=NbInZ5oJ0bc")

    <div align="right"><iframe width="420" height="315"
    src="https://www.youtube.com/embed/NbInZ5oJ0bc" allowfullscreen>
    </iframe><br><a href="https://www.youtube.com/embed/NbInZ5oJ0bc">https://www.youtube.com/embed/NbInZ5oJ0bc</a></div>

2. Projector for RStudio functions

###**Vocabulary:**
probability, simulation, model, sample proportion, chance, independence

###**Essential Concepts:**

!!! note "Essential Concepts: "
    Probability is an area that we humans have poor intuition about. Probability
    measures a long-run proportion: 50% chance means the event happens 50% of the time *if you repeated it
    forever*. When we don't repeat forever, we see variability.

###**Lesson:**

1. Have students consider possible synonyms to the word **chance**. If someone says, “That just
happened by chance,” what does that mean? <span style="color:grey">***Synonyms: possibility, prospect, expectation,
unintentional, unplanned. The actual definition of chance is “a possibility of something
happening.”***</span>

2. Ask the students which game – chess or the board game “Sorry” (**<u>Note:</u>** any game can be
chosen) – is more based on chance? Why? <span style="color:grey">***Sorry is more based on chance because many
outcomes are determined by dice rolls. In chess, there are certain strategies and
movements that can be planned, so it is more a game of skill. With Sorry, the players roll a
die (number cube), so the numbers they roll have an impact on how well they do in the
game.***</span>

3. Next, ask students if they can think of situations where chance is the only force at play. <span style="color:grey">***Possible
responses: card games, slot machines, the lottery, coin flipping, and rock, paper, scissors.***</span>

4. Play the “Heads” video from the movie *Rosencrantz and Guildenstern are Dead* found at:
[https://www.youtube.com/watch?v=NbInZ5oJ0bc](https://www.youtube.com/watch?v=NbInZ5oJ0bc "https://www.youtube.com/watch?v=NbInZ5oJ0bc").

5. In their DS journals, ask students to write down their initial reactions to the clip by responding to
the following questions:

    100. Is it *possible* to get 78 heads in a row when tossing a coin? <span style="color:grey">***Yes, it is possible to get 78
    heads in a row since one coin toss does not determine the next coin toss.***</span>

    100. Do you think it is *likely* to get 78 heads in a row? <span style="color:grey">***No. Although it is possible to get 78
    heads in a row.***</span>

    100. How many times should we get a heads when tossing a coin? <span style="color:grey">***1 out of 2 times or 50% of
    the time.***</span>

    100. On average, how many times should the characters have gotten a heads out of the 78
    tosses? <span style="color:grey">***Roughly about 39 times.***</span>

6. Ask students to discuss their findings with their team members and come to an agreement on
their responses. Afterwards, conduct a *Whip Around* and ask each team to share its findings. Are
there any differences between the teams? Any similarities?

7. As teams share their responses, students should add to or revise their individual findings in their
DS journals.

8. Explain to students that, from the concept of chance, we can start learning about **probability**.
Chance is simply the possibility that something will happen, and probability is a measurement for
how often something happens in the “long run.” Students may have ideas about how to calculate
probabilities based on prior classes or knowledge, but inform them that IDS will be taking a
different approach – using simulations (see next step).

9. Since we don’t want to actually flip a coin 78 times like the actors did in the video, we can have
RStudio simulate them for us. A **simulation** is a way of creating random events that are close to
real-life situations without actually doing them. It is a kind of **model**, which is a way of
representing real world situations so that predictions can be made.

10. Explain to students that R has a function that does coin flipping for us, and that it assumes an
equal probability of heads and tails. Using a projector to display your computer screen to the
whole class, demonstrate how to do one simulation of a coin flip in RStudio. Use the following
function:

    **> rflip(1)**

11. Explain that the value of 1 in the argument part of the function tells R to flip the coin 1 time. If we
want to flip the coin 10 times, we could simply change the function to **rflip(10)**.

12. Run the function again using 10 as the number of times to flip the coin. Ask students:

    100. How many heads (“H”s) were there? <span style="color:grey">***Answers will vary for each sample.***</span>

    100. How many Tails (“T”s) were there? <span style="color:grey">***Answers will vary for each sample.***</span>

    100. In the output, what does **Flipping 10 coins [Prob(Heads) = 0.5]** mean? <span style="color:grey">***This is
    RStudio telling us that we are tossing the coin 10 times and that the***</span> **probability** <span style="color:grey">***of
    getting heads should be 0.5 (it is flipping a fair coin).***</span>

    100. In the output, what does **Number of Heads: 3 [Proportion Heads: 0.3]** mean?
    
        **<u>Note:</u>** This is example output. Your sample may have a different value for the number of
        heads that appeared, and thus a different value for the proportion of heads. <span style="color:grey">***This is
        RStudio telling us that in our sample, we got heads 3 out of the 10 times we flipped
        the coin. The***</span> **sample proportion** <span style="color:grey">***is automatically calculated for us by dividing the
        number of heads by the total number of tosses (in this case, 3/10 = 0.3).***</span>

13. To relate back to the video at the beginning of class, repeat the simulation once more, but use 78
as the number of coin flips **rflip(78)**. Students should record answers to the following
questions in the DS journals:

    100. How many heads (“H”s) were there? Since we know to expect about 39 heads if the coin
    is fair, does the value seem reasonable? <span style="color:grey">***Answers will vary for each sample. Most
    likely, you will see values near 39.***</span>

    100. How many Tails (“T”s) were there? <span style="color:grey">***Answers will vary for each sample.***</span>

    100. What proportion of the coin flips were heads? <span style="color:grey">***Answers will vary for each sample.***</span>

14. Using the **rflip(78)** command, run the simulation a few more times (3 – 5) and have students
record the values for the number of heads and the proportion of heads.

    <span style="color:grey">***As an example, we ran the function 3 times and saw the following values:***</span>

    <span style="color:grey">***Sample 1 – amount of heads: 45***</span>

    <span style="color:grey">***&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;proportion of heads: 0.577***</span>

    <span style="color:grey">***Sample 2 – amount of heads: 33***</span>

    <span style="color:grey">***&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;proportion of heads: 0.423***</span>

    <span style="color:grey">***Sample 3 – amount of heads: 42***</span>

    <span style="color:grey">***&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;proportion of heads: 0.538***</span>

15. Have students answer the questions listed below. The important thing to note is that the values
can and (almost always) WILL change each time you run the simulation to create a new sample.

    100. How do the proportions of heads in the samples compare to each other? <span style="color:grey">***Answers will
    vary.***</span>

    100. How do the proportions of heads compare to the true probability of heads (1/2 or 50%)?
    <span style="color:grey">***Answers will vary, but they should notice that most of the probabilities are close to
    50%.***</span>

    100. Why is there a 50% chance of getting heads during each coin flip? <span style="color:grey">***Since there are two
    sides to a coin, both should be equally likely to come up. So there is a 1 out of 2
    chance of getting heads and 1 out of 2 chance of getting tails.***</span>

16. Next, pose the following question:

    100. If you get a heads on the first toss of a coin, will you definitely get a heads on the next
    toss? Will you definitely get a tails on the next toss? <span style="color:grey">***No. One coin toss should not
    affect another coin toss. Each time you flip the coin, the chances of getting heads
    versus tails remains the same.***</span>

17. Introduce the concept of **independence**. Explain that, when tossing a fair coin, there is no
relationship between each toss. The second toss does NOT depend on the first toss; therefore,
the coin tosses are independent of each other.

###**Class Scribes:**
One team of students will give a brief talk to discuss what they think the 3 most important topics of the
day were.

###<p style="background: black; color: white; text-align: center;">**Homework**</p>
Students will create a Tweet (they do not have to post it online). Using 280 characters or fewer, write a
Tweet about the meaning of probability.