##***<u>Lesson 20: Online Data-ing</u>***

###**Objective:**
Students will discover that data exists on the Internet in a variety of areas, formats, and for a variety of
purposes.

###**Materials:**
1. Video: *Explore a Google Data Center with Street View* found at:<br> [http://www.dailymail.co.uk/sciencetech/article-2219188/Inside-Google-pictures-gives-look-8-vast-datacentres.html#v-1907075360001](http://www.dailymail.co.uk/sciencetech/article-2219188/Inside-Google-pictures-gives-look-8-vast-datacentres.html#v-1907075360001 "http://www.dailymail.co.uk/sciencetech/article-2219188/Inside-Google-pictures-gives-look-8-vast-datacentres.html#v-1907075360001")

2. *Wikipedia – Video Games* handout ([LMR_3.17_Wikipedia - Video Games](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.17_Wikipedia - Video Games.pdf))

3. *Wikipedia – Video Games – CSV Format* handout ([LMR_3.18_Video Games - CSV](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.18_Video Games - CSV.pdf))

4. *Online Data-ing* handout ([LMR_3.19_Online Data-ing](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.19_Online Data-ing.pdf))

###**Vocabulary:**
data farm, tags, HTML

###**Essential Concepts:**

!!! note "Essential Concepts: "
    We stretch students' conception of data, to help them see that many web pages
    present information that can be turned into data.

###**Lesson:**
1. By a show of hands, ask students if they have ever heard of the term **data farm**. If any of them
have, ask him or her to share what they know about it.

2. Inform students that a data farm is a physical space where high capacity servers are placed to
store large amounts of data.

3. Introduce the video titled *Explore a Google data center with Street View* found at [http://www.dailymail.co.uk/sciencetech/article-2219188/Inside-Google-pictures-gives-look-8-vast-datacentres.html#v-1907075360001](http://www.dailymail.co.uk/sciencetech/article-2219188/Inside-Google-pictures-gives-look-8-vast-datacentres.html#v-1907075360001 "http://www.dailymail.co.uk/sciencetech/article-2219188/Inside-Google-pictures-gives-look-8-vast-datacentres.html#v-1907075360001") by explaining that the data center they are about to see is
one of these large data farms used to store vast amounts of data.

4. After students watch the video, have a class discussion using the following questions:

    100. We have been talking about data for a few months now. How would you respond if
    someone asked you, “What are data?” <span style="color:grey">***Answers will vary by class.***</span>

    100. What are some ways that we have stored data? <span style="color:grey">***Data frames in R, Excel
    spreadsheets, .csv files.***</span>

5. Explain that one of the main ways data are distributed is through the Internet. Storing and sharing
data on the Internet requires a different format than what we have seen. For example, Wikipedia
has a page dedicated to the top video games.

6. Distribute the *Wikipedia – Video Games* handout ([LMR_3.17](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.17_Wikipedia - Video Games.pdf)), and have students explain the
information that the data table provides.
<div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://stemc.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.17_Wikipedia - Video Games.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_3.17](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.17_Wikipedia - Video Games.pdf)</div>

7. Once the students understand what the data table describes, walk them through the first portion
of the **HTML**, or Hypertext Markup Language, source code (on page 1). Notice that the first
header on the table is denoted as “Game.” Ask:

    100. How is “Game” represented in the source code? <span style="color:grey">***&lt;th>Game&lt;/th>***</span>

    100. What do you think the &lt;th> code represents? <span style="color:grey">***The &lt;th> is a tag for “table header”***</span>

    100. If this were in RStudio, what would we call this header? <span style="color:grey">***A variable***</span>.

8. Assign each student team one video game from the Wikipedia data table. Each team will
compare how the information is stored in the table with its corresponding HTML source code.
Each team should answer the following questions in the DS journals.

    100. Where are the variable names stored? <span style="color:grey">***The variable names are stored at the
    beginning of the code, in between &lt;th> and &lt;/th>. &lt;th> and &lt;/th> are called***</span> **tags** <span style="color:grey">***–
    they tell the browser to represent the information between them as a header in the
    table.***</span>

    100. How are different values of the variables stored? <span style="color:grey">***Values are stored between the &lt;td>
    and &lt;/td> tags.***</span>

    100. Why do you think the data are stored in such a complex way? Why can’t we just put them
    in a spreadsheet? <span style="color:grey">***Answers may vary by class. One reason is that the data must be
    displayed in a way that allows a browser to make it look pretty (and readable) on a
    computer screen.***</span>

    100. How could we get this into an R dataframe so we can analyze it? <span style="color:grey">***In its current form,
    this would be very difficult. We would need to represent the data in a different
    format in order for R to understand it.***</span>

9. Distribute the *Wikipedia – Video Games – CSV Format* handout ([LMR_3.18](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.18_Video Games - CSV.pdf)) and explain that this
is yet another way to represent the same video game data.

    **<u>Note:</u>** The handout only provides information on the first 5 rows of the Wikipedia table. A full
    version of the file (including all video games in the table) is located on the server with the title
    bestgames.csv.
    
    <div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://stemc.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.18_Video Games - CSV.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_3.18](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.18_Video Games - CSV.pdf)</div>

10. Inform students that a file with the CSV format is easily readable by R. Then ask:

    a. Where are the variable names stored? <span style="color:grey">***The variable names are stored in the first row***</span>

    b. How are values of the variables separated? <span style="color:grey">***The values are separated by commas.***</span>

    c. If we were interested in using the online data, how would we obtain it? <span style="color:grey">***This is a
    challenging problem – one which students may not know how to answer at this
    point. The objective is for them to struggle with how they would obtain data and
    recognize that it is not always as simple as “export, upload, import.”***</span>

11. Split the class into their student teams and distribute the *Online Data-ing* handout ([LMR_3.19](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.19_Online Data-ing.pdf)).
Assign each team a different website (each page of the handout lists a different site) and have
them use this site to complete the questions in the handout.
<div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://stemc.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.19_Online Data-ing.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_3.19](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.19_Online Data-ing.pdf)</div>

12. Have each student team share their findings with one other team. They should have their website
displayed while discussing their results.

###**Class Scribes:**
One team of students will give a brief talk to discuss what they think the 3 most important topics of the
day were.

###<p style="background: black; color: white; text-align: center;">**Homework & Next 2 Days**</p>
For the next 4 days, students will collect data using their newly created Participatory Sensing campaign.

[<u>***Lab 3E: Scraping Web Data***</u>](lab3e.md)

[<u>***Lab 3F: Maps***</u>](lab3f.md)

Complete [Labs 3E](lab3e.md) and [3F](lab3f.md) prior to [Lesson 21](lesson21.md).
