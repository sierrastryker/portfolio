# Sierra Stryker Portfolio

This portfolio highlights example projects that cover a range of topics, including data visualization and management and an agent-based model. 

In this introduction, I will briefly describe each project and demonstrate their viability for application in the workplace. 

All files are Quarto markdowns (.qmd) written in R and designed in RStudio. Quarto builds off of base R and RMarkdown, but uses a more intuitive interface and allows for enhanced visual formatting. 

---

## Agent-Based Model

`ABM.qmd`

This file demonstrates an organizational simulation that gives key insight into what strategies are effective for selection, performance appraisals, and firing. 

An agent-based model (ABM) is a type of simulation wherein individuals are represented by a simple set of rules and their subsequent behaviors can be measured and analyzed. For example, a researcher could evaluate the likelihood of employee turnover by simulating an applicant's person-environment fit and person-job fit. By programming the applicant with a series of rules about what circumstances they would leave their organization and then simulating different types of organizations, an ABM can give key insight into how likely an applicant is to leave, how much turnover should be expected, and the effectiveness of organizational interventions. 

My example ABM replicates Scullen et al. (2005) which simulated the strategy of terminating a uniform percentage of the workforce on an annual basis using performance evaluation scores. By doing so, organizations put more resources into hiring, but there was found to be a greater level of employee effectiveness over time. 

Within the model, agents are generated with randomized scores for potential and then given a performance evaluation and either retained or terminated based on their performance report. Performance values were calculated based on potential variable, but included an element of randomization representing potential inaccuracies or biases in evaluations. Furthermore, multiple simulations were run comparing values for the validity of the selection system, the selection ratio, the reliability of performance evaluations, the percentage of terminated employees, and the expected voluntary turnover rate.

Reference: 

Scullen, S. E., Bergey, P. K., & Aiman‐Smith, L. (2005). Forced distribution rating systems and the improvement of workforce potential: A baseline simulation. _Personnel Psychology_, _58_(1), 1-32.

---

## Data Visualization

`Data_Visualization.qmd`

This file highlights my skill with various types of graphing, including understanding how to create beautiful graphs that are appropriate for the data and can be easily incorporated into a presentation.


This demonstration of data visualization includes donut graphs, bar graphs, histograms, box and whisker plots, and density curves. The decision behind each type of graph is explained and notes are included for what each piece of code is accomplishing. All graphing is completed using the package ggplot2. 

Data management techniques were used to combine categories for the ethnicity groups within the dataset which were then graphed to show percentages. 

This dataset `dds.discr` is a publicly-available file from OpenIntro. It has information for demographics as well as the amount of financial support received for a developmental disability. Using data management and data visualization, technical and non-technical audiences can better understand ethnicity-based discrimination in expenditure amounts. The visualizations and information contained in this file can easily and quickly be transferred to a presentation.

Reference: 

Çetinkaya-Rundel, M., Diez, D., Bray, A., Kim, A., Baumer, B., Ismay, C., Paterno, N., Barr, C. (2023). _openintro: Data Sets and Supplemental Functions from 'OpenIntro' Textbooks and Labs_. http://openintrostat.github.io/openintro/, https://github.com/OpenIntroStat/openintro/.

---
