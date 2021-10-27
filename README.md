# Systems and Networking - Unit I (2021-2022)

[News](#News) | [General Information](#General-Information) | [Syllabus](#Syllabus) | [Class Schedules](#Class-Schedules) |

## News
- All the students that are willing to attend this class (either in-person or remotely) **must subscribe ASAP** to the Moodle web page of the course, as indicated [below](#Moodle-Web-Page).
- Classes will start on **Wednesday, September 29 at 11:00AM**. Students are kindly asked to refer to the class schedule at the following [link](https://acsai.di.uniroma1.it/#schedule). For any further information on how to attend classes, please keep an eye on the dedicated [web page](https://www.uniroma1.it/en/notizia/covid-19-phase-3-person-and-online-classes-exams-and-graduation-sessions).

## General Information

Welcome to the System and Networking - Unit I class!

This is a second-year, first-semester course of the [BSc in Applied Computer Science and Artificial Intelligence of Sapienza University of Rome](https://acsai.di.uniroma1.it/).

This repository contains class material along with any useful information for the 2021-2022 academic year.

### Class Schedule
- **Wednesday** from **11:00AM** to **1:00PM**
- **Thursday** from **8:00AM** to **11:00AM**

### How to Attend Classes
According to the guidelines provided by Sapienza University to contrast the COVID-19 pandemic, the course will be held **both** in-person and remotely. For any further information, students must refer to the official documentation available on the [Sapienza website](https://www.uniroma1.it/en/notizia/covid-19-phase-3-person-and-online-classes-exams-and-graduation-sessions).

#### Attending Classes in Person: Room 2L - Via del Castro Laurenziano 7a ([map](https://goo.gl/maps/1x9rrSjsiieq41At6))
Students who are willing to attend classes in presence must issue their request through the [Prodigit Sapienza](https://prodigit.uniroma1.it/) online booking system, according to the rules established (please, see [here](https://www.uniroma1.it/en/notizia/covid-19-phase-3-person-and-online-classes-exams-and-graduation-sessions)).

#### Attending Classes Remotely: Zoom
Students who are willing to attend classes remotely online will **need to register** to the dedicated Zoom conference, using the following link: https://uniroma1.zoom.us/meeting/register/tZMkcuqurDMtE90QEvSpAXG4QJuMjvxIGZrs

### Moodle Web Page
Students must subscribe to the Moodle web page using the same credentials (username/password) to access Wi-Fi network and Infostud services, at the following link: https://elearning.uniroma1.it/course/view.php?id=13817

### Office Hours
- Please, drop me a message to <a href="mailto:tolomei@di.uniroma1.it">tolomei@di.uniroma1.it</a> if you like to arrange an in-person meeting or schedule a remote call either on Google Meet or Zoom.<br/>
In-person meetings will be held in my office, which is located in Room 106 at the 1st floor of Building E in viale Regina Elena 295 ([map](https://goo.gl/maps/5dSuQbvaeqXePV9y6)).

### Contacts
- Email: tolomei@di.uniroma1.it
- Website: https://www.di.uniroma1.it/~tolomei
- Bacheca Sapienza: https://corsidilaurea.uniroma1.it/it/users/gabrieletolomeiuniroma1it

### Description and Goals
The _Operating System_ (OS) is the key component of any modern computing device. Moreover, it very well represents a fundamental concept at the heart of any Computer Science curriculum, namely _abstraction_.

More specifically, by virtualizing the physical resources of a computer system, OS allows programmers to develop software applications without worrying about the nitty-gritty of the hardware. Decoupling the software from the hardware guarantees more flexibility for the system developer as well as greater usability for the end user.
It is therefore essential for any Computer Science student to have the ability to comprehend how to effectively and efficiently design and exploit the main functionalities of a highly complex software system, such as a modern operating system.

To this end, we will deeply discuss the key responsibilities of so-called general purpose OSs (i.e., those typically installed on our PCs and laptops). Amongst those responsibilities are: CPU scheduling, process/thread synchronization, memory management, file systems, just to name a few. In addition, we will explore how OSs should adapt to resource-limited mobile devices (i.e., tablets and smartphones).

All the concepts introduced are totally covered by the lecture materials provided during the course, and will be treated independently from a specific operating system implementation. However, many examples will be taken from popular OSs available on the market like UNIX/Linux, Windows, macOS, Android, iOS, etc.

### Prerequisites
- Fundamentals of computer architectures
- Basics of computer programming


### Exams
Written and oral exam.
Written exam consists of a Moodle quiz containing **20 multiple-answer questions**. Each correct answer accounts for 3 points, each wrong answer subtracts 1 point, whilst no answer gives no points. The quiz is successfully passed if the overall score is **greater than or equal to 15/30**. Those who obtain a score ranging between 15/30 and 17/30 must take a mandatory oral exam; instead, those who passed the quiz with a score of 18/30 or higher can decide to accept this as their final score or to take an additional oral exam.

### Recommended Textbooks
Despite they are not mandatory for successfully pass the exam, the following textbooks are really useful to anyone who wants to dig deeper into the subjects addressed in this course:
- _Operating System Concepts_ [Silberschatz _et al._];
- _Modern Operating Systems_ [Tanenbaum _et al._];
- _Operating Systems: Three Easy Pieces_ [Remzi] (<a href="http://pages.cs.wisc.edu/~remzi/OSTEP/" target="_blank">freely available online</a>).
 
<hr>

## Syllabus
**Part I: Introduction**
- Basic concepts
- History of operating systems
- Relationship between operating systems and hardware
- Operating systems structures

**Part II: Process Management**
- Processes
- CPU Scheduling
- Threads

**Part III: Process Synchronization**
- Synchronization Tools
- Synchronization Examples
- Deadlock

**Part IV: Memory Management**
- Main memory (RAM)
- Virtual memory

**Part V: Storage Management**
- Mass storage devices
- I/O systems

**Part VI: File System**
- File system interface
- File system implementation
- File system internals

**Part VII: Advanced Topics**
- Protection
- Security
- Distributed operating systems
- Mobile operating systems

<hr>

## Class Schedules

| Lecture \# | Date | Topic                                         | Material       | 
|------------|------|-----------------------------------------------|----------------|
| Lecture 1  | 09/29/2021 | Basics and History of Operating Systems | [slides: <a href="./lectures/slides/01_Basics_and_History.pdf" target="_blank">PDF</a>] |
| Lecture 2  | 09/30/2021 | Computer Architecture and OS Structures | [slides: <a href="./lectures/slides/02_Computer_Architecture_and_OS_Structures.pdf" target="_blank">PDF</a>]|
| Lecture 3 | 10/06/2021 | Process Virtual Address Space and PCB | [slides: <a href="./lectures/slides/03_Process_Virtual_Address_Space_and_PCB.pdf" target="_blank">PDF</a>]|
| Lecture 4  | 10/07/2021 | Basics of OS Process Management | [slides: <a href="./lectures/slides/04_Basics_of_OS_Process_Management.pdf" target="_blank">PDF</a>]|
| Lecture 5  | 10/13/2021 | CPU Scheduling (1 of 2) | [slides: <a href="./lectures/slides/05_CPU_Scheduling_1.pdf" target="_blank">PDF</a>]|
| Lecture 6  | 10/14/2021 | CPU Scheduling (2 of 2) | [slides: <a href="./lectures/slides/06_CPU_Scheduling_2.pdf" target="_blank">PDF</a>]|
| Lectures 7 & 8  | 10/20/2021-10/21/2021 | Threads | [slides: <a href="./lectures/slides/07-08_Threads.pdf" target="_blank">PDF</a>]|
| Lecture 9 | 10/27/2021 | Process/Thread Synchronization (Locks) | [slides: <a href="./lectures/slides/09_Synchronization_Locks.pdf" target="_blank">PDF</a>]|
<!--| Lezione 13 | 16/11/2020 | Sincronizzazione tra Processi/Thread (2) | [slides: <a href="./lectures/slides/07_Synchronization_2.pdf" target="_blank">PDF</a>] [<a href="./code/synchronization.tgz" download="synchronization.tgz">code</a>]|
| Lezione 14 | 18/11/2020 | Deadlock | [slides: <a href="./lectures/slides/08_Deadlock.pdf" target="_blank">PDF</a>] |
| Lezione 15 | 23/11/2020 | Gestione della Memoria (1) | [slides: <a href="./lectures/slides/09_Memory_Management.pdf" target="_blank">PDF</a>] |
| Lezione 16 | 25/11/2020 | Gestione della Memoria (2) | [slides: <a href="./lectures/slides/10_Memory_Management_Paging.pdf" target="_blank">PDF</a>] |
| Lezioni 17 - 18 | 30/11/2020 - 02/12/2020 | Memoria Virtuale | [slides: <a href="./lectures/slides/11_Virtual_Memory.pdf" target="_blank">PDF</a>] |
| Lezioni 19 - 20 | 07/12/2020 - 09/12/2020 | Dispositivi di Memoria di Massa | [slides: <a href="./lectures/slides/12_Mass_Storage.pdf" target="_blank">PDF</a>] |
| Lezione 21 | 14/12/2020 | File System: Interfaccia e Implementazione | [slides: <a href="./lectures/slides/13_File_System.pdf" target="_blank">PDF</a>] |
| Lezioni 22 - 23 - 24 | 16/12/2020 - 21/12/2020 - 23/12/2020 | Esercitazioni | |

# Anni Precedenti
In questa sezione è possibile accedere alle informazioni del corso relativamente agli anni accademici precedenti rispetto a quello corrente.

**NOTA:** _La directory che include il materiale didattico è **unica** e il suo contenuto può subire modifiche o aggiornamenti di anno in anno; pertanto, è possibile che vi siano discrepanze tra ciò che è presente su questo sito e ciò che invece è stato mostrato in un determinato anno, diverso da quello corrente._

-->
