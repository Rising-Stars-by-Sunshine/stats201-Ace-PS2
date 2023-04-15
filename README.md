# Forecasting Remote Job Search Trends with Machine Learning: Analyzing Google Search Volumes as a Time Series
## Project information
- **Author**: Ace Asim, Ethics and Leadership (Public Policy), Class of 2025, Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2023 Spring Term (Seven Week - First) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: Acknowledgements to Prof. Luyao Zhang and Ava Baker whom this project could not be done without.

- **Project Summary**: 
The COVID-19 pandemic has led to a significant increase in interest in remote work. This study applies machine learning methods to Google search trend data related to "Remote Jobs" to forecast future demand for such jobs. The study aims to answer the following research questions: How has the demand for remote jobs changed over time, especially during and after the COVID-19 pandemic? What factors contribute to this change in demand? To answer these questions, we collect and analyze search volume data from Google Trends and complement this with a literature review of changing perceptions of remote work. The findings reveal that interest in remote jobs has increased since the COVID-19 pandemic and is expected to continue to grow in the future. The intellectual merits of this research are twofold: first, it contributes to the growing body of research on remote work and its impact on the labor market; second, it demonstrates the potential of machine learning methods to analyze and forecast demand for different job types. The practical impact of this research is significant, as it can inform policymakers, employers, and job seekers about the changing nature of work and help them make informed decisions.

## Table of Contents
- [data](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Ace/tree/main/data)
- [code](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Ace/tree/main/code)
- [spotlight](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Ace/tree/main/spotlight)



## Data
- Data Source: https://trends.google.com/trends/explore?date=today%205-y&geo=US&q=remote%20work | [Data File](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Ace/blob/main/data/Queried_Data/Remote%20Work%20Google%20Trends%20-%20Sheet1.csv)
- [Queried Data](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Ace/tree/main/data/Queried_Data)
- [Processed Data](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Ace/tree/main/data/Processed_Data)


## Code
- [Query Data](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Ace/blob/main/code/Query_Data.ipynb)
- [Process Data](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Ace/blob/main/code/Process_Data.ipynb)
- [Analyze Data](https://github.com/Rising-Stars-by-Sunshine/stats201-PS2-Ace/blob/main/code/Analyze_Data.ipynb)

## Spotlight
**Figure 1: Random Forest Regression**

![image](https://user-images.githubusercontent.com/122700704/232252695-f7ca8fe0-f392-41e4-9424-1f0fd6176ba3.png)

*Source: [Google Trends](https://trends.google.com/trends/explore?date=today%205-y&geo=US&q=remote%20work) Created By: [sklearn.ensemble.RandomForestRegressor](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html)*

**Figure 2: Random Forest Regression**

![image](https://user-images.githubusercontent.com/122700704/232252891-8d377dc3-2dfd-4cc7-bd8c-4ff0d5bfd099.png)



## References

### Data Source
- Data Source Title and URL
### Code Source
- Code Source Title and URL
### Articles
- Article Source Title and URL
### Literature
- Literature References in [Chicago Author-Date](https://www.chicagomanualofstyle.org/tools_citationguide/citation-guide-2.html) Style and [BibTex](https://scholar.google.com/) 

Levin, Dan, and Luyao Zhang. 2020. “Bridging Level-K to Nash Equilibrium.” *The Review of Economics and Statistics* 104 (6): 1329–40. https://doi.org/10.1162/rest_a_00990.

```
@article{levin2022bridging,
  title={Bridging level-k to nash equilibrium},
  author={Levin, Dan and Zhang, Luyao},
  journal={Review of Economics and Statistics},
  volume={104},
  number={6},
  pages={1329--1340},
  year={2022},
  publisher={MIT Press One Rogers Street, Cambridge, MA 02142-1209, USA journals-info~…}
}
```

