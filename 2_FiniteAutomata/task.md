# Topic: Determinism in Finite Automata. Conversion from NDFA 2 DFA. Chomsky Hierarchy.

### Course: Formal Languages & Finite Automata
### Author: Vasile Drumea

----

## Overview
&ensp;&ensp;&ensp; A finite automaton is a mechanism used to represent processes of different kinds. It can be compared to a state machine as they both have similar structures and purpose as well. The word finite signifies the fact that an automaton comes with a starting and a set of final states. In other words, for process modeled by an automaton has a beginning and an ending.

&ensp;&ensp;&ensp; Based on the structure of an automaton, there are cases in which with one transition multiple states can be reached which causes non determinism to appear. In general, when talking about systems theory the word determinism characterizes how predictable a system is. If there are random variables involved, the system becomes stochastic or non deterministic.

&ensp;&ensp;&ensp; That being said, the automata can be classified as non-/deterministic, and there is in fact a possibility to reach determinism by following algorithms which modify the structure of the automaton.


## Objectives:
1. Understand what an automaton is and what it can be used for.

2. Continuing the work in the same repository and the same project, the following need to be added:
    a. Provide a function in your grammar type/class that could classify the grammar based on Chomsky hierarchy.

    b. For this you can use the variant from the previous lab.

3. According to your variant number (by universal convention it is register ID), get the finite automaton definition and do the following tasks:

    a. Implement conversion of a finite automaton to a regular grammar.

    b. Determine whether your FA is deterministic or non-deterministic.

    c. Implement some functionality that would convert an NDFA to a DFA.
    
    d. Represent the finite automaton graphically (Optional, and can be considered as a __*bonus point*__):
      
    - You can use external libraries, tools or APIs to generate the figures/diagrams.
        
    - Your program needs to gather and send the data about the automaton and the lib/tool/API return the visual representation.


## Implementation tips:

1. Not much, just to mention that it would be enough for you to implement the project just to work with your specific variant. Of course, it would be gr8 if you could make it as generic as possible. :)

2. In order to show the execution you can implement a client class/type, which is just a "Main" class/type in which you can instantiate the types/classes. Another approach would be to write unit tests if you are familiar with them.


## Evaluation:
1. The project should be located in a __*public*__ repository on a git hosting service (e.g. Github, Gitlab, BitBucket etc.):

  * You only need to have one repository.
  * For now there is no need to use libs/frameworks so please don't use libs that have this kind of stuff already implemented.

2. It should contain an explanation in the form of a Markdown with the standard structure from the ../REPORT_TEMPLATE.md file.

3. In order to make the evaluation as optimal as possible you should obey the indications and document the project accordingly so that I could evaluate them by myself. The works can be presented by you as well if you want either at the lectures or online.

4. You need to submit on ELSE the URL to the repository. (__NOTE__: Be aware that sometimes on ELSE you need to submit the assignment after it is in draft state. So if it is in draft it will not be evaluated).

5. If the work doesn't correspond to the requirements I'll revert the submission and leave some comments. If needed you can reach out and ask questions. 

7. The deadline for this assignment is __07/03/2022::23:59:59:99__.

8. After the deadline, the students will have to present the laboratory works, and for each week, the max grade would be decreased by 1.
