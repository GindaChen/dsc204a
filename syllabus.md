---
layout: page
nav_order: 2
title: Syllabus
description: >-
    Syllabus
---

# Syllabus

{:.no_toc}

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---


The course is organized into four parts, covering the following topics.

1. **Foundations of Data Systems**: Data models, big data storage and retrieval, and how to encode information when you store data. 
2. **Scaling Distributed Systems**: Cluster, cloud, edge, network, replication, partition, consistency, ACID.
3. **Data Processing and Programming model**: Batch processing, stream processing, MapReduce, Hadoop, Spark, Ray.
4. **Machine Learning Systems**: GPUs, TensorFlow, PyTorch, data and model parallelism, LLM training and serving.


A significant component of this course is hands-on Python programming to implement data exploration, data preparation, distributed deep learning training and inference, and model selection pipelines on large real-world data using popular libraries (e.g., Ray, PyTorch).

## Logistics
- **Lectures**: MWF 11:00 AM - 11:50 AM.
- **Location**: [CENTR 214](https://maps.app.goo.gl/znFRbd8TLGnTMdjk9).
- **Instructor**: [Umesh Bellur](https://ubellur.github.io/); Office: HDSI 242.

## Course Content and Format
### Lectures
The class meets 3 times a week for 50-minute lectures in person.
  - Attending the lectures is highly encouraged. 
  - There will be scribe notes required for each lecture. Students should form groups of 2 - 3 people and sign up one slot. See [details below](#scribe-notes).
  - There will be reading summary required per week. Everyone needs to submit their reading summary individually. See [details below](#reading-summary).
  - We will use [Piazza](https://piazza.com/ucsd/spring2025/dsc204a) for asynchronous discussions and questions.

### 3 Programming Assignments (PAs)
  - See the [assignments page](assignments.md) for updates on the PA schedule and details.
  - There are **no late days** for the PAs. Plan your work accordingly.

### Exams: 
  - We will have at least one midterm exam.  
  - There will be a final exam. Date(s) to be announced for all exams.
  - We will have in class quizzes.
  - If you miss an exam or quiz, you will get no credit for it, unless you notify the instructor in advance with a university approved reason and receive a makeup exam slot.
  - Exams will be open notes. The only requirement is you should neither give nor receive help from anyone by any means.

### Scribe notes
Each student is required to scribe for a small number of lectures (most likely just 1). Most lectures will have at least 3 students acting as scribes, and they should work as a team. 
During your assigned lectures, you are to take detailed notes in collaboration with your fellow scribes. 
After the lecture, the scribe team is to convert their notes into LaTeX format using the provided template. 
These notes should be 4-8 pages long, and must be submitted electronically. 
We only require one set of notes from the scribe team. 
**You must submit scribe notes within 4 days of the class you are scribing for. So, for a Monday class submit on Friday midnight, Wednesday class - submit by Sunday midnight and Friday class - submit by Tuesday midnight of the next week. Late submissions will receive 0 credit.** 
The instructors will then audit your notes, and post them to the [class home page](https://ubellur.github.io/dsc204a/index.html) for everyone's benefit. 
As long as your scribe notes are of sufficient standard, you will be awarded full credit for scribe duties. 
You will receive zero credit if you fail to submit your notes.
  - Sign-up: [Spreadsheet](https://docs.google.com/spreadsheets/d/1AxC-7gUCdLYlJ2HclwyRl6YkEP7uyDpUw48_mYQcO00/edit?usp=sharing)
  - Template: [Overleaf latex template](https://www.overleaf.com/read/xfkmrdrzxqyy#ed68ba)
  - Submit on [Gradescope](https://www.gradescope.com/courses/993741) 

### Reading Summary
Starting from the second week, the instructor/TA team will provide one required reading and multiple optional readings prior to each lecture. The required readings for this class are compulsory. The optional readings are highly recommended.
At the end of each week, you are to submit a 2-page summary of the readings you have done for all the required readings of all lectures of the week. 
These reading summaries are a requirement for this class, and they must be submitted via Gradescope by you in order to receive credit. 
Your summary should be written at a high level, and should focus on the main point of the readings (i.e. avoid complicated math). As long as your summary is reasonable, you will be given full credit.
There will be no readings for the first and last week  of the instruction. Hence, in total, you need to submit 8 reading summaries (week 2 - week 9) unless otherwise indicated by the instructor. 

You are encouraged to use ChatGPT to improve the writing of your summary; but you should avoid using software like ChatPDF to generate a summary without actually finishing any readings by yourself. 
The TA team will perform quick scans on all summaries and contact you if they notice the summary seems to be entirely generated by ChatGPT (the writing style is easily detectable). 
  - Template: [NeurIPS format](https://neurips.cc/Conferences/2023/PaperInformation/StyleFiles)
  - Length: 2 pages
  - Submission: [Gradescope](https://www.gradescope.com/courses/993741)
  - **Due: starting from the 2nd week, the summary of the week is due on Sunday 11:59pm of the week**

## Pre-requisites

- DSC 202 (Data Mgt for Data Science); or substantial practical experience with scalable data systems and ML algorithms, subject to the consent of the instructor.
- Proficiency in Python programming.
- Knowledge of deep learning and deep learning frameworks such as PyTorch.


## Grading

### Components 
- Programming Assignments:  (35%) 9% + 12% + 14%
- Exams: 45%
- Quizzes: 5%
- Scribe Duties: 5%
- Reading Summary: 10%
- Extra Credit - to be decided. 


### Cutoffs 
The grading scheme is a hybrid of absolute and relative grading. The absolute cutoffs are based on your absolute total score. The relative bins are based on your position in the total score distribution of the class. The better grade among the two (absolute-based and relative-based) will be your final grade.



<table style="border: 1px solid black;">
  <tr>
    <td width="200px">Grade</td>
    <td width="200px">Absolute Cutoff (>=)</td>
    <td>Relative Bin (Use strictest)</td>
  </tr>
  <tr>
    <td>A+</td>
    <td width="200px">95</td>
    <td>Highest 5%</td>
  </tr>
  <tr>
    <td>A</td>
    <td width="200px">90</td>
    <td>Next 10% (5-15)</td>
  </tr>
    <tr>
    <td>A-</td>
    <td width="200px">85</td>
    <td>Next 15% (15-30)</td>
  </tr>
  <tr>
    <td>B+</td>
    <td width="200px">80</td>
    <td>Next 15% (30-45)</td>
  </tr>
    <tr>
    <td>B</td>
    <td width="200px">75</td>
    <td>Next 15% (45-60)</td>
  </tr>
    <tr>
    <td>B-</td>
    <td width="200px">70</td>
    <td>Next 15% (60-75)</td>
  </tr>
    <tr>
    <td>C+</td>
    <td width="200px">65</td>
    <td>Next 5% (75-80)</td>
  </tr>
    <tr>
    <td>C</td>
    <td width="200px">60</td>
    <td>Next 5% (80-85)</td>
  </tr>
  <tr>
    <td>C-</td>
    <td width="200px">55</td>
    <td>Next 5% (85-90)</td>
  </tr>
  <tr>
    <td>D</td>
    <td width="200px">50</td>
    <td>Next 5% (90-95)</td>
  </tr>
  <tr>
    <td>F</td>
    <td width="200px">< 50</td>
    <td>Lowest 5%</td>
  </tr>
</table>
		
**Example**: Suppose the total score is 82 and the percentile is 33. So, the relative grade is B-, while the absolute grade is B+. The final grade then is B+.

**Non-Letter Grade Options**: You have the option of taking this course for a non-letter grade. The policy for P in a P/F option is a letter grade of C- or better; for S in an S/U option is a letter grade of B- or better.


## Classroom Rules
- <code>No late days</code> for submitting the PAs. No extensions on the final exam time window. Plan all your work well up front accordingly.
- Students are encouraged to ask questions and participate in discussions in class and on Piazza. Please raise your hand before speaking and the instructor will call on you to speak.
- Please review UCSD's honor code and policies and procedures on [academic integrity](https://academicintegrity.ucsd.edu/) here. If plagiarism is detected in your code, or if we detect collusion on the graded quizzes or exams, or if you are found to be using someone else's clickers, or if any other form of academic integrity violation is identified, you will get zero for that component of your score and get downgraded substantially. I will also notify the University authorities for appropriate disciplinary action to be taken, up to and including expulsion from the University.
- Please review UCSD's principles of community and our commitment to creating an inclusive learning environment on [this website](https://ucsd.edu/about/principles.html).
- Harassment, discrimination, or intimidation of any form against any student will not be tolerated in class or on Piazza. Please review UCSD's policies on dealing with harassment and discrimination on [this website](https://ophd.ucsd.edu/).




<script src="../assets/darkmode.js"></script>
<script>
  window.addEventListener("DOMContentLoaded", (event) => {
    onLoad();
});
</script>
