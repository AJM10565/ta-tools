# ta-tools
A reference for new TA's at LUC (or somewhere else) based on my experience as a computer science TA for two years.

Dear Computer Science Teaching Assitant:

Sometimes I wonder about the nature of what it means to be a teaching assistant. 

Mastery of a subject improves as you're forced to explain what you know to others. Assuming a class of perfect students, a professor’s ability to teach can be tested by assessing the students on what they were taught. Assuming an ideal professor, the strength of the students to learn can be measured by evaluating them. In most cases, neither the professor nor the students are perfect. The job of the TA, therefore, is to help bridge the gap on both ends.
A Teaching Assistantship is a paid position. Your work is valuable to the university, to the professor, and to the students. You are tied to a professor or three each semester, and your function is to make their lives easier. -> Sometimes, I wonder about the merits of having student cohorts with an assigned TA and the outcomes of keeping the classes more or less the same but changing out the professor. Instead of four TA's each helping on one course for all the students, each cohort of students gets a learning assistant that grades there work and holds office hours, etc. But I digress <-

It is essential to set boundaries between work and life. Many of my TA professors have become confidants or friends, but should you feel that you are unable to bear your task load due to one or more professors overloading you do to those relationships, you need to act immediately to reaffirm your specific class duties. An overloaded TA does neither the students nor the professors any good.

How a CS TA is different from any other TA. -Automaton.


Warnings to excellent TAs.

How to make a bad TA, acceptable.


Best,
Allan Miller (LUC CS TA 2018-2020)


Guidelines for Grading Automation:

1) Set up a meeting with each professor, you will be the TA for before the first class begins. At this meeting, discuss their expectations for you during the semester, and any of the following modifications to student expectations (syllabus changes) will make your job more doable.

2) Every assignment should include a rubric from the professor explaining how to grade it (Each professor has there own style of producing this information, some are more straightforward than others, but critically, YOU must understand what the different areas mean in terms of how to assign integer values to fuzzy categories)

3) Most professors want to look over your grades before you make them public. Set up a system for that. 

4) Give yourself 1-2 weeks per Large Assignment (1a,2a,2b, etc.) to get the grades back to the student. I think of this as ~5 3-day chunks. Grade what you can in the first one. By the second, you should contact the professor about any common mistakes in the code and how you should approach if you can’t reason out on your own. Then 1-2 more chunks to finish up, do #3) [above - grade look over], then upload grades and follow release schedule. For 100-200 level courses halve the chunk times, the projects are more straightforward.

5) You should build a system for automatic Sakai grade uploads. There are some GitHub projects I can link you to, and Konstantin knows about some of them. There are two main approaches. One is to save the rubric and comments into a spreadsheet and populate comments about each sub-section. For any student for any subsection that is not full credit, cover your ass, and include a simple note about why this is the case. In general, these will follow a pattern for the class independent of rampant cheating, and you can simplify these to codes and have a table lookup for yourself to save time. The other method is to have a program that you can start and stop where it prompts you to enter the data in the command line. One positive feature of the second method is that you can automate some code reviews and have it auto-populate, although it requires more setup. The benefit of the prior is that you can easily share the table as a snapshot of your progress (although you can implement saving progress to a table in the first method).

6) You should probably pick up bash scripting and python scripting I/O. The first four weeks of the semester should be used for building and dry running your workflow on a fake Sakai project.

