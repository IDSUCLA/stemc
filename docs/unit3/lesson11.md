##***<u>Lesson 11: The Gettysburg Address</u>***

###**Objective:**
Students will learn the definition of sampling bias and will learn that random samples reduce bias when
estimating a population parameter. They will gain practice collecting a random sample from a small
population and estimating the population parameter.

###**Materials:**
1. *Gettysburg Address* handout ([LMR_3.7_Gettysburg_Address](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.7_Gettysburg Address.pdf))

2. *Sampling the Gettysburg Address* handout ([LMR_3.8_Sampling the Gettysburg Address](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.8_Sampling the Gettysburg Address.pdf))

3. Dotplot titled “Mean Word Length, Self-Selected Sample, Size = 10” – on board or poster paper

4. *Gettysburg Address – Word Length Histogram* file ([LMR_3.9_Gettysburg Histogram](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.9_Gettysburg Histogram.pdf))

5. *Gettysburg Word Lengths* handout ([LMR_3.10_Gettysburg_Words](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.10_Gettysburg Words.pdf))

6. RStudio

7. Projector for RStudio functions

8. Dotplot titled “Mean Word Length, Random Sample, Size = 10” – on board or poster paper

    **<u>Note:</u>** This dotplot will be used again during [Lesson 13](lesson13.md), so the results need to be kept in some
    way (this can be either on poster paper or by simply taking a photo).

###**Vocabulary:**
sampling bias

###**Essential Concepts:**

!!! note "Essential Concepts: "
    Statistics vary from sample to sample. If the typical value across many samples is
    equal to the population parameter, the statistic is 'unbiased.' Bias means that we tend to “miss the mark.”
    If we don't do random sampling, we can get biased estimates.

###**Lesson:**
1. Introduce the lesson by describing the Gettysburg Address:

    100. President Lincoln delivered the Gettysburg Address in November 1863.

    100. It is one of the most famous speeches in the United States.
 
    100. In it, Lincoln invoked the principles of human equality contained in the U.S. Constitution
    and Declaration of Independence.

2. Read the Gettysburg Address aloud to the class OR have students read it aloud. The text of the
speech can be found in the *Gettysburg Address* handout ([LMR_3.7](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.7_Gettysburg Address.pdf)).
<div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://stemc.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.7_Gettysburg Address.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_3.7](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.7_Gettysburg Address.pdf)</div>

3. Today we will use the Gettysburg Address to learn about different sampling techniques.

4. Inform students that the Gettysburg Address contains 272 words. We can consider these 272
words to be our population because it includes all words in the entire speech. From the
population, we can sample 10 words that we think represent the speech. It is ok for this step to be
vague – students can come up with their own concept for what they think “representative” means
in this case.

5. Distribute the *Sampling the Gettysburg Address* handout ([LMR_3.8](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.8_Sampling the Gettysburg Address.pdf)), which includes the actual
speech, as well as 2 sampling activities. For this part of the lesson, we will only be looking at
Sampling Activity 1 on page 1 of the handout.

    **<u>Note:</u>** This activity was originally created by Allan Rossman and Beth Chance, and has been
    modified for the IDS curriculum.

    <div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://stemc.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.8_Sampling the Gettysburg Address.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_3.8](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.8_Sampling the Gettysburg Address.pdf)</div>

6. Inform students that they will get 30 seconds to select 10 words that they think are representative
of all words in the speech.

    **<u>Note:</u>** It is important that students work fast so they are forced to choose based on first
    impressions and don't have time to reflect. Also, this activity tends to not work well if students are
    informed of the punch line (that random samples are unbiased) before they begin.

7. At this point, explain to students that we are actually interested in answering a specific question:

    **What is the typical <u>word length</u> in the Gettysburg Address?**

8. Next, students should record each circled word, as well as the number of letters each word has
(this is the word length) in the table on the handout. Then, they should summarize the data in a
dotplot and calculate the mean word length of the sample.

9. On the board, create a class dotplot (may also be done on poster paper) titled “Mean Word
Length, Self-Selected Sample, Size = 10.” Once all students have completed the first page of the
*Gettysburg Address* handout ([LMR_3.8](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.8_Sampling the Gettysburg Address.pdf)), ask each student to record the <U>mean word length of his
or her sample</u> on the class’s dotplot.

