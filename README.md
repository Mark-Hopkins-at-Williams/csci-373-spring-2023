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
| Fri Feb 3    | course info session            |                                    |
| Mon Feb 6    | search spaces                  | 3.1, 3.2, 3.3.1 - 3.3.3            |
| Wed Feb 8    | breadth-first search           | 3.4.1                              |
| Fri Feb 10   | UCS and DFS                    | 3.4.2, 3.4.3                       |
| Mon Feb 13   | analysis of search and IDS     | 3.3.4, 3.4.4                       |
| Wed Feb 15   | heuristic search               | 3.5.1, 3.5.2                       |
| Mon Feb 20   | heuristics                     | 3.6                                |
| Wed Feb 22   | minimax                        | 5.1, 5.2, 5.3                      |
| Fri Feb 24   | expectimax                     | 5.5                                |
| Mon Feb 27   | alpha-beta pruning             |                                    |
| Wed Mar 1    | TBD                            |                                    |
| Fri Mar 3    | exam 1                         |                                    |
| Mon Mar 6    | exam 1 review                  |                                    |
| Wed Mar 8    | probability                    | 12.1 - 12.5                        |
| Fri Mar 10   | bayesian networks              | 13.1, 13.2.1, 13.2.2, 13.2.4       |
| Mon Mar 13   | variable elimination           | 13.3.1, 13.3.2                     |
| Wed Mar 15   | complexity of inference        | 13.3.3                             |
| Fri Mar 17   | belief propagation             |                                    |
| Mon Apr 3    | gaussians                      | 13.2.3, A.3                        |
| Wed Apr 5    | kalman filters                 | 14.4                               |
| Fri Apr 7    | markov decision processes      | 17.1, 17.1.1                       |
| Mon Apr 10   | value iteration                | 17.2.1                             |
| Wed Apr 12   | passive reinforcement learning | 22.1                               |
| Fri Apr 14   | active reinforcement learning  | 22.2                               |
| Mon Apr 17   | ethics                         |                                    |
| Wed Apr 19   | exam 2                         |                                    |   
| Fri Apr 21   | exam 2 review                  |                                    |
| Mon Apr 24   | truth table inference          | 7.1, 7.2                           |
| Wed Apr 26   | propositional logic            | 7.3                                |
| Fri Apr 28   | entailment and satisfiability  | 7.4                                |
| Mon May 1    | search-based sat solvers       | 7.5.0, 7.5.1                       |
| Wed May 3    | resolution                     | 7.5.2                              |
| Fri May 5    | dpll                           | 7.6.1, 7.6.3                       |
| Mon May 8    | binary decision diagrams       |                                    |
| Wed May 10   | first-order logic              |                                    |
| Fri May 12   | exam 3                         |                                    |


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