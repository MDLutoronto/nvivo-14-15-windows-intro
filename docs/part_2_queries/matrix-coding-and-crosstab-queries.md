---
created_date: 2023-11-20
staff:
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
maintainer: 
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
title: Matrix Coding and Crosstab Queries
parent: Part 2 - Queries
nav_order: 1
layout: default
---
Matrix Coding and Crosstab Queries
----------------------------------

1. Next up are Matrix Coding queries. These allow you to see coding intersections between two lists of items. It is called Matrix Coding Query in the Explore Ribbon or described as “Find coding intersections between two lists of items” in the Query Wizard. So for example, let’s say you want to see which interviewees (based on cases) had the most positive and negative attitudes (based on coding) \- you can do this with a Matrix Coding query. **Go to the Explore menu and select Matrix Coding Query**.

    <img src="{{ '/assets/images/MatrixCrosstab_1.png' | relative_url }}" alt='In the top Ribbon, under the explore tab, a red box around Matrix Coding Query.' title='' width='1017' height='123' />

2. This query is formed using drag and drop. First, **using the left menu, under Cases, go to People, and then expand Interview Participants**.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_068.png' | relative_url }}" alt='In the left menu, under Cases, a red box around the People folder. In the People folder, a red box around the expand button for Interview Participants.' title='' width='1425' height='739' />

3. **Highlight all of the interviewees by clicking on the first one, holding down the Shift key, and then clicking on the last one**. Then **drag and drop them on the left side of the matrix query under Rows**.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_069.png' | relative_url }}" alt='Under Interview Participants, all cases are selected and outlined in red, with an arrow pointing to the Rows field of the Matrix Coding Query window.' title='' width='1203' height='921' />

4. Then, **using the left menu, under Coding, click on Codes**, and then **go to Attitude and expand it**.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_070.png' | relative_url }}" alt='In the left menu, under Coding, a red box around the Codes folder. In the Nodes folder, a red box around the expand button for Attitude.' title='' width='616' height='688' />

5. **Highlight all the attitude child codes** and then **drag and drop them on the right side** of the matrix query under Columns.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_071.png' | relative_url }}" alt='Under Attitude, all child codes are selected and outlined in red, with an arrow pointing to the Columns field of the Matrix Coding Query window.' title='' width='1208' height='637' />

6. **Click on Run Query** to see the results. You will see a grid or matrix with the number of references where those codes and cases intersect.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_072.png' | relative_url }}" alt='In the Matrix Coding Query Results Preview Window, a red box around Run Query.' title='' width='981' height='224' />

7. To see the results more clearly and point out interesting patterns,use the shading options available from the top left of the Matrix ribbon. **Scroll down and select the purple option**.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_073.png' | relative_url }}" alt='In the Ribbon, the Matrix tab is outlined in red and under the Matrix tab, the second Cell Shading option is highlighted.' title='' width='1443' height='720' />

8. We can see that the darker the purple, the more two items intersect. In this case, we can see for example that Barbara had strong positive and negative references, Thomas’s interview was more negative than positive, and William’s was only positive.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_074.png' | relative_url }}" alt='In the Matrix Coding Query Results window, a red box around the results table.' title='' width='991' height='611' />

9. **Click on the Chart tab on the right**.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_075.png' | relative_url }}" alt='In the Matrix Coding Query Results Preview Window, a red box around the Chart tab.' title='' width='989' height='591' />

10. You will see the results displayed in a chart. The default is a 3D bar graph.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_076.png' | relative_url }}" alt='In the Query Results Window, the Chart preview is highlighted.' title='' width='1020' height='1048' />

11. You can select other chart types from the Chart ribbon above to change it. Again, NVivo’s visualization options are limited, and these graphs are often not the best way to display your data. In this scenario the shaded matrix view offers a clear visualization of the data.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_077_0.png' | relative_url }}" alt='On the ribbon, the visuals tab is outlined in red. A red box around the Type options.' title='' width='1105' height='1110' />

12. **Click on the Coding Matrix tab on the right**. Then right click on the table, and go to Cell Contents. You will see that the default number shown is coding references, but there are a lot of other options to consider to explore the data in different ways. For example, change it to Words Coded, you can see that Charles had a lot of negative things to say. **Once you have finished examining the results, close the query results tab**.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_078.png' | relative_url }}" alt='In the Matrix Coding Query Results Preview window, a red box around the Coding Matrix tab. An open context menu for the results table with the cell content dropdown menu open and outlined in red, and with Coding References checked..' title='' width='1134' height='730' />

