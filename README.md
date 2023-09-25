# Applied Data Science @ Columbia
## Fall 2023
## Project 1: What made you happy today?

![image](figs/word_cloud/Overview.jpeg)

### [Project Description](doc/Proj1_desc.md)
This project is to capture the cause of happiness moment based on plain text data.  

Term: Fall 2023

+ Projec title: Happy Moment Cause by NLP
+ This project is conducted by [Heze Ma]

+ This project is to capture the cause of happiness moment based on plain text data.
+ To delve deeper into the causes of happiness, we analyzed a dataset of 100,535 happy moments provided by 10,841 contributors. Although initial categories like affection and bonding provided a baseline understanding, they were too broad for our specific use case. We employed the Guided BERTopic method for topic modeling, which refined our original seven categories into 17 more detailed topics. This approach outperformed the benchmark model, LDA, in topic coherence evaluation. As a result, broader categories like "affection" were expanded to include more specific themes, such as "food". Visual aids, including pie charts and word clouds, were used to illustrate top topics across different age groups. Key findings revealed that while achievement, family, and food were universal sources of happiness, nuances existed; for instance, pets brought more joy to the elderly, entertainment resonated with the young, and online shopping emerged as a notable source of happiness for younger cohorts.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
