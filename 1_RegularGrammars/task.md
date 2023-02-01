# Topic: Intro to formal languages. Regular grammars. Finite Automata.

### Course: Formal Languages & Finite Automata
### Author: Vasile Drumea

----

## Overview
&ensp;&ensp;&ensp; A formal language can be considered to be the media or the format used to convey information from a sender entity to the one that receives it. The usual components of a language are:
- The alphabet: Set of valid characters;
- The vocabulary: Set of valid words;
- The grammar: Set of rules/constraints over the lang.

&ensp;&ensp;&ensp; Now these components can be established in an infinite amount of configurations, which actually means that whenever a language is being created, it's components should be selected in a way to make it as appropriate for it's use case as possible. Of course sometimes it is a matter of preference, that's why we ended up with lots of natural/programming/markup languages which might accomplish the same thing.



## Objectives:
1. Understand what a language is and what it needs to have in order to be considered a formal one.

2. Provide the initial setup for the evolving project that you will work on during this semester. I said project because usually at lab works, I encourage/impose students to treat all the labs like stages of development of a whole project. Basically you need to do the following:

    a. Create a local && remote repository of a VCS hosting service (let us all use Github to avoid unnecessary headaches);

    b. Choose a programming language, and my suggestion would be to choose one that supports all the main paradigms;

    c. Create a separate folder where you will be keeping the report. This semester I wish I won't see reports alongside source code files, fingers crossed;

3. According to your variant number (by universal convention it is register ID), get the grammar definition and do the following tasks:

    a. Implement a type/class for your grammar;

    b. Add one function that would generate 5 valid strings from the language expressed by your given grammar;

    c. Implement some functionality that would convert and object of type Grammar to one of type Finite Automaton;
    
    d. For the Finite Automaton, please add a method that checks if an input string can be obtained via the state transition from it;


   
## Implementation tips:

1. You can use 2 classes in order to represent the 2 main object which are the grammar and finite automaton. Additional data model, helper classes etc. can be added but should be used (i.e. you shouldn't have source code file that are not used).

```
public class Grammar
{
    // Some state variables as needed.
    // {V_n, V_t, P, S}

    public Grammar(some params...)
    {
        ...
    }

    // This method could be called 5 times to get 5 words.
    // You have multiple options on how to implement this method.
    public String generateString()
    {
        // The implementation...
    }

    public FiniteAutomaton toFiniteAutomaton()
    {
        // Convert this to an object of type Finite Automaton.
    }
}

public class FiniteAutomaton
{
    // Some state variables as needed.
    // {Q, Sigma, delta, q0, F}

    public FiniteAutomaton(constructor params...)
    {
        ...
    }

    public boolean stringBelongToLanguage(final String inputString)
    {
        ...
    }
}
```

2. In order to show the execution you can implement a client class/type, which is just a "Main" class/type in which you can instantiate the types/classes. Another approach would be to write unit tests if you are familiar with them.


## Evaluation:
1. The project should be located in a __*public*__ repository on a git hosting service (e.g. Github, Gitlab, BitBucket etc.):

  * You only need to have one repository.
  * For now there is no need to use libs/frameworks so please don't use libs that have this kind of stuff already implemented.

2. It should contain an explanation in the form of a Markdown with the standard structure from the ../REPORT_TEMPLATE.md file.

3. In order to make the evaluation as optimal as possible you should obey the indications and document the project accordingly so that I could evaluate them by myself. The works can be presented by you as well if you want either at the lectures or online.

4. You need to submit on ELSE the URL to the repository. (__NOTE__: Be aware that sometimes on ELSE you need to submit the assignment after it is in draft state. So if it is in draft it will not be evaluated).

5. If the work doesn't correspond to the requirements I'll revert the submission and leave some comments. If needed you can reach out and ask questions. 

7. The deadline for this assignment is __17/09/2022::23:59:59:99__.

8. After the deadline, the students will have to present the laboratory works, and for each week, the max grade would be decreased by 1.
