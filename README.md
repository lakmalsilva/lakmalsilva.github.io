
# On identifying technical debt using bug reports in practice

**Lakmal Silva**

**Licenciate Thesis in Software Engineering**

## Key Information

Defense date and location: June 12, 2023 at 0900.

Venue: Campus Gräsvik, J Building, Blekinge Institute of Technology, Karlskrona, Sweden

Opponent: Associate Professor Davide Taibi

Main supervisor: Associate professor Dr. Krzysztof Wnuk.

Supervisor: Senior lecturer Dr. Michael Unterkalmsteiner.

Examiner: Associate professor Dr. Krzysztof Wnuk.

## List of papers included in the thesis

### Chapter 2 - On designing a process for identifying Architectural Technical Debt from Bug Reports
 **L. Silva**, M. Unterkalmsteiner , K. Wnuk | <a href="https://github.com/lakmalsilva/lakmalsilva.github.io/blob/main/papers/ATD.pdf" target="_blank">Download</a>
  
#### Abstract

*Background:* A key challenge with Architectural Technical Debt (ATD) is ATD identification. Most existing methods use source code analysis that does not capture the hidden ATD in the architecture design. A few studies focus on ATD identification in software architecture design, but it is unclear whether they can scale to industrial contexts.

*Objectives:* We design and illustrate the evolution of an efficient ATD identification process using bug reports. Furthermore, we validate the process by analyzing actual bug reports filed by customers.

*Method:* Design Science Research was used to design and evolve an ATD identification process in three design iterations. The iterations were conducted at Ericsson, focusing on improving the process to scale in large software-intensive systems.

*Results:* We report how we engineered the ATD identification process. In particular, we illustrate the results from each design iteration, discuss the lessons learnt, and demonstrate the implementation of the final ATD identification process for decision-making activities at Ericsson. We identified 30 ATD related defects from a random sample of 251 bug reports that spanned over four releases of the system we investigated.

*Conclusions:* Our study indicates that bug reports can be used as a data source for identifying ATD using our proposed process and decision-making activities. Furthermore, we emphasize the need for clarity and consensus among the stakeholders regarding the scope and boundaries of architectural components that constitute a software system for the ATD analysis to be relevant.

### Chapter 3 - MultiDimEr: a multi-dimensional bug analyzEr
 **L. Silva**, M. Unterkalmsteiner , K. Wnuk | <a href="https://dl.acm.org/doi/pdf/10.1145/3524843.3528099" target="_blank">Download</a>
 
#### Abstract

*Background:* Bugs and bug management consumes a significant amount of time and effort from software development organizations. A reduction in bugs can significantly improve the capacity for new feature development.

*Aims:* We categorize and visualize dimensions of bug reports to identify accruing technical debt.  This evidence can serve practitioners and decision makers not only as an argumentative basis for steering improvement efforts, but also as a starting point for root cause analysis, reducing overall bug inflow.

*Method:* We implemented a tool, MultiDimEr, that analyzes and visualizes bug reports. The tool was implemented and evaluated at Ericsson.

*Results:* We present our preliminary findings using the MultiDimEr for bug analysis, where we successfully identified components generating most of the bugs and  bug trends within certain components.

*Conclusions:* By analyzing the dimensions provided by MultiDimEr, we show that classifying and visualizing bug reports in different dimensions can stimulate discussions around bug hot spots as well as validating the accuracy of manually entered bug report attributes used in technical debt measurements such as fault slip through.
                    
### Chapter 4 - Towards identifying and minimizing customer-facing documentation debt
**L. Silva**, M. Unterkalmsteiner , K. Wnuk | <a href="https://github.com/lakmalsilva/lakmalsilva.github.io/blob/main/papers/doc_debt.pdf" target="_blank">Download</a>

#### Abstract

*Background:* Software documentation often struggles to catch up with the pace of software evolution. The lack of correct, complete, and up-to-date documentation results in an increasing number of documentation defects which could introduce delays in integrating software systems. In our previous study on a bug analysis tool called MultiDimEr, we provided evidence that documentation-related defects contribute to a significant number of bug reports.

*Aims:* First, we want to identify documentation defect types contributing to documentation defects and thereby identifying documentation debt. Secondly, we aim to find pragmatic solutions to minimize most common documentation defects to pay off the documentation debt in the long run.

*Method:* We investigated documentation defects related to an industrial software system. First, we looked at the types of different documentation and associated bug reports. We categorized the defects according to an existing documentation defect taxonomy.

*Results:* Based on a sample of 101 defects, we found that a majority of defects are caused by documentation defects falling into the Information Content (What) category (86). Within this category, the documentation defect types Erroneous code examples (23), Missing documentation (35), and Outdated content (19) contributed to most of the documentation defects. We propose to adapt two solutions to mitigate these types of documentation defects.

*Conclusions:* In practice, documentation debt can easily go undetected since a large share of resources and focus is dedicated to deliver high-quality software. This study provides evidence that documentation debt can contribute to increase in maintenance costs due to the number of documentation defects. We suggest to adapt two main solutions to tackle documentation debt by implementing (i) Dynamic Documentation Generation (DDG) and/or (ii) Automated Documentation Testing (ADT), which are both based on defining a single and robust information source for documentation.
   
