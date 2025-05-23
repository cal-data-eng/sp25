---
layout: page
title: Syllabus
nav_order: 2
description: >-
    Data Engineering
markdown: kramdown

lec_info: TuTh 9:30am, Lewis 100
---

<!-- Common md links can go here -->
[schedule]: {{ site.baseurl }}/

# Syllabus
{:.no_toc}

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## About Data 101 (Info 258)

This course will cover the principles and practices of managing data at scale, with a focus on use cases in data analysis and machine learning. We will cover the entire life cycle of data management and science, ranging from data preparation to exploration, visualization and analysis, to machine learning and collaboration.

The class will balance foundational concerns with exposure to practical languages, tools, and real-world concerns. We will study the foundations of prevalent data models in use today, including relations, tensors, and dataframes, and mappings between them. We will study SQL as a means to query and manipulate data at scale, including analytical challenges like sampling, aggregation and windowing, and performance concerns like views and indexes, data models, query processing and optimization, and transactions, all from a user perspective. We will study the foundations and realities of data preparation, including hands-on work with real-world data using standard Python and SQL frameworks. We will explore data exploration modalities for non-programmers, including the fundamentals behind spreadsheet systems and interactive visual analytics packages. We will look at approaches for managing the lifecycle of data science, including the establishment, monitoring, and maintenance of data pipelines for both analytics and machine learning. Time permitting, we will look at the specifics of ML pipelines including data validation, training, prediction serving and feedback loops, as well as technologies for representing, moving, sharing, and caching data including event streaming systems, key-value/document stores, in-memory and on-disk representation formats, log analytics, and search engines.

**Textbook**: There is no official textbook for Data 101 this semester; we will provide (informal) course notes that will be released with the respective lectures.

### Prerequisites
COMPSCI C100/DATA C100/STAT C100 or COMPSCI 189 or INFO 251 or DATA 144/INFO 254 or equivalent upper-division course in data science. COMPSCI 61B or INFO 206B or equivalent courses in programming. This class will not assume deep experience with databases or big data solutions.

### Info 258 vs Data 101

Data 101 is the same class as Info 258; there are some small differences with respect to the weightage for the optional final project (basically: this is optional for Data 101 but compulsory for Info 258) but everything else stays the same.

### Enrollment
See our [FAQ page]({{site.course_faq}}).

### Communications
* **Ed** is our primary method of communication and making announcements, and you are responsible for checking it frequently. We will also make assignment "megathreads" where you can public ask questions about the course assignments.
* **bCourses** will only have lecture webcasts, if any.
* **Gradescope** is where all assignments are submitted.
* **[{{site.course_email}}](mailto:{{site.course_email}})** is the course staff email and is for private logistical student support and DSP accommodations. This email monitored by both the instructor and a core set of staff to ensure fastest response. Please only contact the course instructor directly for matters that require strict privacy and/or their personal attention.

## Course Culture
Students taking Data C101 (Info 258) come from a wide range of backgrounds. We hope to foster an inclusive and safe learning environment based on curiosity rather than competition. All members of the course community — the instructors, students, and course staff — are expected to treat each other with courtesy and respect. Some of the responsibility for that lies with the staff, but a lot of it ultimately rests with you, the students.


### Be Aware of Your Actions
Sometimes, the little things add up to creating an unwelcoming culture to some students. For example, you and a friend may think you are sharing in a private joke about other races, majors, genders, abilities, cultures, etc. but this can have adverse effects on classmates who overhear it. There is a great deal of research on something called “stereotype threat”: research finds that simply reminding someone that they belong to a particular culture or share a particular identity (on whatever dimension) can interfere with their course performance.

Stereotype threat works both ways: you can assume that a student will struggle based on who they appear to be, or you can assume that a student is doing great based on who they appear to be. Both are potentially harmful.

Bear in mind that diversity has many facets, some of which are not visible. Your classmates may have medical conditions (physical or mental), personal situations (financial, family, etc.), or interests that aren’t common to most students in the course. Another aspect of professionalism is avoiding comments that (likely unintentionally) put down colleagues for situations they cannot control. Bragging in open space that an assignment is easy or “crazy,” for example, can send subtle cues that discourage classmates who are dealing with issues that you can’t see. Please take care, so we can create a class in which all students feel supported and respected.