10. When all students have recorded their sample statistics in the dotplot, conduct a class discussion
based on the questions listed below.

    **<u>Note:</u>** You might need to do a reality check. Students will often make mistakes when adding the
    word lengths and when dividing. Be suspicious (and double-check) extreme values.

    100. What does each point on the plot represent? <span style="color:grey">***Each point represents one student's
    estimate of the mean length of all of words in the Gettysburg address.***</span>

    100. What is the typical value represented in the dotplot? <span style="color:grey">***Answers will vary by class. You
    should indicate the approximate location of the mean of the distribution (the
    balancing point, on the dotplot. Remind students that when we ask for the 'typical'
    value we mean the value in the center of the distribution.***</span>

    100. How much variability is there in the distribution? <span style="color:grey">***Answers will vary by class. One
    reasonable approach is for students to give the range (the difference between the
    largest and smallest values).***</span>

    100. What is the shape of the distribution? <span style="color:grey">***Answers will vary by class. Often, the shape is
    right-skewed, but it might not be for you. Note that outliers here will often be
    arithmetic errors, but not always.***</span>

11. Next, display the histogram from the *Gettysburg Address – Word Length Histogram* file
([LMR_3.9](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.9_Gettysburg Histogram.pdf)), which shows the distribution of word lengths for the entire population of words in the
Gettysburg Address.
<div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://stemc.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.9_Gettysburg Histogram.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_3.9](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.9_Gettysburg Histogram.pdf)</div>

12. Remind students that the population is the 272 words from the speech, and inform them that the
mean word length of the population, or the population parameter, is 4.22. Using *Think-Pair-Share*,
ask:

    100. How does the typical value of our class’s sample means compare to the actual population
    mean of 4.22? <span style="color:grey">***Almost always, the class’s typical mean will be higher (sometimes
    much higher) than 4.22. Some students will be close to 4.22. But point out that we
    are talking about the "trend" or typical outcome. The typical outcome is usually too
    high.***</span>

13. Explain that self-selected samples often produce biased results. **Sampling bias** is a description
of the process, or the sampling plan, that is used to collect data. If the resulting samples tend to
produce results that are influenced in one particular direction, we say that the sampling plan is
biased.

    **<u>Note:</u>** Bias is NOT the same as prejudice. Bias is a tendency to lean towards a certain belief or
    viewpoint, and is mostly unconscious. Prejudice is a very conscious phenomenon though, where
    a person actively makes a decision to dislike something based on unfounded facts.

14. Refer back to the dotplot of sample means and point out how it is biased. Ask:

    100. Why was our original sampling procedure biased? <span style="color:grey">***When we look for 'representative'
    words, and do so quickly, our eyes are drawn by the larger, more unusual words,
    and we tend to overlook small words such as “in,” “a,” “we,” etc.***</span>

15. Go back to the *Gettysburg Address* handout ([LMR_3.8](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.8_Sampling the Gettysburg Address.pdf)), and direct students to page 2 for
Sampling Activity 2. Inform students that they will now do a sampling procedure that results in a
better representation of the population of words in the speech.

16. Explain that a random sample tends to produce unbiased sample results.

17. Before students begin the activity, demonstrate how to generate 10 random numbers from a
possible 272 using RStudio.

    **> sample((1:272), size = 10, replace = FALSE)**

18. Each student should generate his or her own set of 10 random numbers. Once students have
created their random numbers, distribute the *Gettysburg Address Word Lengths* handout
([LMR_3.10](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.10_Gettysburg Words.pdf)).
<div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://stemc.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.10_Gettysburg Words.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_3.10](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.10_Gettysburg Words.pdf)</div>

19. Explain that the table contains the word number, word, and length of each word in the Gettysburg
Address. Demonstrate how to find a word that corresponds to one of the random numbers
generated by RStudio, and explain that this word is now part of our random sample.

20. Then, each student will complete the handout by creating a dotplot and calculating the mean of
their random sample.

21. On the board, near the first dotplot, create another class dotplot (may also be done on poster
paper) titled “Mean Word Length, Random Sample, Size = 10.” Once all students have completed
the second page of the *Gettysburg Address* handout ([LMR_3.8](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.8_Sampling the Gettysburg Address.pdf)), ask each student to record <u>the
mean word length of his or her random sample</u> on the class’s dotplot.

    **<u>Note:</u>** As in Step 7, be sure to check arithmetic for outliers!

22. When all students have recorded their sample statistics in the dotplot, conduct a class discussion
based on the following questions:

    100. What does each point in the dotplot represent? <span style="color:grey">***Each dot represents one student's
    estimate of the mean word length. But this time, the estimates are based on a
    random sample of 10 words.***</span>

    100. What do you notice about the typical value in this distribution? <span style="color:grey">***Answers will vary by
    class. They should notice that the means of the random samples are fairly close to
    the population mean of 4.22. (Again, you might have to discard or correct outliers.)***</span>
    
    100. What shape does this distribution have? What does that tell us? <span style="color:grey">***Typically, the
    distribution of sample means for random samples will be symmetric and unimodal.***</span>
    
    100. What does this distribution tell us about the benefits of random samples? <span style="color:grey">***We can reduce
    bias by collecting random samples instead of self-selected samples.***</span>
    
    100. Why do we need sampling? Why can’t we just get the information from the actual
    population? <span style="color:grey">***It is usually impossible to include every person or object from a
    population. Even for the population of size 272 words in the Gettysburg Address, it
    would take a long time to calculate the word lengths of every single word.***</span>

23. Conclusions and takeaways:

    100. It turns out that there are approximately 5.17•10<sup>17</sup> different possible samples of 10 words
    from the Gettysburg Address.

    100. If we could determine the mean for each of these samples and produce a dotplot for all of
    these means, then the center of the dotplot would lie exactly at 4.22.
    
    100. The resulting distribution of the means from all possible samples is called the sampling
    distribution for the sample mean (for samples of size 10 from this population).
    
    100. The above dotplot is an approximation to the actual sampling distribution.
    
###**Class Scribes:**
One team of students will give a brief talk to discuss what they think the 3 most important topics of the
day were.

###<p style="background: black; color: white; text-align: center;">**Homework & Next Day**</p>
Students should write a reflection about why random sampling is better at reducing bias than other
sampling procedures.

[<u>***Lab 3C: Random Sampling***</u>](lab3c.md)

Complete [Lab 3C](lab3c.md) prior to [Lesson 12](lesson12.md).