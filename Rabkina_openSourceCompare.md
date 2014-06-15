Irina Rabkina

June 16, 2014

FOSS Summer 2014

#Comparison of Open Source Projects

## PsychoPy 
#### [Official Site](www.psychopy.org "Psy Official Site")  /   [Github Repo](https://github.com/psychopy/psychopy "Psy Github Repo") 

#####Background
PsychoPy is an open source software used for designing experiments in psychology and neuroscience. It provides experimenters with control over the flow of experiments (i.e. what stimuli participants see and the order in which they see them). Psychopy is a free (and, frankly, more user-friendly) alternative to commercial software such as E-Prime, Presentation, and Matlab's PsychToolbox. Experimenters who are comfortable coding in Python can use PsychoPy as a library (called the "Coder"); others can use the Psychopy GUI (called the "Builder") to design experimental flow and a Python script will be compiled for them. Experiments can be run through the standalone console or at the interpreter.

#####Developer Interest
The lead developer on the project is Jonathan Peirce, an associate professor of psychology at the University of Nottingham. Although Dr. Peirce's main research area is vision neuroscience, he updates PsychoPy frequently. In fact, in the three months or so that have passed since I last programmed an experiment using PsychoPy, the software version has updated from 1.79.01 to 1.80.06. Dr. Peirce is also very active in both the [Psychopy Users](https://groups.google.com/d/forum/psychopy-users "Psy Users") and [Psychopy Developers](https://groups.google.com/d/forum/psychopy-dev "Psy Dev") Google groups. Other major contributors to the project are Dr. Jeremy Gray of Michigan State University and Dr. Yaroslav Halchenko of the New Jersey Institute of Technology. There is also a developer mailing list.

#####User Interest
According to Dr. Peirce's personal [website](peirce.org.uk "Peirce"), hundreds of labs use PsychoPy. The PsychoPy Users Google group is very active. There have been over 2000 topic threads created since PsychoPy was first distributed in 2010. Because PsychoPy is free, easy to use, and accomplishes a task that is necessary for all psychology and cognitive neuroscience researchers, its popularity is likely to continue to increase.

#####Documentation 
PsychoPy is well documented--after having taken only an introductory computer science class, I was able to figure out how to use the Builder and complement the output through the Coder, very quickly. There is separate documentation for the two modes, which is updated with each release. API documentation is created automatically from doc strings. There are also tutorials and FAQs available.

#####Code Readability
The code is well organized and readable. It follows most PEP conventions (although several diversions from this standard are noted on the "For Developers" page on the PsychoPy website). Developers are encouraged to add comments to non-trivial elements of their code, so the logic is relatively easy to follow.

#####Software Engineering Practices
The source code for PsychoPy is managed through git. Additions and changes are submitted to lead developers via pull request. All developers are asked to complete unit tests before submitting their work in order to ensure that all features work and integrate with existing code. Further testing and review is done by the lead development team before submissions are merged to the main repository. It is hard to tell whether the developers of PsychoPy use continuous integration, but they do have frequent updates and releases. 

#####Opportunities to Contribute
There is a "For Developers" section of the PsychoPy website that includes instructions for contributors. It also includes links to both the Google group and email list. Since the project is always evolving, there is a suggestion to post to the group or send an email before beginning any major changes or additions to the project in order to avoid duplicating code and/or creating unnecessary or bulky features. In addition to creating new features, editing documentation, testing existing or upcoming features, and writing tutorials are also encouraged. In fact, there is currently an effort to translate some of the GUI dialog boxes to other languages. 

## The Virtual Brain
#### [Official Site](www.thevirtualbrain.org "TVB Official Site")  /   [Github Repo](https://github.com/the-virtual-brain "TVB Github Repo") 

#####Background
The Virtual Brain is an attempt to create a model of the human brain that can be used in scientific studies. It is available as both a GUI and a Python library. Users can upload DTI and fMRI images for patients/participants, and the software allows them to model responses to stimuli, create artificial lesions, and perform other experiments that would be costly (and unethical) to perform on human subjects. Unfortunately, this project is a bit of a catch 22: it is difficult to model neuron-level connectivity in the brain without studying connectivity at that level in humans. The solution that the developers of The Virtual Brain have employed is allowing users to choose equations and parameters that they believe to be most descriptive for their models. The majority of these equations come from physics or animal (e.g. squid) physiology, and may not be accurate representations of the human brain.

