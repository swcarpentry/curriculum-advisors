### July 2018 Meeting of the Software Carpentry Curriculum Advisory Committee

There was one meeting held:
- Monday, July 9, 2018 at 22:00:00

Attending:  
- Byron J. Smith
- Marianna Foos
- Erin Becker
- Madicken Munk
- Jonah Duckles
- Brittany Lasseigne

Detailed Agenda: https://docs.google.com/document/d/1omiazrV7k9BGwuy5sguxAXvOGQAcMwfEEtn9VYI3AHc/edit#heading=h.pdjengsh9uts (includes meeting notes)

#### Overall goals
1. Provide guidance to Maintainer teams for individual lessons about proposed major changes to their lessons.
2. Coordinate with the ‘Pathways’ subcommittee (a subgroup of the Maintainers) in proposing ordering of lessons and episodes in a 2-day workshop.

##### A1. Goals and rationale for having two distinct R and two distinct Python lessons
Background: SWC has two R (Programming with R and R for Reproducible Scientific Analysis ) 
and two Python (Programming with Python and Plotting and Programming in Python ) lessons. 
Community members (Maintainers) and workshop requesters (hosts) have asked for clarification about what 
the difference is between the two lessons for each language and which they should use for their workshop. 
One Maintainer proposes for the two different R lessons having one be using tidyverse and the other using 
only base R. 

Discussion:
- Major strategy question about whether we have one tight set of lessons or a broader set of lessons. 
- Choosing between these lessons can be confusing as a new instructor. 
- Adding more to the instructor notes pages to inform that choice.
- Need to make it clear what the goals and audience are for each.
- Add a rubric for each lesson to show exactly what is covered to help people choose.
- We need to have face-to-face onboardings. Just zoom meetings to say we need to talk about those lessons. (long term idea) 
- Be opinionated - provide options, but state that one lesson is better for novice learners or better for
a particular audience. 
- Francois is working on a survey to start collecting data on what parts of the lessons get taught. 
- This data can inform recommendations about what parts of the lesson new instructors should teach.
Consensus: Have better documentation about the scope of the lessons that is useful for people choosing the correct lesson. 

What are the differences?
- R for Rep Research is better suited for having a longer time period. The other for when time is limited. 
- The R inflammation lesson is a direct copy of the Python inflammation lesson. Bring in the data as a matrix (not a df). 
- The older Python version has general programming techniqes, numpy. The newer one has more about pandas and thinking about learner objectives. Newer lesson is potentially better designed. 

##### A2. Potential major revisions to the Git lesson
Background: There have been recurring conversations about both the story used for the Git lesson 
and whether Git should be taught through the command line or a GUI. These are both issues that the lesson 
Maintainers have asked for high-level guidance on. The CAC should discuss and provide advice about next steps 
forward on this lesson. 

Discussion: 
 - Should include command line and not just graphical interface.
- A lot of value in using the command line. Compliments the shell lesson. 
- Powerful to reinfoce concepts across lessons.
- An additional lesson adding some GUI features could be useful.
- Hesitant to modify the Git lesson to be specific to a GUI like the R Studio interface. Not open science software.
- Want our learners using version control - what is the best way to do that?
- Alternative stories as more relatable. Guac lesson (originally developed by Ivan?) or stone soup. Learners have responded well to this lesson.  
- Alternative is to teach a git clone as the very first command (when teaching shell). Tie everything together. 
By the time we have them do git status they can see that git has been tracking everything, very powerful. We can also have them do collaborative editing and go through the mechanics of a PR without understanding what’s happening. Tie the lessons better together. 
- Wolf man story line isn't engaging unless you know the joke behind it. Not approachable for novice instructors.
- Guac lesson is engaging. Also stone soup. 
- This lesson is the one people go off script for. 
- There are complete versions of the guac lesson somewhere. 
We’re asking someone to re-write the story. It’s not a small task but if they use the current guac version is easier. 
- Is it possible to consider adding the guac story? Maybe a transitional period where there is an alternative. 
- Can phase out the wolf man one if people are using the guac lesson. Prevents a huge shift. Can get data on relative usage. Asking a lot of git maintainers. 
- Same burden with having two R and two Python lessons.
Consensus: No consensus. Will continue to discuss asynchronously.

##### A3. Rearrangement of shell lesson
Not discussed due to time limitations.

##### A4. Specific requests for guidance from Maintainers
Background: The Python Maintainers have explicitly asked for guidance from the Curriculum Advisory 
Committee on these three issues:

- [Use of command line Python vs. Jupyter Notebooks](https://github.com/swcarpentry/python-novice-gapminder/issues/15)
- [Bokeh vs matplotlib for plotting](https://github.com/swcarpentry/python-novice-gapminder/issues/27)
- [Wide vs tall data format](https://github.com/swcarpentry/python-novice-gapminder/issues/230)

Action: Members of the CAC with Python experience will comment on those issues and make suggestions.

##### B. Coordination with the Pathways subcommittee
Background: It is widely recognized among the Maintainers and experienced Instructors that it is not 
possible to get through the full curriculum in a two day workshop. However, new Instructors find it 
difficult to decide what to leave out, and either end up teaching things in order (and potentially missing 
important things at the end) or teaching very quickly to try to squeeze everything in. The Pathways 
subcommittee is working to outline “pathways” through the curricula so that novice Instructors have 
guidance as to what should be included in a limited time frame. There will be multiple suggested pathways. 
The Pathways subcommittee includes (April Wright, Edwin Khoo, Madicken Munk, Anne Fouilloux, Daisie Huang, 
Diya Das, Jonah Duckles, and Naupaka Zimmerman) and has a Slack channel (#swc-pathways). Jonah and Madicken 
are also on the CAC, so should be able to provide an update about this subcommittees work and whether / 
how it will interface with the CAC. 

##### C. Coordination of data sets between SWC lessons

Background: One Maintainer raised as an agenda item the question of whether data sets should be synched 
between different SWC lessons. 

Not discussed due to time limitations.

#### Action items:
- Specific CAC members with Python experience will follow-up with Python Maintainers on specific issues raised.
- Continue discussion of Git story and come to decision asynchronously.
- Make plan for improving documentation about differences between R and Python lessons to provide clear guide for
choosing one of those lessons.