13. Let’s move on to the last query we will look at, Crosstab queries. Crosstab queries are similar to Matrix Coding queries, but you can expand out all the categories for an attribute along the columns automatically. For example, to determine which codes came up most by Township of respondent. **Go to the Explore menu, and from the Queries drop\-down menu, select Crosstab**.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_079.png' | relative_url }}" alt='In the top Ribbon, under the explore tab, a red box around Queries and Crosstab.' title='' width='874' height='248' />

14. This query is partially formed using drag and drop. First, **using the left menu, under Coding, select Codes**. **Highlight all the top\-level codes** (make sure none of the Code categories are expanded) and **then drag and drop them on the left side of the Crosstab query tab under Codes**.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_080.png' | relative_url }}" alt='In the left menu, under Coding, a red box around the Codes folder. Under Codes, all codes are selected and outlined in red, with an arrow pointing to the codes field of the Crosstab Query window.' title='' width='1843' height='762' />

15. The default option for the Crosstab codes against is attributes. **For Classification, select Person, and for Attribute 1, select Township, from the drop\-down menus**. This Crosstab query will create a matrix where the codes are along the rows, and for the columns, it will take all the values of one attribute (in this case, Township) and use those for the column headers. Then it will tally where they intersect.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_081.png' | relative_url }}" alt='In the Crosstab Query Window, Crosstab codes against is set to Attributes, Classification is set to person, and Attribute 1 is set to Township. A red box outlines these three settings.' title='' width='1081' height='226' />

16. **Click on Run Query to see the results**. You will see a matrix with the number of references where those codes and attributes intersect.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_082.png' | relative_url }}" alt='In the Crosstab Query window, a red box around Run Query.' title='' width='1080' height='220' />

17. Like with the Matrix Coding, **use the shading options available from the top left of the Crosstab ribbon to see the patterns more clearly**. If we select the green option, we can see that the darker the green, the more two items intersect.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_083.png' | relative_url }}" alt='In the Crosstab Query Results window, a red box around the results table. In the menu bar, the green shading selected is highlighted. ' title='' width='1486' height='596' />

18. Again, we can **right click on the table, and go to Cell Contents to change what is displayed**. In this case, **try selecting Coding Presence**. Often times you might not have a big enough data set to gain meaning from the numerical values for coding references, for example, but you can at least see where there is an intersection at all or not. For example, we see that the code of a “Sense of Community” has only been used on data for a few townships. Normally people don’t report these numbers, but use them to gain insight into their project.

    <img src="{{ '/assets/images/NVivo15_intro_pt2_084.png' | relative_url }}" alt='In the Crosstab Query window, a context menu for the results table with the Cell Content dropdown menu open and a red box around Coding Presence.' title='' width='1025' height='302' /><img src="{{ '/assets/images/NVivo15_intro_pt2_085.png' | relative_url }}" alt='In the Crosstab Query window, a red box outlines the results table.' title='' width='1053' height='448' />

19. You’ll see that NVivo also offers three other query types: Coding Comparison Queries, which are used when working on a team to see how much agreement there is between team members on coding, and Compound and Group Queries that are used to create more complicated queries combining elements from the other query types we have discussed. While these will not be covered in this tutorial, you are encouraged to play around with these queries on your own time to learn more.

 

### Test Your Understanding 3

Using the Explore menu options run a Matrix Coding query on social media content only, where the columns are the attitude child codes (positive, negative, etc.) and the rows are the remaining top\-level codes (Balance, Economy, etc.). What two codes have the most negative references?

Next run a Crosstab query, where the rows are the top\-level codes (Balance, Economy, etc.) and the Person attribute is Education Level. What code was coded the most by coding references for people whose highest level of education completed is undergraduate college?

Click [here](https://mdlutoronto.github.io/nvivo-14-15-windows-intro/part_2_queries/test-your-understanding-answers) for the answers.

**Technique**: [Qualitative Data Analysis](https://mdlutoronto.github.io/tutorials-search/?technique=Qualitative+Data+Analysis) \| **Tools**: [NVivo](https://mdlutoronto.github.io/tutorials-search/?tool=NVivo)   