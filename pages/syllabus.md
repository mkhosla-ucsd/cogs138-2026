---
layout: default
title: Syllabus
nav_order: 3
has_toc: true
permalink: /syllabus/
---

# Syllabus

* * *
- TOC
{:toc}

## Course Description

This course introduces students to **neural data science**: how to reason about, analyze, and model modern neuroscience datasets using computational tools from statistics, data science, and machine learning.

The quarter will move from Python and core data-analysis tools toward broader questions about neural data types, statistical inference, encoding/decoding, dimensionality reduction, and machine learning.

## Course Materials

There is no required textbook, but useful references include:

- *Python Data Science Handbook*
- Wallisch et al., *Neural Data Science*
- Adhikari & DeNero, *Computational and Inferential Thinking: The Foundations of Data Science*

## Learning Goals

By the end of the course, students should be able to:

- think from a **data-first** perspective about neuroscience questions,
- Work with many different neuroscience data types that might include data on behavior, brain structure and connectivity, single-unit spiking, field potential, gene expression, and even text-mining of the peer-reviewed neuroscientific literature,
- choose reasonable computational/statistical approaches for a question,
- consider alternative hypotheses and assess for spurious correlations and results
- interpret results critically,
- and design a data-driven final project.

## Grading 

### Course Components & Points

|  | % of Total Grade | 200 Total Points |
| :--- | :--- | :--- |
| 4 Assignments | 40 | 80 (20 each) |
| 4 Reading Quizzes | 20 | 40 (10 each) |
| Final Project Proposal | 5 | 10 |
| Final Project Notebook | 20 | 40 |
| Final Project Presentation | 5 | 10 |
| 1 Final Exam | 10 | 20 |
| Extra Credit (Guest lecture attendance + Course Surveys + SET) | N/A | 5 (bonus) |

### Final Grades

Your letter grade will be determined using the following grading scale:

| Percentage              | Letter Grade              |
| ----------------------- | ------------------------- |
| 97-100%                 | A+                        |
| 93-96.99%                  | A                         |
| 90-92.99%                  | A-                        |
| 87-89.99%                  | B+                        |
| 83-86.99%                  | B                         |
| 80-82.99%                  | B-                        |
| 77-79.99%                  | C+                        |
| 73-76.99%                  | C                         |
| 70-72.99%                  | C-                        |
| 67-69.99%                  | D+                        |
| 63-66.99%                  | D                         |
| 60-62.99%                  | D-                        |
| <60%                    | F                         |

### Grades
Grades for assignments will be released on Canvas approximately a week after the submission date. Ultimately it is your responsibility to check your final grade and get in touch if you believe there is a problem.

### Regrade Policy
We will work hard to grade everyone fairly and return assignments quickly. But we know you also work hard and want you to receive the grade you’ve earned. Occasionally, grading mistakes do happen, and it's important to us to correct them.

If you think there is a mistake in your grade for an assignment, submit a regrade request to Prof. Khosla and the TA within 72 hours of receipt of the grade. This request should include evidence of why you think your answer was correct (_i.e._, a specific reference to something said in lecture) and should point to the specific part of the assignment for us to reconsider.

**If you think a grading error has occurred please follow these steps:**
- You have 72 hours to request a regrade
- If it is a group project, confer w/ your team first and submit one regrade after your team comes to a consensus)
- Provide evidence for why your answer is correct and merits a regrade (i.e. a specific reference to something said in a lecture, the readings, or office hours)
- We will get back to you within 48 hours after regrades close with our final decision.



## Attendance

Regular attendance is strongly encouraged. The course is cumulative, and many lectures build directly on previous material. Participation in class discussions and project workdays will help students stay on track.

## Sections 
Discussion sections will be used to review content from lectures, discuss readings, help with coding and the Final Project, and guide your assignments, so it is to your benefit to go, participate, and ask questions. Further, groups will be created within sections (usually week 2), so it is especially helpful to attend discussion section that week. 

