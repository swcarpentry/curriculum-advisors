November Meeting of the Software Carpentry Curriculum Advisory Committee
There was one meeting held:

Tuesday,November, 2022 from 20:00 to 21:00 UTC

In Attendance:
 Byron J. Smith (time-keeper)
Georgina Pegu
James Balamuta (note-taker)
Alex Pakalniskis (facilitator)
Menglan Xiang

Detailed Agenda: https://pad.carpentries.org/Q4_meeting_for_the_swc_cac (including notes).

Agenda/Notes:
Welcome to the SWC CAC and Introductions (20:00 UTC - 10 minutes)
SWC CAC Expectations and Operations (20:10 UTC - 15 minutes)
Replacing assertions with exceptions for defensive programming (20:25 UTC - 10 minutes) <https://github.com/swcarpentry/curriculum-advisors/issues/1>
Potential survey of community members about lessons (20:35 UTC - 15 minutes) <https://github.com/swcarpentry/curriculum-advisors/issues/2>
Matters arising and overflow (20:50 UTC - 10 minutes)

Discussion: Async GitHub discussions are they okay? 
1. We prefer to handle as many non-complex issues by using GitHub Issues.

2. We need to have some sense of priority: Urgent, Medium, Low.
3. If no urgency, they get left and forgotten. 
4. Scan e-mails. Maybe Byron or another to send a summary or check-in e-mail? 
Open issues? 
Theme of the week? If you haven't looked at this topic, take a look at the topic or forever hold your peace.

Discussion:Assertions with exceptions for defensive programming: https://github.com/swcarpentry/curriculum-advisors/issues/1
1. No deadline 
2. Proposed Changes: https://damienirving.github.io/python-novice-inflammation/10-defensive/index.html 
Original: https://swcarpentry.github.io/python-novice-inflammation/10-defensive/index.html 
PR: https://github.com/swcarpentry/python-novice-inflammation/pull/981/files
3. Worries: Cognitive overload, introduction of the `if` structure, workshop timing preventing discussion of core content (defensive programming)
Technical concerns: The `assert` keyword can be optimized out if `-O` is used. Is this the best practice? 
* Either way would be sound. 
* For exceptions: Exceptions should be favoured because more `try-catch` examples are seen in  practice
* Against exceptions:  Exceptions  would impact being able to discuss the defensive programming component as that is moved further inside of the lesson.
Vote: 2 against, 2 for, 2 abstained

Discussion: Potential survey of community members about lessons
1. Originally brought up by Annajiat 
https://github.com/swcarpentry/curriculum-advisors/issues/2 
2. Priortization of content for workshops that are two-days, one-day, half-day.
3. Questions: Given X amount of time to teach it, would you teach: Always, sometimes, never. 

- Full half-day session: We would always get to pull requests. 

- Instead of a 6 hour workshop, is it an interweave vs. solid block? 
- Interweave: 2 hours every week for 3 weeks? 
- What kind of users are coming into the workshop?
- Are they only teaching python if they have a 2x 4 hour session blocks? 
- What's the format of that? Is it split up over time?
- Do they have a sense of how these lessons are being used? 
- What is in the workshop format vs. what is hybrid? 
Lunch time conversation is very valuable in person.

Action points for potential survey:
* Maybe use GitHub to figure out our objectives and, then, construct questions.
* Next quarterly meeting: Send out the Survey. 
* Need to know what "Send out" means (reach out to leadership)? 
* Reach out to author to see if they wish to be involved? Set a deadline of end of December?

Overall action points before next quarterly meeting:
* E-mail blast at the end of the week to emphasize whether we need to make a vote or read
* To 10-defensive lesson maintainers, we recommend:
    - placing the `assert` methods first to ensure defensive programming would be covered
    - when adding exceptions make sure to emphasize in the exception section that -O would remove Assertions but not Exceptions. 
* Reach out to Annajiat: does he want to lead the survey on workshop content. What material is being taught? Workshop format vs Hybrid format?
* Range of Dates: January 23rd - February 3rd