### Be an Adult
Beyond the slips that many of us make unintentionally are a host of behaviors that the course staff, department, and university do not tolerate. These are generally classified under the term harassment; sexual harassment is a specific form that is governed by federal laws known as Title IX. UC Berkeley’s [Title IX website](https://ophd.berkeley.edu/){:target="_blank"} provides many resources for understanding the terms, procedures, and policies around harassment. Make sure you are aware enough of these issues to avoid crossing a line in your interactions with other students. For example, repeatedly asking another student out on a date after they have said no can cross this line.

Your reaction to this topic might be to laugh it off, or to make or think snide remarks about “political correctness” or jokes about consent or other things. You might think people just need to grow a thicker skin or learn to take a joke. This isn’t your decision to make. Research shows the consequences (emotional as well as physical) on people who experience harassment. When your behavior forces another student to focus on something other than their education, you have crossed a line. You have no right to take someone else’s education away from them.

### Issues with Course Staff

From the Data Science Department: [Data Science Undergraduate Studies](https://data.berkeley.edu/academics/undergraduate-programs){:target="_blank"} faculty and staff are committed to creating a community where every person feels [respected, included, and supported](https://data.berkeley.edu/equity-inclusion){:target="_blank"}. We recognize that incidents may happen, sometimes unintentionally, that run counter to this goal. There are many things we can do to try to improve the climate for students, but we need to understand where the challenges lie. **If you experience a remark, or disrespectful treatment, or if you feel you are being ignored, excluded or marginalized in a course or program-related activity**, please speak up. Consider talking to your instructor, but you are also welcome to contact Executive Director Christina Teller at [cpteller@berkeley.edu](mailto:cpteller@berkeley.edu) or report an incident anonymously through this [online form](https://docs.google.com/forms/d/e/1FAIpQLSfBwaUe7VMQz6VzkYFvf4KYwNSTve9iJlBSQyAmsXoSE0LnWw/viewform){:target="_blank"}.

As course staff, we are committed to creating a learning environment welcoming of all students that supports a diversity of thoughts, perspectives and experiences and respects your identities and backgrounds (including race, ethnicity, nationality, gender identity, socioeconomic class, sexual orientation, language, religion, ability, and more.) To help accomplish this:

- If your name and/or pronouns differ from those that appear in your official records, please let us know.
- If you feel like your performance in the class is being affected by your experiences outside of class (e.g., family matters, current events), please don’t hesitate to come and talk with us. We want to be resources for you.
- We (like many people) are still in the process of learning about diverse perspectives and identities. If something was said in class (by anyone) that made you feel uncomfortable, please talk to us about it.
- While the course staff understands that improving diversity, equity, and inclusion (DEI) are not enough to overcome systemic issues in academia such as racism, queerphobia, and other forms of discrimination and hatred, we also recognize the importance of DEI work.
    - The Data Science Department has some resources available at [https://data.berkeley.edu/about/diversity-equity-and-inclusion](https://data.berkeley.edu/about/diversity-equity-and-inclusion){:target="_blank"}.
    - There’s also a great set of resources available at [https://eecs.berkeley.edu/resources/students/grievances](https://eecs.berkeley.edu/resources/students/grievances){:target="_blank"}.
- If there are other resources you think we should list here, let us know!

**We will take all complaints about unprofessional or discriminatory behavior seriously.**

### Misuse of Course Resources
If individuals are disrespectful to students, course staff, or others via course resources, they will lose access to course resources. E.g., if someone is unkind in the course forum, their account will be removed from the course forum. If someone is unkind in the classroom, they will be asked to leave the classroom.

## Course Components

### Lecture

There are two 80-minute lectures per week, **{{page.lec_info}}**. You can attend in-person or online, or watch the recording. The class [schedule][schedule] will contain links to video recordings posted within 24 hours after the corresponding class.

**Lecture check-ins**: Every lecture (starting the 3rd lecture, **1/28**, onwards) will have a short series of questions to help check your understanding of the material. You will have one week to complete each check-in; no late submissions will be accepted. Each check-in is worth 1 point and is graded on completeness as follows:
  * Synchronous (during lecture) complete at least one question.
  * Asynchronous (after lecture, within 1 week) complete all questions.

  In both cases, navigate to [slido.com](https://www.slido.com/)

### Discussion

This course also includes one weekly 50-minute discussion section held on Thursdays and Fridays. This section will help you synthesize materials via worksheets and activities and is good practice for the final exam. Handouts wil be posted on the class [Schedule][schedule]. Section attendance is not required, but you are strongly encouraged to practice the material on your own time. Discussion begins with the first week of classes.

### Projects

There will be five (5) programming assignments released throughout the semester (see the [schedule][schedule]). Generally, you will have one to two weeks to complete each project. Projects are graded on accuracy and are almost equally weighted, with the exception of Project 0 (weighted half of the other projects). Project deadlines are generally **Wednesday 5pm**.

### Homework Assignments

There will be five (5) homework assignments released on Gradescope throughout the semester. You will have one to two weeks to complete short written assignments. Each homework assignment consists of multiple choice and short answer questions. Homework assignments are graded on accuracy and are equally weighted. Homework assignment deadlines are generally **Wednesday 5pm**.

### Exams

This course has two exams:
* Midterm exam: Wednesday, March 12th, 6:00pm - 8:00pm
* Final exam: Wednesday, May 14th, 11:30am - 2:30pm

**Exams are offered in-person only.** It is your responsibility to ensure that you are not enrolled in another class that conflicts with our midterm or final exam time. All details will be posted on Ed.

### Final Project

We will have an **optional** final course project this semester. This will be an open-ended exploration of data systems, and you will submit a written final report. <s>Details to be released after the midterm.</s> Released!

### Office Hours

Office Hours are a great place to get help from course staff and to find study partners for this course. You can find a list of all office hours on the [calendar]({{site.base_url}}/calendar) page. There are two categories of office hours:
* **TA/Tutor office hours**, held weekly in **Warren 101B**. Attend to get help with homework assignments, projects, or any other content-related questions.
* **Instructor office hours**, held weekly in **Soda 787** are for content-related questions, but also general course questions, data science advising, or perspectives on academia/industry. These are not intended for homework or project questions. Feel free to bring tea/coffee and/or a reusable mug.

## Grading
Letter grades for the course will be based on your overall score in the class. The default scheme for Data 101 is without the optional final project:

{: .table }
| **Component** | **Weight<br/>(default)** | **Weight<br/>(Final Project)** | **Details** |
| --------- |:---:|:---:|--- |
| Lecture Check-Ins | 6% | 6% |  Drop 4 lowest scores. Skip Lecture 01 and 02. |
| Projects | 36% | 36% | (8% each typically) No drops; Project 0 worth half of others; See [Late Policy](#late-policy) |
| Homework Assignments | 18% | 18% | (3.6% each) ~~No~~ **1** drop; See [Late Policy](#late-policy) |
| Midterm | 15% | 10% |     |
| Final Exam | 25% | 20% | Final is cumulative. |
| Final Project | -- | 10% | Optional. See midway drop penalty below |

If you choose to do the project, your final grade will be the maximum of the two grading schemes. If you submit the team confirmation form at the checkpoint, but opt out of working on the project at any point after that, you will be assessed a penalty of 1% on your final grade.

For Info 258 students, the grading scheme will be the one involving the final project.

<!--Letter grades will be based on a combination of absolute cutoffs and the distribution of overall scores. Towards the end of the term, we will make three guarantees: "An overall score of at least x will result in a grade of at least C-; at least y will result in at least B-; at least z will result in at least A-." The thresholds x, y, and z will depend on this term’s performance.
-->


## Late Policy
Everyone has **9** slip days, which can be applied to late submissions of _projects_ and _homework assignments_, including the final project.

* Each project or homework assignment can have a max of 3 slip days applied to it. These slip days will be automatically applied at the end of the semester to maximize your grade, based on the final grade shown in gradescope.
* Slip days are rounded up to the next day. That is, 5 minutes late = 1 day late. We will use the submission time as displayed on Gradescope. You should track your own slip days.
* If you have no remaining slip days, there is a 15% reduction to your total score for every day that the assignment is late. After 3 slip days (i.e., late days), you can no longer receive credit for the submission.
* Lecture check-ins are not eligible for slip days.
* _Please do not ask the staff to apply slip days to particular assignments, or track how many you have used._ If an assignment is open for submission it is _always_ in your interest to turn in your best effort.

### Additional Extensions
We recognize that life can be unexpected. If you encounter the need for additional extensions at any time in the semester, please don't hesitate to let us know. The sooner we are made aware, the more options we have available to us to help you.

The [Additional Extensions form]({{site.course.additional_extensions}}){:target="\_blank"} is for addressing any circumstances that cannot be resolved via the slip day policy above. This form is designed to lower the barrier to reaching out to us, as well as build your independence in managing your academic career long-term. Within one business day of filling out the form, a course staff will reach out to you and, as needed, provide a space for conversation and arrange course accommodations as necessary. When making extension requests:
* Send requests before the assignment deadline
* Send one extension request per assignment
* If your extension request is granted, then the extension is to the original on-time deadline, from which slip days can be used. We will prioritize using your slip days over providing additional extensions.

You are responsible for reasonable, timely communication with course staff.
Simply submitting a request does not guarantee you will receive an extension. Even if your work is incomplete, please submit before the deadline so you can receive credit for the work you did complete.

## DSP Accommodations
If you have DSP accommodations for extended time on assignments, please make sure we have received your DSP accommodation letter. We will contact you about arrangements.

## Collaboration and Integrity
You are encouraged to discuss practice problems and lecture content with your fellow students and with course staff. Arguing with friends about exercises is an excellent and time-honored way to learn. However, **you must write up all your own assignments and code by yourself**. Copying assignments from other sources is not only dishonest, it also doesn’t help anyone, least of all yourself. We have important rules:

1. All code you submit should be written by you alone.

1. Do not possess or share code. Before submitting your final work, you should never be in possession of solution code that you did not write. Looking up solution code online is effectively possessing solution code. You will be equally culpable if you distribute code, now or in the future. If you find yourself struggling or really desperate, reach out to the staff and/or submit to Additional Extensions.

1. Cite your sources:
* **Study groups**: If you do discuss the assignments with others please include their names at the top of your notebook. Restated, you and your friends are encouraged to discuss course content and high-level approaches to problem-solving, but you are not allowed to share your code nor answers. You can work on a project alongside another person or group of people (e.g., study group), but it should not substantially resemble anyone else's.
* **StackOverflow, etc.** You should cite these sources, even if it's using small snippets of code (e.g., googling "postgres string matching" may lead you to some sample code that you copy and paste. Include the link to these online sources.
* **With extreme caution**: If you're just generating some amount of boilerplate code with GitHub Copilot / LLMs / etc., that's OK. However, you should not use such tools to generate non-trivial methods. AI methods often suffer from hallucinations, incompleteness, mistakes, and other idiosyncracies, and so there is a real danger to trusting them. There is always a need for human verification and validation, so in this class we emphasize your ability to do data engineering work without access to AI. **Any AI-generated code must be cited (with the prompt and log) and explicitly indicated as such.** Violation of this citation rule is a serious act of plagiarism. 

**_Each assignment will ask you to list any collobrators, outside sources, or other help received. You are expected to fill this hout honestly._**

We will follow the [EECS departmental policy](https://eecs.berkeley.edu/resources/students/academic-dishonesty){: target="\_blank"} on academic honesty, so be sure you are familiar with it.
We will be running advanced plagiarism detection programs on all assignments.
Posting solutions is also prohibited. If you find a solution online, please email a link to that solution tot he instructor.

We are tough with dishonest students and we hope that we will not be put in that situation in this class. We expect that you will work with integrity and with respect for other members of the class, just as the course staff will work with integrity and with respect for you. If you need help, just reach out and ask us. You are not alone.

## Academic and Wellness Resources

Our [Resources](../resources) page lists not only course-specific academic resources such as course notes, past exams, study guides, and prerequisite review links, but also campus wellness resources on COVID-19, academic support, technology support, mental well-being, DSP accommodations, dispute resolution, social services, campus community, and basic needs. Our staff will also refer to this page when supporting you through this course.


## We want you to succeed!

If you are feeling overwhelmed, visit our office hours and talk with us, or fill out the Additional Extensions Form. We know college can be stressful and we want to help you succeed.

Finally, the main goal of this course is that you should learn, and have a fantastic experience doing so. Please keep that goal in mind throughout the semester. Welcome to Data 101!

