##***<u>Lesson 21: Learning to Love XML</u>***

###**Objective:**
Students will understand the need for data to be stored in different ways - specifically, why it makes
sense for web data to be formatted as XML.

###**Materials:**
1. *Online Data-ing* handout ([LMR_3.19_Online Data-ing](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.19_Online Data-ing.pdf))

    **<u>Note:</u>** This should have been completed during the previous class.

2. Mountain Peak XML data found at:<br>
[http://gh.idsucla.org/ids_labs/extras/webdata/mountains.html](http://gh.idsucla.org/ids_labs/extras/webdata/mountains.html "http://gh.idsucla.org/ids_labs/extras/webdata/mountains.html")

    **<u>Note:</u>** Open with Google Chrome or Firefox browsers, NOT with Safari.

3. Projector

4. *Mountains – HTML vs. XML* handout ([LMR_3.20_Mountains - HTML vs. XML](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.20_Mountains - HTML vs. XML.pdf))

###**Vocabulary:**
XML

###**Essential Concepts:**

!!! note "Essential Concepts: "
    XML is a programming language that we use with our campaigns. We create basic
    XML "tags" in the code, which help us store data in a format we understand.

###**Lesson:**
1. Allow time for student teams to present their findings from the *Online Data-ing* handout
([LMR_3.19](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.19_Online Data-ing.pdf)) if there was not sufficient time during the previous lesson.

2. Remind students that in the previous lesson they learned about a variety of ways that data can be
presented online.

3. They've been working with comma separated (CSV) files and R data frames. Last time and in the
lab, they worked with HTML tables. Today they are going to learn how HTML can be displayed as
an XML table.

4. **XML**, or Extensible Mark up Language, is a popular format for storing data on the Internet. It is
useful because it creates readable web pages, and also because it allows programmers to easily
update values in the data table if those values change.

5. In pairs, ask students to brainstorm ways in which data that is found online is different than the
way we see data in RStudio. Then, create a class brainstorm from the student pair responses.

6. After the brainstorm, emphasize the following:

    100. RStudio’s default way to work with data is as large data frames (tables) where rows
    represent observations and columns represent variables.
    
    100. Data that is viewed online often has a different structure.
    
    100. Data structures found on the web might be displayed in tables, such as those on
    Wikipedia, or streams, such as Twitter, and might even include data spread across
    multiple sections of a web page, such as Yelp.
    
    Show students, on a projector, the Mountain Peak XML data found at<br>
    [http://gh.idsucla.org/ids_labs/extras/webdata/mountains.html](http://gh.idsucla.org/ids_labs/extras/webdata/mountains.html "http://gh.idsucla.org/ids_labs/extras/webdata/mountains.html")
    
    Ask students to look at the data and determine if they have seen it before. Hint: They have! It was
    the data they scraped during [Lab 3E](lab3e.md).

7. Once students figure out that the XML is just the same data as the website they scraped during
[Lab 3E](lab3e.md), distribute the *Mountains – HTML vs. XML* handout ([LMR_3.20](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.20_Mountains - HTML vs. XML.pdf)), which displays both
HTML and XML versions of the data.

    **<u>Note:</u>** The handout only includes the first 3 mountains.

    <div align="right"><iframe src="https://docs.google.com/viewerng/viewer?url=https://stemc.idsucla.org/IDS_Curriculum_v_5.0_preview/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.20_Mountains - HTML vs. XML.pdf&embedded=true" style=" width:420px;height:400px;" frameborder="0"></iframe><br>[LMR_3.20](../IDS_Curriculum_v_5.0/2_IDS_LMRs_v_5.0/IDS_LMR_Unit 3_v_5.0/LMR_3.20_Mountains - HTML vs. XML.pdf)</div>

8. Ask student pairs to answer the following:

    100. Why are certain XML tags indented in the XML version of the data? <span style="color:grey">***The indentations
    tell us how to structure the HTML table. For example, all the mountains are
    contained in the &lt;data> section, but are further tagged by each particular mountain
    within the &lt;mountain> and &lt;/mountain> tags. All information stored between those
    two tags will be displayed as one row of the HTML table.***</span>

    100. What are the role of tags (ex. &lt;state>) and end tags (ex. &lt;/state>) in the XML code?
    <span style="color:grey">***Tags tell us when a certain type of data begins, and end tags tell us when the data
    should end. In other words, it tells us where to find the specific values of a variable
    (ex. Alaska would be the value of the “state” variable since it is between the
    &lt;state> and &lt;/state> tags.***</span>

    100. Where are the variable names? <span style="color:grey">***The variable names can be found between each
    &lt;mountain> and &lt;/mountain> tags. Specifically, the first variable is “peak” and the
    last variable is “rank.”***</span>
    
    100. Where are the observations? <span style="color:grey">***The observations are located within each of the
    variable tags. For example, the observation “Mount McKinley (Denali)” is found
    between the &lt;peak> and &lt;/peak> tags.  ***</span>  

9. Assign student pairs one of the above questions to share out with the class. Student pairs that did
not receive an assignment must participate using the *Agree/Disagree* strategy.

10. As a class, discuss the answers to the questions above.

11. XML formats make it easier to display data on the web in a pleasant matter and make it easier for
programmers to find and alter data if the values change or if, for example, they wish to add a new
row to a table.

###**Class Scribes:**
One team of students will give a brief talk to discuss what they think the 3 most important topics of the
day were.

###<p style="background: black; color: white; text-align: center;">**Homework**</p>
For the next 3 days, students will collect data using the class’s newly created Participatory Sensing
campaign (see [Lessons 16](lesson16.md)-[18](lesson18.md)).

For homework, students should reflect about how XML and HTML data are displayed. They should
discuss when each format is appropriate.