#####Developer Interest
Because this project is very scientifically oriented, the leads on the project are neuroscientists from all over the world. The computation and software development are led by Viktor Jirsa of Aix-Marseille Université and Randy McIntosh of the University of Toronto. Other developers are also neuroscientists from various universities who collaborate with Dr. Jirsa and Dr. McIntosh on other projects. The Virtual Brain is somewhat of a niche project, so outside developer interest seems to be small.

#####User Interest
Due to the niche nature of this project, user interest is also limited. There is a [Google group](https://groups.google.com/forum/#!forum/tvb-users "TVB") available for users, but most posts are made by the same set of researchers. From a neuroscientist's perspective, a project like this is ambitious but premature; the target audience for this software would be unlikely to accept it as accurate and useful at this time. Relatedly, the current functionality of The Virtual Brain is too limited to be useful for most researchers.

#####Documentation
Documentation for The Virtual Brain is not linked directly from the website, but is available and relatively thorough. It describes most of the uses for various elements of the project and gives instructions for how to access the functionality through the GUI. Several tutorials are provided.

#####Code Readability
The organization of The Virtual Brain's code base requires quite a bit of familiarity with the project in order to be accessible. The code does, however, follow PEP conventions and has adequate comments, so individual files are not difficult to understand.

#####Software Engineering Practices
Because the majority of The Virtual Brain's developers are primarily neuroscientists, the software engineering practices employed in the project are not clear. Github is used for source control, but there does not appear to be a wiki or any other source of communication between developers. There also do not appear to be guidelines for outside developers to follow.

#####Opportunities to Contribute
It is not immediately clear whether opportunities to contribute to this project exist, let alone what those opportunities may be. Although there is an invitation to contribute to the code on The Virtual Brain's website, it seems that the project is mostly open source in the sense that it is offered under GPLv2 and users are welcome to modify the code for their own needs.

## Scikit-Learn
#### [Official Site](http://scikit-learn.org "SKL Official Site")  /   [Github Repo](https://github.com/scikit-learn/scikit-learn "SKL Github Repo") 

#####Background
Scikit-Learn is an open source Python library for machine learning. It was originally written as a toolkit for SciPy, another open source project, but has since been rewritten to be a separate library. It supports a variety of supervised and unsupervised algorithms, and allows some parameter customization. 

#####Developer Interest
The original version of this software was developed by David Cournapeau, but it has since been rewritten by a group of other developers. According to the project's Github, over 250 people have contributed to the project. According to his personal [website](http://fa.bianp.net/blog/pages/about.html "website"), Fabian Pedregosa, a French PhD student, was the lead developer/release manager until 2012. It is not clear who currently holds that role.

#####User Interest
Scikit-Learn is used by several major projects, such as Evernote and Mendeley. It is also used by Artificial Intelligence/Machine Learning researchers. Although there does not appear to be an active Users Google group, there is a community on [Stack Overflow](http://stackoverflow.com/questions/tagged/scikit-learn "Stack Overlow") and a mailing list.

#####Documentation
Although the documentation of Scikit-Learn can be hard to navigate--there are several different sections (i.e. User Guide, API, Quick Start, etc.) and it is not always entirely clear where to look--it is definitely thorough. It provides an introduction to machine learning with suggestions for which algorithms to use for various types of problems, along with detailed descriptions of how the algorithms are implemented in the software and how to use them. There is also a tutorial available, and links to presentations on how to use Scikit-Learn. 

#####Code Readability
Scikit-Learn code is very readable. It mostly follows PEP8 guidelines and is thoroughly commented. There are further coding guidelines provided that are specific to the Scikit-Learn repository, and serve to keep the code uniform.

#####Software Engineering Practices
According to the "Contributing" page of the Scikit-Learn website, "High-quality unit testing is a corner-stone of the sciki-learn development process." There is also a developer's [wiki](https://github.com/scikit-learn/scikit-learn/wiki "wiki") that is used for communication between developers and to plan sprints. To that end, the Scikit-Learn development community generally seems to rely on Agile practices. Git is used for source control, and there are specific instructions/guidelines for contributing to the project.

#####Opportunities to Contribute
There are many opportunities to contribute to Scikit-Learn. In fact, there is a page on the main website dedicated to helping new contributors get started. There is also an "easy" tag on the "Issues" page on Github that has suggestions for easy changes that can be implemented by new contributors. There is even a note encouraging newcomers to cut their teeth on these issues, as it allows the core developers to focus on bigger changes. Furthermore, additions and edits to documentation are encouraged.





