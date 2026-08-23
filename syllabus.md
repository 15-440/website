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

<!-- If you have not taken 15-213/15-513 but believe you have taken an equivalent course (for example, master's students might have taken a similar course during their undergrad), you may join the waitlist. This year (Fall 2026) exceptionally, we have decided to allow these students to join the course _after_ the waitlist clears for students who have the proper prerequisites (if it clears). -->

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

Your final grade for the course will be based on the following weights for the components of the course. The weights of the individual projects will vary by the difficulty of the project:

- 36% Projects (5% P0, 8% P1, 5% P2, 18% P3)
- 5% Homework
- 15% Quizzes
- 20% Midterm Exam
- 20% Final Exam 
- 4% Participation

All quizzes and exams will be closed note, closed book.  

Participation will be recorded using in-class, multiple-choice polls. While these polls are evaluated based purely on participation, selecting the correct answers will serve as a tool to assess your grasp of the lecture content. You can access the class poll at [www.pollev.com/cmu15440](https://www.pollev.com/cmu15440). **Please make sure you are signed-in with your CMU Andrew email address, otherwise your participation will not be documented.**

_Because of the importance of understanding both the theoretical and hands-on elements of systems, students must pass all three components of the course (homeworks, quizzes and exams, and the projects) to receive a passing grade for the course._ This does not affect the actual letter grade assignment unless one of the components is not completed to a passing standard.

## AI Policy

We believe that the distributed systems concepts you learn in this course matter, and that learning them well is critically important for the future systems that you design and build; subtle concurrency anomalies, race conditions, and partial failures can compromise safety-critical infrastructure.  There is increasingly strong evidence that AI use can interfere with learning.  We also believe, however, that authentic learning experiences (including the use of modern AI) provide rich value, and we are philosophically opposed to creating a policy that we can't equitably enforce.  

With that in mind:

- **Projects:**  Each student is responsible for understanding every line of code submitted, regardless of which partner or agent drafted it.  You may use AI tools, including agents, to help craft your solutions to the programming projects.  Although the use of autonomous agents is not prohibited, we strongly recommend against the use of tools that generate substantial code without your direct control.  You must know how and why your solution works, and we expect you to be able to produce solutions to similar problems on paper, including the generation of syntactically correct programs, without the use of AI or other external tools.
- **Homeworks:**  We believe that the use of AI tools on homework is much more likely to interfere with learning than to help you learn.  Although we don't prohibit the use of AI tools, we strongly recommend that you complete the homeworks by hand, using AI only as a high-level resource similar to how you might use a Wikipedia page. Our homeworks are designed to help you understand key concepts, some of which will be tested on written quizzes and exams.  
- **Quizzes, exams, and presentations:**  All external resources, including AI tools, are prohibited during project presentations and on quizzes and exams.
- **Disclosure and attribution:**  If you use AI tools to assist with a project or homework submission, you must include an explicit disclosure in your submission, specifying: (1) the platform(s) and specific model(s) used; (2) the type of tool use (e.g., code autocompletion, debugging assistance, agent-based code generation); and (3) how it was used (e.g., generated 50% of the code, helped in debugging, generated test cases, etc.).  It is an academic integrity violation to not fully disclose the use of AI tools.
- **Course material and data privacy:**  You are strictly prohibited from feeding course-supplied content (including project starter code, assignment writeups, test suites, and homework problems) into platforms whose data retention or training policies could leak course material into future models.  By default, consumer accounts on platforms such as OpenAI ChatGPT, Google Gemini, and Anthropic Claude allow consumer data to be used for model training.  Please see [CMU’s AI Safety page](https://www.cmu.edu/computing/services/ai/meet-ai/secure-ai.html) for a list of platforms that can be safely used with non-sharable data, when used via your CMU Andrew account.

Our course is designed to be completed successfully without the use of AI tools.  We encourage you to use AI tools thoughtfully in ways to improve your learning rather than as a way to save time or effort.

## Academic Integrity and Collaboration Policy

We expect that your work on assignments, projects, and exams will be your own work. Thus, you may not copy any part of a solution to a problem that was written by another student, or was developed together with another student, or was copied from another unauthorized source such as the Internet. You may not look at another student's solution, even if you have completed your own, nor may you knowingly give your solution to another student or leave your solution where another student can see it.

You may not possess smart glasses or have a phone or other computing device visible during a quiz or exam.  Possessing smart glasses during a quiz or exam will be considered an academic integrity violation, even if you are not wearing them.

Here are some examples of behavior that are inappropriate:

- Copying (or retyping) files, parts of files (such as source code, written text, or unit tests), quiz solutions, or exam solutions from another person or source, either in draft or final form, even if the file permissions are incorrectly set to allow it. This behavior is still clearly inappropriate even if you make modifications (such as style changes or minor logic modifications) from the original source.
- Searching for or viewing a current or past student's homework solution.
- Allowing someone else to view or copy your code, written assignment, quiz, or exam, either in draft or final form.
- Getting help that you do not fully understand or from someone whom you do not acknowledge on your solution.
- Coaching others step-by-step without them understanding your help.
- Writing, using, or submitting a program that attempts to alter or erase grading information or otherwise compromise security of course resources.
- Lying to course staff.
- Making your work publicly available in a way that other students (current or future) can access your solutions, even if others’ access is accidental or incidental to your goals.
- If any of your work contains any statement that was not written by you, you must put it in quotes and cite the source. If you are paraphrasing an idea you read elsewhere, you must acknowledge the source. Using existing material without proper citation is plagiarism, a form of cheating. If there is any question about whether the material is permitted, you must get permission in advance.

It is not considered cheating to clarify vague points in the assignments, lectures, lecture notes, or to give help or receive help in using the computer systems, compilers, debuggers, profilers, or other facilities.

Some projects are specifically noted as group projects. For these, interpret "you" in the preceeding paragraphs to mean "you and your partner(s)."

Any violation of this policy is cheating. The minimum penalty for cheating (including plagiarism) will be a zero grade for the whole assignment; a typical penalty will be -100% on the assignment. Dishonesty while discussing an academic integrity issue (i.e. lying to course staff) usually results in an 'R' in the course. All violations of this collaboration policy will be referred to the appropriate University disciplinary board, with possible additional disciplinary action. For more information, see the University Policy on Academic Integrity.

There is no statute of limitations for violations of the collaboration policy; penalties may be assessed (and referred to the university disciplinary board) after you have completed the course, and some requirements of the collaboration policy (such as restrictions on you posting your solutions) extend beyond your completion of the course.

If you have any question about how this policy applies in a particular situation, ask the instructors or TAs for clarification.

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

- 10 late days are given for each student to use on any project or homework deadline.
  - Use it for any reason that you **honestly feel is a valid reason**.
  - No need to email us for permission.
  - For partnered projects, late days will be deducted from each partner.
    - If one partner runs out of late days, no late days can be used. 
  - You are responsible for keeping track of the number of late days you have used.
- **At most 3 late days** can be used for each deadline. 
- There is no grade penalty for these 3 late days.
- Work cannot be more than 3 days late.  Assignments will **NOT** be accepted 72 hours after the due date.
- After expending all late days, any late work will **NOT** be accepted.
- No TA help will be given after the official deadline (i.e., during late days).
- If you have a **serious** medical emergency (e.g. you've been hospitalized), and your academic advisor can verify this, we will find a way to accommodate you. Please contact the [instructors mailing list](mailto:ds-staff-F26-private@andrew.cmu.edu) to arrange a reasonable replacement turn-in time. Keep in mind that catching a cold, going to the eye doctor, getting food poisoning, etc, don't count as a serious medical emergency– in these cases, the above policy of up to 3 late days per assignment (out of a total of 10 overall) apply.

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
