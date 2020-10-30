# leak_study

Paper: Memory and resource leak defects and their repairs in Java projects [Springer](https://link.springer.com/article/10.1007/s10664-019-09731-8)

To cite this paper:
> Ghanavati, M., Costa, D., Seboek, J. et al. Memory and resource leak defects and their repairs in Java projects. Empir Software Eng 25, 678–718 (2020). https://doi.org/10.1007/s10664-019-09731-8

A detailed empirical study on 491 issues from 15 large open-source Java projects. The study proposes taxonomies for the leak types, for the defects causing them, and for the repair actions. In particular, this study tries to answer the following research questions:

- RQ1. What is distribution of leak types in studied projects?
- RQ2. How are leak-related defects detected?
- RQ3. To what extent are the leak-inducing defects localized?
- RQ4. What are the most common root causes?
- RQ5. What are the characteristics of the repair patches?
- RQ6. How complex are repairs of the leak-inducing defects?

To build a suitable dataset for our study, we apply a four-step filtering methodology: (1) keyword search, (2) issue type filtering, (3) resolution filtering, and (4) manual investigation. This four-step filtering method yields a dataset with 491 leak-related issues, each representing a unique leak bug report (i.e., none are duplicates of another).
