##***<u>Lesson 3: Let’s Try an Experiment!</u>***

###**Objective:**
Students will explore the importance of randomized assignment in experiments. They will understand that
without random assignment, there might be confounding variables and will be able to suggest possible
confounding variables.

###**Materials:**
1. Measuring Tape

###**Essential Concepts:**

!!! note "Essential Concepts: "
    Randomized assignment is required to determine cause and effect.

###**Lesson:**
1. Inform students that they will be exploring the question “Why do we need randomized
assignment?” by conducting an experiment. Tell students that you have a treatment that can
make people taller. Explain that the class will be divided into two groups, one group will get the
treatment, and one group will not. The group that does not receive the treatment will be the
control group. After the treatment, they will measure the groups to see which is taller. Now divide
the class into two groups by placing the boys in the treatment group and the girls in the control
group.

    Remember that in an experiment we typically have a treatment group and a control group. In
    the MythBusters experiment, they compared number of yawns after treatment, and not any
    measurements before treatment, because they were comparing the treatment group to the
    control group (the control group is specifically here because it is a comparable untreated
    group - this allows us to not need “before” measurements). Therefore, in this case, we will run
    the experiment and then compare average height of the treatment group to the control group.

2. Tell them that after the treatment group takes the treatment, your statistic to compare groups will
be to measure the heights. If the treatment group is taller, then the treatment must have worked.
There are two possible outcomes to dividing the class this way:

    100. The students will protest (as they should) and you can start a discussion as to why this is
    not a good way to divide the class.

    100. OR the students don’t protest and you continue with the experiment. The treatment
    should be something silly, like waving a ruler in front of the person’s face or by asking
    them to chant “grow, grow, grow!” three times. After treatment, measure the heights of
    each group and ask them if they think this is good evidence (**do not say “proves”**) that
    the treatment is effective.

3. Regardless of the outcome, students should recognize that by putting the boys in one group, the
outcome was pre-determined, since boys tend to be taller than girls to begin with. This is an
example of a **confounding factor**. Confounding factors are variables that provide an alternative
explanation of the effect of the treatment on the outcome variable.

4. Ask students: “How should students be put into groups?”

5. Discuss various other methods of grouping students. Someone will probably say to split the
groups into equal numbers of boys and girls. At this suggestion, divide the class into two groups
by placing the tallest boys and tallest girls in the treatment group, and the shorter boys and
shorter girls in the control group. <span style="color:grey">***Students should be able to recognize that you shouldn’t
use any characteristics to decide the groups.***</span>

6. Continue discussion of other ways to decide the groups. Use the following questions as a guide:

    100. What about flipping a coin?

    100. What will the gender balance look like? <span style="color:grey">***Each group should have about the same
    balance as the class, though not exactly.***</span>

    100. Why is it important that the groups be similar? <span style="color:grey">***Because otherwise, something else
    might be the cause of the response changing.***</span>

7. Inform students that today the class will begin to design their own experiment using what they
have learned over the last few lessons. The question they will investigate is:

    **How does our perception of time change when exposed to a stimulus?**

8. They will be trying to determine the length of one minute without the use of time-aids. In their
experiment, they will subject some students to a stimulus and others to no stimulus. They will
then analyze the data to determine if subjecting students to a stimulus affects the perception of
how long a minute of time lasts.

9. In their DS journals, ask students to answer the following questions about the elements of their
experiment:

    100. What is the research question we’re interested in addressing?

    100. Who are the subjects that will be participating in the experiment?

    100. How should we randomly assign the subjects into treatment and control groups? (See
    step 12 for an RStudio method that the teacher can use)

    100. What is the outcome variable that we will be measuring? What unit of measurement
    should we use?

    **<u>Note:</u>** Students will decide on a treatment to apply to each group on the following day.

10. As a class, discuss the responses to the questions above (step #9, a-e) and come to a
consensus for each question’s answer.

11. Inform the class that they will be using the answers they have agreed upon as the final design of
the class’s experiment.

12. At the end of the class, the students should be assigned to the treatment or control groups using
the randomization method they chose as a class in step #9c.

    **<u>Note:</u>** One method to determine group assignment would be to use the class roster and the
    sample() function in RStudio. The students have a number that corresponds to their placement on
    the roster (i.e. student 1’s last name most likely starts with an A, and then we move alphabetically
    through the roster). You can then use RStudio to randomly select which half of the
    numbers/students will be assigned to the treatment group.

    **> sample(1:30, size = 15, replace = FALSE)**

13. Students will conduct the experiment in the [next lesson](lesson4.md).

###**Class Scribes:**
One team of students will give a brief talk to discuss what they think the 3 most important topics of the
day were.