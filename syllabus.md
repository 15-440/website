---
layout: default
comments: false
keywords:

title: Syllabus
description: All important things to know about the course. Course objectives, textbook, grading policies, etc.
buttons:
micro_nav: true
---

## Prerequisites

Because this course has a big project component, you must be proficient in C and programming on UNIX systems. We will use the [Go programming language](https://golang.org/) throughout the term. It is required that you have taken 15-213 and gotten a "C" or higher since many of the programming skills you will need are taught in that course. **However, if you received a C in 15-213, you must meet with your academic advisor to discuss your background before taking 15-440/640, perhaps taking an additional course to sharpen your systems skills. Your advisor must email us approval and an explanation of why you have sufficient background to take 15-440/640.**

If you have not taken 15-213/15-513 but believe you have taken an equivalent course (for example, master's students might have taken a similar course during their undergrad), you may join the waitlist. This year (Fall 2022) exceptionally, we have decided to allow these students to join the course _after_ the waitlist clears for students who have the proper prerequisites (if it clears). 

## Learning Objectives

After this course, students will have learned to...

- Implement and structure distributed systems programs.
- Write programs that can interoperate using well-defined protocols.
- Debug highly concurrent code that spans multiple programs running on multiple cores and machines.
- Reason about distributed algorithms for locking, synchronization and concurrency, scheduling, and replication.
- Use standard network communication primitives such as UDP and TCP.
- Understand the general properties of networked communication necessary for distributed systems programming in clusters and on the Internet.
- Employ and create common paradigms for easing the task of distributed systems programming, such as distributed filesystems, RPC, and MapReduce. Be able to clearly elucidate their benefits, drawbacks, and limitations.
- Identify the security challenges faced by distributed systems programs.
- Be able to select appropriate security solutions to meet the needs of commonly encountered distributed programming scenarios.

## Textbook

[**Distributed Systems**](https://www.distributed-systems.net/)
<br>Maarten Van Steen & Andrew S. Tanenbaum
<br>Published by CreateSpace Independent Publishing Platform, ISBN 978-1543057386, 3rd edition.

The lecture notes will be available after each lecture to assist with studying -- **please read them** as they often contain material that goes beyond just what we covered in lecture! For supplemental reading in particular areas, you may find one of the following texts, available from the library, helpful:

- **Computer Networks: A Systems Approach,** fourth edition, by Larry Peterson and Bruce Davie.
-  **Operating Systems Concepts** seventh edition, by Silberschatz, Galvin and Gagne
- For the projects, please see [Dave's Notes on Software Engineering for Systems Hackers](http://www.cs.cmu.edu/~dga/systems-se.pdf).
- For programming, see **Unix Network Programming: Networking APIs: Sockets and XTI (Volume 1)** by W. Richard Stevens.
- **Advanced Programming in the Unix Environment** by W. Richard Stevens, Addison-Wesley, 1993.

## Grading

Your final grade for the course will be based on the following weights for the components of the course. The weights of the individual projects will vary slightly by the difficulty of the project:

- 45% Projects
- 15% Homework
- 20% Midterm 1
- 20% Midterm 2

The midterms will be in-class, closed-book exams. While they may cover all material to that point in the class, their content will emphasize the material covered since the previous exam. The final exam will be a closed-book exam, covering material from the whole semester, with slight emphasis on material covered since the last midterm.

For more information about the project component, see the [assignments](/assignments) page.

The homework will combine both textbook-like questions as well as hands-on experimental exercises. There will be three homework assignments.

_Because of the importance of understanding both the theoretical and hands-on elements of systems, students must pass all three components of the course (homeworks, exams, and the projects) in order to receive a passing grade for the course._ This does not affect the actual letter grade assignment unless one of the components is not completed to a passing standard.

## Collaboration

Students are encouraged to talk to each other, to the TAs, to the instructors, or to anyone else about any of the assignments. Any assistance, though, must be limited to discussion of the problem and sketching general approaches to a solution. Each student must write out his or her own solutions to the homework. The project handouts have more detailed information about collaboration when working on the projects, but, basically, each programming project group must write their own code and documentation for the programming projects done as a group.

Consulting another student's or group's solution is prohibited, and submitted solutions may not be copied from any source. These and any other form of collaboration on assignments constitute cheating. If you have any question about whether some activity would constitute cheating, please feel free to ask the instructors.

You may not supply work that you complete during 15-440 to other students in future instances of this course or for use in future instances of this course (just as you may not use work completed by students who've taken the course previously). To be clear, this also means you may not leave your solutions publicly visible on the web, github, or any other platform.

<!-- ## Piazza Policy

This course uses the Piazza web site for answering questions. The home Piazza page for this course is at: [{{ site.course.piazza }}]({{ site.course.piazza }}). When posting questions on Piazza, students must keep in mind the collaboration guidelines noted above, and use those guidelines to determine:

- Whether to mark your post "private to the instructors" or public;
- How much detail and help to provide in an answer to a fellow student

Part of the learning process is struggling with the material until you arrive at the right insight for you to understand it. Posting too much detail in response to a request for assistance can impair learning. On the other hand, sometimes it's great to be nudged in the right direction when you're not able to get out of a rut. And, of course, misunderstandings of the assignment or tools available should be helped rapidly. Please use your best judgement when posting to the Piazza site, as if you were collaborating with your friends in person. A few rough guidelines:

- _Please do post and answer publicly:_ Misunderstandings of the assignment; clarifications about the requirements; bugs in the assignment spec or reference implementation or tests; small, detailed questions about the operation of system calls, functions, etc. Things that look like they'd go in the FAQ are good candidates for asking or answering.
- _Please don't post or answer publicly:_ More than a few lines of code; in-depth explanations of how your system works; questions about the best approach for architecting the system at a high level; questions about your grade; problems with your partner; etc.

Please use your judgement between these two examples. If you post privately, please let us know whether or not it would be OK to mark the post public if we feel it would be beneficial to the class to make it public. -->

## Late Policy

Take project and homework deadlines seriously. Our experience is that students often seriously underestimate the effort involved in programming assignments and projects. If we give you 4 weeks to complete an assignment, there is typically a reason. In the interest of fairness, we have adopted the following late policy:

- 2 late days are automatically granted for every assignment for valid reasons.
  - This applies for every project and homework individually.
  - Use it for any reason that you **honestly feel is a valid reason**.
  - No need to email us for permission.
- There is no grade penalty for these 2 late days.
- No TA help will be given after the official deadline (i.e., during late days).
- Work cannot be more than 2 days late.  Assignments will **NOT** be accepted 48 hours after the due date.
- If you are ill: If you have a medical note, you may turn in your assignments late without penalty. Please contact the instructors to arrange a reasonable replacement turn-in time. You must notify us before the due-date. Without a medical note, the above policies apply.

<!--
- The deadline for any assignment (except for those announced in advance) can be extended with a 10% penalty per day.
- No deadline can be extended by more than two days. Assignments will NOT be accepted 48 hours after the due date.
- If you are ill: If you have a medical note, you may turn in your assignments late without penalty. Please contact the instructors to arrange a reasonable replacement turn-in time. You must notify us before the due-date. Without a medical note, you will accessed the same late penalty as with any other reason for being late.
-->

## Re-Grading

If you think we made a mistake in grading, please submit a regrade request on Gradescope with a note explaining your concern no later than two weeks after the day the assignment was returned. We will have the question re-graded by the person responsible for grading that question.

Also note that in this course, project grades will be determined based on the final submission you make to Gradescope.

## Recordings

The course staff in 15-440 strongly encourage participation and asking questions during lectures, and to attend our office hours and interact there. Therefore, to protect the privacy of your fellow students, no audio or video recordings may be made of the class without the prior permission of the instructor. If the course staff make audio or video recordings of the course, we will notify the course before such recordings are made (and will make it extremely obvious because there will be a big camera in the back of the room...).

## Partner Problems

Please try to avoid having partner problems. Seriously! Share your hopes before they turn into concerns, your concerns before they have problems, and your problems before they inflate into crises.

Also, in order for the course staff to help you and your partner work through issues, or for us to provide an appropriate response to serious partner problems, you must contact us well before the relevant due date! While some problems can never be truly solved, it is likely that your career after CMU will you to sometimes "involve management" to address issues with co-workers, and will certainly require you to work out all sorts of problems with your co-workers. If you find yourself in a situation which you can't resolve, it will provide you with an opportunity to practice interacting with management.

A special case to avoid is coming to us a day or two before a major deadline to tell us that your partner has been ill (etc.) for multiple weeks. We, and thus you, have many more options if you inform us while a problem is developing, instead of after the fact.

## Take care of yourself

Do your best to maintain a healthy lifestyle this semester by eating well, exercising, avoiding drugs and alcohol, getting enough sleep and taking some time to relax. This will help you achieve your goals and cope with stress.

All of us benefit from support during times of struggle. You are not alone. There are many helpful resources available on campus and an important part of the college experience is learning how to ask for help. Asking for support sooner rather than later is often helpful.

If you or anyone you know experiences any academic stress, difficult life events, or feelings like anxiety or depression, we strongly encourage you to seek support. Counseling and Psychological Services (CaPS) is here to help: call 412-268-2922 and visit their website at [http://www.cmu.edu/counseling/](http://www.cmu.edu/counseling/). Consider reaching out to a friend, faculty or family member you trust for help getting connected to the support that can help.

## Diversity, Equity, and Inclusion

**We must treat every individual with respect.** We are diverse in many ways, and this diversity is fundamental to building and maintaining an equitable and inclusive campus community. Diversity can refer to multiple ways that we identify ourselves, including but not limited to race, color, national origin, language, sex, disability, age, sexual orientation, gender identity, religion, creed, ancestry, belief, veteran status, or genetic information. Each of these diverse identities, along with many others not mentioned here, shape the perspectives our students, faculty, and staff bring to our campus. We, at CMU, will work to promote diversity, equity and inclusion not only because diversity fuels excellence and innovation, but because we want to pursue justice. We acknowledge our imperfections while we also fully commit to the work, inside and outside of our classrooms, of building and sustaining a campus community that increasingly embraces these core values.

Each of us is responsible for creating a safer, more inclusive environment.

Unfortunately, incidents of bias or discrimination do occur, whether intentional or unintentional. They contribute to creating an unwelcoming environment for individuals and groups at the university. Therefore, the university encourages anyone who experiences or observes unfair or hostile treatment on the basis of identity to speak out for justice and support, within the moment of the incident or after the incident has passed. Anyone can share these experiences using the following resources:

- **Center for Student Diversity and Inclusion:** csdi@andrew.cmu.edu, (412) 268-2150
- **Report-It online anonymous reporting platform:** [reportit.net](http://www.reportit.net/) username: tartans password: plaid

All reports will be documented and deliberated to determine if there should be any following actions. Regardless of incident type, the university will use all shared experiences to transform our campus climate to be more equitable and just.