## Course Assignments & Topics
Neuroscience is a rapidly changing field that is increasingly moving towards ever larger and more diverse datasets that are analyzed using increasingly sophisticated computational statistical methods. There is a strong need for neuroscientists who can think deeply about problems that incorporate information from a wide array of domains including psychology and behavior, cognitive science, genomics, pharmacology and chemistry, biophysics, statistics, and AI/ML. With its focus on combining many large, multidimensional, heterogeneous datasets to answer questions and solve problems, data science provides a framework for achieving this goal.

Determining what data one needs, and how to effectively combine datasets, is a creative process. For example, a neural data scientist might be tasked with combining:

1) _demographic information_ and 2) _multiple cognitive and behavioral measures_, from people from whom we might collect;

3) _biometric data_, 4) _motion capture data_ to understand motor control, and 5) _eye-tracking_ to study attention, along with;

6) _structural connectomic_ and 7) _functional brain imaging_ data collected using methods with different spatial and temporal resolution (such as fMRI and EEG), and then place those results into context relative to;

8) _average human brain gene expression patterns_ and 9) _the existing knowledge embedded within the peer-reviewed neuroscience literature_ (>3,000,000 papers).

These types of data are very different: continuous and ordinal, time-series, video and images, directed graphs, spatial, high-dimensional categorical / nominal, and unstructured natural language. What is the appropriate way to aggregate and synthesize these data? What are the benefits and caveats for, say, aggregating spatially versus temporally? Being able to conceptualize how to carry out this integration is necessary before leveraging any technical skills will even be useful.

### Readings & Quizzes
Quizzes cover the reading material assigned, e.g. Quiz 1 only covers material from reading 1 (R1).

- Four multiple choice (10 questions) quizzes
- No time limit
- Open notes, but you must work alone.
- Taken and submitted through Gradescope

Late reading quizzes will be accepted up to 48 hours; however, they will receive ½ credit.

## Assignments

Assignments are all individual. They are intended to reinforce lecture material and support progress toward the final project. Assignments will be released and submitted on datahub.

## Final Project

Students will work in groups of 2-3 members on a final project that applies computational tools to a neuroscience question or dataset. See the [Final Project]({{ site.baseurl }}/final-group-project/) page for more details.

**Proposal**
Around mid-quarter, you are required to submit a project proposal. The template will be provided to you. 
- One report submitted through Gradescope per group. 
- One PDF submission per group (ensure all your names and PIDs are on the PDF)
- Your team may resubmit as many times as you like before the deadline
- Late submissions:
  - Late reports have 5 points deducted within the first 24 hours, and an additional 5 points during the following 24 hours.
  - No late reports accepted after 48 hours.
  - 
You should integrate the feedback given on your proposal into your product, and reach out to Dr. Khosla or our TA if you have any questions or concerns.

**Final submission**
Your final product for this project will be a Jupyter Notebook that walks us through the steps of your analysis to answer your experimental question. Ultimately, you should generate three different plots that concisely address your experimental question.

{: .note .fs-2 }
To reiterate, your team will create a jupyter notebook for all project-related work and work on that copy together. Make sure to read all the instructions. You will receive feedback along with a grade typically within a week for the proposal. Feedback from us should be incorporated into the final submission.



### Exam
The final exam is comprehensive and will cover the lectures (and possibly guest lectures). An exam review session will be held during discussion section week 10.

- One multiple-choice exam
- Available for 72 hours on Gradescope
- You have 1 hour to finish once started
- One attempt
- Taken and submitted through Gradescope

No late exams are permitted, except for extenuating circumstances. Please reach out to staff as early as possible if you know something will prevent you from taking the exam on time.

## Academic Integrity

Students are expected to follow UC San Diego academic integrity policies. Collaboration is encouraged when explicitly permitted, but submitted work must accurately reflect the rules for that assignment.

## Accessibility and Support

Students requesting accommodations should work with the Office for Students with Disabilities (OSD). If something outside class is affecting your ability to succeed, please reach out early.
