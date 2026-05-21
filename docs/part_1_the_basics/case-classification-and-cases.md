---
created_date: 2023-11-20
staff:
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
maintainer: 
    - name: Kelly Schultz
      link: https://library.utoronto.ca/staff/kelly-schultz
title: Case Classification and Cases
parent: Part 1 - The Basics
nav_order: 7
layout: default
grand_parent: Introduction to NVivo 14/15 for Windows 
---
Case Classification and Cases
-----------------------------

If you have demographics or other important attributes that you want to incorporate into your study, case classifications and cases can help. For example, if you were analyzing interview transcripts, you might want to create a case classification called “Interviewees” with attributes such as their name, age, education, job title, etc. Once your case classification is in place that defines what characteristics you want to capture for your interviewees, you could then create one case for each interviewee with those attributes filled in. So for example, if you interviewed someone named Geeta, you would create a case called Geeta (or some ID number if needed for confidentiality) with information about Geeta. You would then use that Geeta case to code all the files/content that are associated with Geeta (where the Case acts like a code). Later you can then run queries that incorporate that information to answer questions such as, do executives talk more about sustainability? We will talk about how to run queries later in the tutorial.

You can manually create case classifications and cases by using the left menu, under Cases. You can right click on case classification and create a new classification or right click on cases to create a new case. But often times, it is easier and more common to upload a spreadsheet with all the information for the cases. Let’s try that now.

1. For our project, we have a spreadsheet called Interviewees. Open it up in Excel and take a look. It lists our interviewees and their attributes. NVivo would call this a classification sheet. Now close it.

    <img src="{{ '/assets/images/IntroNVivo1415WindowsExcelFileUpdate.png' | relative_url }}" alt='Excel file showing interviewees and attributes about then, such as Interview title, data centers managed, last major purchase or upgrade, role level, experience, and size of team. All attributes are categorical variables.' title='' width='1972' height='404' />

2. **Go to the Import menu, and from the Classifications drop\-down menu, select Import Classification Sheets...**

    <img src="{{ '/assets/images/NVivo15_intro_078.png' | relative_url }}" alt='Red box around the Import Ribbon and the Import Classification Sheet button.' title='' width='725' height='368' />

3. **Browse to the Interviewees spreadsheet and click on Next**.

    <img src="{{ '/assets/images/NVivo15_intro_079.png' | relative_url }}" alt='Import Classification Window with the browse button outlined in red.' title='' width='516' height='600' />

    <img src="{{ '/assets/images/nvivo_workshop_win_075.png' | relative_url }}" alt='Import Classification Sheet window file explorer at the workshop folder, Interviewees.xml selected. Red box around the open button.' title='' width='965' height='561' />

    <img src="{{ '/assets/images/NVivo15_intro_081.png' | relative_url }}" alt='Import Classification Window with the browse field completed, and Next outlined in red.' title='' width='513' height='600' />

4. **From the Classification Type drop\-down menu, select Case Classification**. Keep the rest of the defaults (i.e., everything has a checkmark) and **click on Next**.

    <img src="{{ '/assets/images/NVivo15_intro_082.png' | relative_url }}" alt='Import Classification Window with the classification type drop down menu open and the Case Classification option selected and outlined in red.' title='' width='508' height='598' />

5. Our classification sheet’s first column provides the name of each case (i.e., the interviewee’s first name). So **select As names** if not already selected. Also keep Create new cases if they do not exist checked so that our cases will be created. Then **click on Next**.

    <img src="{{ '/assets/images/NVivo15_intro_083.png' | relative_url }}" alt='Import Classification Window with As names selected and Next outlined in red.' title='' width='510' height='596' />

6. This last step allows us to specify how dates, times and numbers should be imported. We can keep the defaults here. **Click on Finish**.

    <img src="{{ '/assets/images/NVivo15_intro_084.png' | relative_url }}" alt='Import Classification Window with Finish outlined in red.' title='' width='513' height='596' />

7. Using the left menu, **under Cases, select Cases** to see our newly created cases. These cases can now be used in coding the same way codes are used.

    <img src="{{ '/assets/images/NVivo15_intro_085.png' | relative_url }}" alt='Left menu Cases opened and a red box around the Cases list.' title='' width='705' height='588' />

8. We can take advantage of NVivo’s autocoding features to allow us to identify the interviewee’s responses in a file and code them automatically into the appropriate case. **Using the left menu, under Data \> Files, go to the Interviews folder and right click on the interview transcript titled “Data Center Interview Transcript oct3\_2014”. Select Autocode…**

    <img src="{{ '/assets/images/NVivo15_intro_086.png' | relative_url }}" alt='In the interviews folder, a context menu for the last transcript is open with Auto Code... highlighted.' title='' width='845' height='746' />

9. You are presented with a wizard with different autocoding features that I encourage you to explore on your own. For now, let’s **select Speaker name**. This is going to automatically code text based on speaker name. Then **click on Next**.

    <img src="{{ '/assets/images/NVivo15_intro_087.png' | relative_url }}" alt='Auto Code Wizard Window with the Speaker name option selected and outlined in red. The Next button is highlighted.' title='' width='621' height='598' />

10. Our transcripts are formatted in a consistent manner so we can always pick out who is speaking because the text is labeled as “INT:” for the interviewer’s words, and the person’s name in capital letters followed by a colon for the interviewee’s words. We need to tell NVivo who are all the unique speakers in this document. **Under Enter all speakers, type in “INT” and hit Enter. Then type in BASEL and hit the TAB key.** You should check the preview below to confirm that NVivo is picking up each unique speaker by highlighting them in different colours. If it looks correct, **click on Next**.

    <img src="{{ '/assets/images/NVivo15_intro_088.png' | relative_url }}" alt='Auto Code Wizard Window with the a red box around the Enter all Speakers field, Preview, and the Next button.' title='' width='620' height='599' />

11. **Make sure Add to existing classification is selected and from the drop\-down next to it, Interviewees is selected. Then click on Finish.** This should code everything that Basel said in the transcript with Basel’s case.

    <img src="{{ '/assets/images/NVivo15_intro_089.png' | relative_url }}" alt='Auto Code Wizard Window with a red box around Add to Existing classification and finish.' title='' width='619' height='600' />

12. **Using the left menu, under Cases, click on Cases to see cases** again. **Double click on the BASEL case**. You should see everything that Basel said in his interview. These words are coded to this case. The BASEL case code is now linked to Basel’s interview responses.

    <img src="{{ '/assets/images/NVivo15_intro_090.png' | relative_url }}" alt='Cases open with Basel selected and a red box around the Basel window.' title='' width='1337' height='814' />

**Technique**: [Qualitative Data Analysis](https://mdlutoronto.github.io/tutorials-search/?technique=Qualitative+Data+Analysis) \| **Tools**: [NVivo](https://mdlutoronto.github.io/tutorials-search/?tool=NVivo)   