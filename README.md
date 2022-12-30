# CSCI 373: Artificial Intelligence (Williams College)
## Spring 2023


### Basic Information

**Professor:** Mark Hopkins, mh24@williams.edu

**Class Schedule:** MWF 9-950am.

**Office Hours:** TBD.

**Textbook:** Artificial Intelligence: A Modern Approach (4th edition) by 
Stuart Russell and Peter Norvig. Make sure to get the newest (4th) edition!
The textbook has a Kindle version.

**Website:** [http://markandrewhopkins.com/csci-373-artificial-intelligence/](http://markandrewhopkins.com/csci-373-artificial-intelligence/)

**Course Information Sheet**:  [here](https://docs.google.com/document/d/1umo-FwRfV2CT3SBygofSQ59Obb-n7zAU5SH1Zr4T8PQ/edit?usp=sharing)


### Overview

This course establishes the algorithmic foundations required to become an informed, 
well-rounded practitioner of artificial intelligence. At a high level, it 
focuses on three types of reasoning: search-based, probabilistic, and logical. 
While you likely have some experience with all three of these subjects in previous
classes, the focus of this course will be on: (a) coming to terms with the
fact that almost everything we want to do is NP-hard or worse, and
then (b) sometimes successfully doing it anyway.


### Coursework

**Homework (40%):** There will be weekly homework assignments, typically assigned on Monday
and due the following Monday (though there will be exceptions). Be advised: some 
homeworks are rather substantial. Doing the homeworks is a crucial part of learning 
the material.

**Projects (30%, 10% each):** There will be three projects during the course. Each project is
weighted equally and addresses one module of the course. In other words, there will be one
project about search-based reasoning, one project about probabilistic reasoning, and one
project about logical reasoning. 

The projects will be done in groups of two. Each project will be due shortly after the
end of its corresponding module. In addition to submitting your project code online, each group 
will meet with me for 15 minutes, during which you will present your design and answer
questions about the design decisions that you made.

**Exams (30%, 10% each):** There will be three exams during the course. Each exam is weighted
equally and covers one module of the course. In other words, there will be one exam about 
search-based reasoning, one exam about probabilistic reasoning, and one exam about logical
reasoning.

The exams must be done individually, without consulting other students or external resources
on the Internet. However, you are welcome to consult your course notes and provided course
materials (including the textbook) while writing the exams. The exams will be designed to
be completed during a 50-minute class period, and you will be given a free class
period to complete each exam. However, the exams will be "take-home", and need only be submitted
sometime before midnight on the day they are assigned. You are free to use as much extra time 
as you need on the day of the exam.


### Learning Outcomes

After successful completion of the course, a student should:

1. Have facility with search-based reasoning, as demonstrated by the ability to:
  - express a novel reasoning task as a search space
  - know when and how to apply search strategies such as BFS, DFS, iterative deepening, and A*
  - know when and how to apply game search strategies such as minimax, alpha-beta, and expectimax
  - analyze the worst-case time and space requirements of a search strategy on a search space
  - develop good search heuristics, and be able to determine their admissibility
2. Have facility with probabilistic reasoning and reinforcement learning, as demonstrated by the ability to:
  - express a novel reasoning task as an appropriate probabilistic graphical model
  - read the structure of a Bayesian network (e.g. identify independence relationships, inferential complexity)
  - implement exact and approximate algorithms for probabilistic inference
  - implement a temporal model to solve a real-time task
  - implement a reinforcement learner for a simple task (i.e. a task whose associated state space has <1000 states)
3. Have facility with logical reasoning, as demonstrated by the ability to:
  - translate English statements into propositional logic
  - know when and how to apply logical inference procedures, including resolution and DPLL
  - analyze the worst-case time and space requirements of inference on a logical statement
  - express logical statements in equivalent forms (e.g. CNF)
  - identify relationships between logical statements (e.g. equivalence, entailment)


### Lecture Schedule (tentative, subject to change)

| Date         | Topic                          | Reading (AIMA 4th edition)         |
| ------------ | ---------------------------    | ---------------------------------- |
| Fri Sep 9    | course intro                   |                                    |
| Mon Sep 12   | search spaces                  | 3.1, 3.2, 3.3.1 - 3.3.3            |
| Wed Sep 14   | breadth-first search           | 3.4.1                              |
| Fri Sep 16   | UCS and DFS                    | 3.4.2, 3.4.3                       |
| Mon Sep 19   | analysis of search             | 3.3.4                              |
| Wed Sep 21   | iterative deepening            | 3.4.4                              |
| Fri Sep 23   | minimax                        | 5.1, 5.2, 5.3                      |
| Mon Sep 26   | expectimax                     | 5.5                                |
| Wed Sep 28   | heuristic search               | 3.5.1, 3.5.2                       |
| Fri Sep 30   | heuristics                     | 3.6                                |
| Mon Oct 3    | exam 1                         |                                    |
| Wed Oct 5    | exam 1 review                  |                                    |
| Fri Oct 7    | mountain day?                  |                                    |
| Mon Oct 10   | reading period                 |                                    |
| Wed Oct 12   | probability                    | 12.1 - 12.5                        |
| Fri Oct 14   | bayesian networks              | 13.1, 13.2.1, 13.2.2, 13.2.4       |
| Mon Oct 17   | variable elimination           | 13.3.1, 13.3.2                     |
| Wed Oct 19   | complexity of inference        | 13.3.3                             |
| Fri Oct 21   | approximate inference          | TBD                                |
| Mon Oct 24   | gaussians                      | 13.2.3, A.3                        |
| Wed Oct 26   | kalman filters                 | 14.4                               |
| Fri Oct 28   | markov decision processes      | 17.1, 17.1.1                       |
| Mon Oct 31   | bellman equations              | 17.1.2                             |
| Wed Nov 2    | value iteration                | 17.2.1                             |
| Fri Nov 4    | passive reinforcement learning | 22.1                               |                                    
| Mon Nov 7    | active reinforcement learning  | 22.2                               |
| Wed Nov 9    | ethics                         |                                    |
| Fri Nov 11   | ethics                         |                                    |
| Mon Nov 14   | exam 2                         |                                    |                                    
| Wed Nov 16   | exam 2 review                  |                                    |                                    
| Fri Nov 18   | truth table inference          | 7.1, 7.2                           |
| Mon Nov 21   | language and semantics         | 7.3                                |
| Wed Nov 23   | thanksgiving break             |                                    |
| Fri Nov 25   | thanksgiving break             |                                    |
| Mon Nov 28   | propositional logic            | 7.4                                |                                    
| Wed Nov 30   | propositional inference        | 7.5.0, 7.5.1                       |                                    
| Fri Dec 2    | resolution                     | 7.5.2                              |
| Mon Dec 5    | dpll                           | 7.6.1, 7.6.3                       |
| Wed Dec 5    | logic and probability          | TBD                                |                                    
| Fri Dec 9    | exam 3                         |                                    |


### Reading Assignments

Reading assignments will be posted on the website a minimum of two days 
in advance of each lecture. I will assume that the reading is done prior 
to lecture. 

### Collaboration Policy

Follow[^1] the spirit of the [50 ft rule](http://courses.cms.caltech.edu/cs171/materials/pdfs/50ft_policy.pdf),
except on exams, where you should neither collaborate nor use external resources.

[^1]: Thanks to Jim Bern for the pointer.


### Inclusivity

This course aspires to be a welcoming environment for all students. Please let me
know if any issues arise, and I will do my best to address them.


### Health/Accessibility Resources

Students with disabilities or disabling conditions who experience barriers in this
course are encouraged to contact me to discuss options for access and full course 
participation. The Office of Accessible Education is also available to facilitate 
the removal of barriers and to ensure access and reasonable accommodations. Students with 
documented disabilities or disabling conditions of any kind who may need accommodations 
for this course or who have questions about appropriate resources are encouraged to 
contact the Office of Accessible Education at oaestaff@williams.edu.