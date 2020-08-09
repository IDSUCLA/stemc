##***<u>Lesson 19: Data Scientists or Doctors?</u>***

###**Objective:**
Students will create their own decision trees based on training data (i.e., the data from the previous day's
lessons), and then see how well their decision tree works on new test data.

###**Materials:**
1. *Decision Tree for Heart Attack Risk* graphic ([LMR_4.22_CART Heart Attacks](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 4_v_5.0/LMR_4.22_CART Heart Attacks.pdf))

2. *Make Your Own Decision Tree* handout ([LMR_4.23_Your Own Decision Tree](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 4_v_5.0/LMR_4.23_Your Own Decision Tree.pdf))

###**Vocabulary:**
training data, testing data

###**Essential Concepts:**

!!! note "Essential Concepts: " 
    We can determine the usefulness of decision trees by comparing the number of
    misclassifications in each.

###**Lesson:**

1. Ask students the following question:

    ***If a close friend or family member were having chest pains, would you want to take that
    person to a doctor or to a data scientist?***

2. Give the students some time to think about the question and have a few of them share out their
responses with the class.

    **Note:** It’s likely that most students will choose to bring their loved one to a doctor.

3. As it turns out, back in the late 1970s, a cardiologist (and early data scientist) named Lee
Goldman developed a decision tree based on millions of patient observations. The decision tree
was made to diagnose whether people were or were not having a heart attack. Interestingly, the
results of the decision tree compared to how actual doctor diagnoses are shown below:

    100. Correct diagnoses using the decision tree were above 95%.

    100. Correct diagnoses based on individual doctors’ expertise? Anywhere between 75-90%.

4. Display the graphic from the* Decision Tree for Heart Attack Risk* file ([LMR_4.22_CART Heart Attacks](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 4_v_5.0/LMR_4.22_CART Heart Attacks.pdf)) and explain that this is one example of what the decision tree might have looked like.

    Note: This is NOT the actual tree Goldman developed.

    <div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://stemc.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 4_v_5.0/LMR_4.22_CART Heart Attacks.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_4.22](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 4_v_5.0/LMR_4.22_CART Heart Attacks.pdf)</div>

5. Using a *Pair-Share*, ask students to discuss the following questions using the graphic above, as
well as what they learned during the previous lesson’s activity.

    a. What are decision trees?

    b. How do they work at classifying data into groups?

6. Then display the following data (the same data from the player cards used in the previous
lesson):

    | **Team** | **Player** | **Height (inches)** | **Weight (pounds)** | **Age** | **League** |
    |------------------|--------------------|-----------------|-----------------|-----|--------|
    | Carolina  | Cam Newton | 77 | 245 | 26 | NFL |
    | Chicago  | Sean Johnson | 75 | 217 | 26 | USMNT |
    | Dallas  | Matt Cassel | 76 | 230 | 33 | NFL |
    | Dallas  | Tony Romo | 74 | 230 | 35 | NFL |
    | Dallas  | Matt Hedges | 76 | 190 | 25 | USMNT |
    | Kansas  City | Alex Smith | 76 | 216 | 31 | NFL |
    | Kansas City | Matt Besler | 72 | 170 | 28 | USMNT |
    | New England | Tom Brady | 76 | 225 | 38 | NFL |
    | New England | Jermaine Jones | 72 | 179 | 34 | USMNT |
    | Seattle | Russell Wilson | 71 | 206 | 27 | NFL |
    | Seattle | Clint Dempsey | 73 | 170 | 32 | USMNT |
    | Toronto | Michael Bradley | 73 | 179 | 28 | USMNT |
    | Toronto | Jozy Altidore | 73 | 174 | 26 | USMNT |
    | Washington, D.C. | Robert Griffin III | 74 | 223 | 25 | NFL |
    | Washington, D.C. | Steve Birnbaum | 74 | 181 | 28 | USMNT |

7. Distribute the *Make Your Own Decision Tree* handout ([LMR_4.23_Your Own Decision Tree](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 4_v_5.0/LMR_4.23_Your Own Decision Tree.pdf)) and
give students time to come up with their own decision trees based on the **training data** they are
given. Students may work in pairs or teams. They should follow the directions on page 1 of the
handout and come up with a series of possible yes/no questions that they could ask to classify
each player into his correct league (the NFL or the USMNT).
<div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://stemc.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 4_v_5.0/LMR_4.23_Your Own Decision Tree.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_4.23](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 4_v_5.0/LMR_4.23_Your Own Decision Tree.pdf)</div>

8. Once the students have finished creating their decision trees, ask the following questions:

    100. Will you be able to classify other players from a new data set correctly using this
    particular decision tree?

    100. Is this decision tree too specific to the training data?

9. Inform the students that they should now use the **testing data** on page 2 of the handout to try to
classify 5 *mystery players* into one of the two leagues. They should record the classification that
their tree outputs in the data table on page 2.

10. Let the students compare their decision trees and league assignments with one another.
Hopefully, there will be a bit of variety in terms of the trees and the classifications.

11. Next, show students the correct league classifications for the 5 mystery players. The mystery
player names are also included in this table.

    | **Team** | **Player** | **Height (inches)** | **Weight (pounds)** | **Age** | **League** |
    |----------------|-----------------|-----------------|-----------------|-----|--------|
    | Toronto | Michael Bradley | 74 | 175 | 28 | USMNT |
    | New York | Eli Manning | 76 | 218 | 34 | NFL |
    | New Orleans | Drew Brees | 72 | 209 | 36 | NFL |
    | Washington, DC | Perry Kitchen | 72 | 160 | 23 | USMNT |
    | New England | Lee Nguyen | 68 | 150 | 29 | USMNT |

12. By a show of hands, ask:

    a. How many students misclassified all of the players in the testing data?

    b. How many misclassified 4 of the 5 players?

    c. How many misclassified 3 of the 5 players?

    d. How many misclassified 2 of the 5 players?

    e. Did anyone correctly classify ALL 5 mystery players? If so, ask those students to share
    their decision trees with the rest of the class.

13. Inform students that, when faced with much more data, creating classification trees becomes
much harder to make by hand. It is so difficult, in fact, that data scientists rely on software to grow
their trees for them. Students will learn how to create decision trees in RStudio during the next lab.

###**Class Scribes:**
One team of students will give a brief talk to discuss what they think the 3 most important topics of the
day were.

###<p style="background: black; color: white; text-align: center;">**Homework & Next Day**</p>
Write a paragraph describing the role testing data and training data play in creating a classification
tree.

[<u>***LAB 4G: Growing Trees***</u>](lab4g.md)

Complete [Lab 4G](lab4g.md) prior to [Lesson 20](lesson20.md).