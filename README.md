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
- [Google Trends](https://trends.google.com/trends/explore?date=today%205-y&geo=US&q=remote%20work)
### Code Source
- [Tutorial | Prediction](https://github.com/Rising-Stars-by-Sunshine/stats201-tutorial-prediction/tree/main/code)
### Articles
- [“Remote Work Before, During, and after the Pandemic.”](https://www.ncci.com/SecureDocuments/QEB/QEB_Q4_2020_RemoteWork.html)
- [“A Two-Year, 50-Million-Person Experiment in Changing How We Work.”](https://www.nytimes.com/2022/03/10/business/remote-work-office-life.html)
- [“Accelerating Remote Work after COVID-19.”](https://www.thecgo.org/research/accelerating-remote-work-after-covid-19/)
- [Parker, Kim, Juliana Horowitz, and Rachel Minkin. 2020. “How Coronavirus Has Changed the Way Americans Work.”](https://www.pewresearch.org/social-trends/2020/12/09/how-the-coronavirus-outbreak-has-and-hasnt-changed-the-way-americans-work/)

### Literature

**Chicago Author-Date Format**

Battisti, Enrico, Simona Alfiero, and Erasmia Leonidou. 2022. “Remote Working and Digital Transformation during the COVID-19 Pandemic: Economic–Financial Impacts and Psychological Drivers for Employees.” Journal of Business Research 150 (June). https://doi.org/10.1016/j.jbusres.2022.06.010.

Brynjolfsson, Erik, John Horton, Adam Ozimek, Daniel Rock, Garima Sharma, and Hong-Yi TuYe. 2020. “COVID-19 and Remote Work: An Early Look at US Data.” National Bureau of Economic Research, June. https://doi.org/10.3386/w27344.

Coate, Patrick. 2021. “Remote Work Before, During, and after the Pandemic.” Www.ncci.com. January 25, 2021. https://www.ncci.com/SecureDocuments/QEB/QEB_Q4_2020_RemoteWork.html.

Fan, Wen, and Phyllis Moen. 2023. “Ongoing Remote Work, Returning to Working at Work, or in between during COVID-19: What Promotes Subjective Well-Being?” Journal of Health and Social Behavior, January, 002214652211502. https://doi.org/10.1177/00221465221150283.

Galanti, Teresa, Gloria Guidetti, Eleonora Mazzei, Salvatore Zappalà, and Ferdinando Toscano. 2021. “Work from Home during the COVID-19 Outbreak.” Journal of Occupational & Environmental Medicine 63 (7): 426–32. https://doi.org/10.1097/jom.0000000000002236.

Goldberg, Emma. 2022. “A Two-Year, 50-Million-Person Experiment in Changing How We Work.” The New York Times, March 10, 2022, sec. Business. https://www.nytimes.com/2022/03/10/business/remote-work-office-life.html.

Google. 2023. “Google Trends.” Google Trends. February 28, 2023. https://trends.google.com/trends/explore?date=today%205-y&geo=US&q=remote%20work.
Gupta, Arpit. 2020. “Accelerating Remote Work after COVID-19.” The CGO. April 30, 2020. https://www.thecgo.org/research/accelerating-remote-work-after-covid-19/.

Jacks, Tim. 2021. “Research on Remote Work in the Era of COVID-19.” Journal of Global Information Technology Management 24 (2): 93–97. https://doi.org/10.1080/1097198x.2021.1914500.

Ozimek, Adam. 2020. “The Future of Remote Work.” SSRN Electronic Journal, May. https://doi.org/10.2139/ssrn.3638597.

Parker, Kim, Juliana Horowitz, and Rachel Minkin. 2020. “How Coronavirus Has Changed the Way Americans Work.” Pew Research Center’s Social & Demographic Trends Project. December 9, 2020. https://www.pewresearch.org/social-trends/2020/12/09/how-the-coronavirus-outbreak-has-and-hasnt-changed-the-way-americans-work/.

Tomić, Damir, and Karla Vizinger. 2023. “Effects of Remote Business during the Covid-19 Pandemic - a Literature Review.” American Journal of Economics and Business Innovation 2 (1): 1–13. https://doi.org/10.54536/ajebi.v2i1.1088.

Tursunbayeva, Aizhan, Stefano Di Lauro, and Gilda Antonelli. 2021. “Remote Work at the Time of COVID-19 Pandemic and Beyond: A Scoping Review.” HR Analytics and Digital HR Practices, December, 127–69. https://doi.org/10.1007/978-981-16-7099-2_6.

**BibTex Format**

```
@article{ozimek_2020_the,
  author = {Ozimek, Adam},
  month = {05},
  title = {The Future of Remote Work},
  doi = {10.2139/ssrn.3638597},
  url = {https://content-static.upwork.com/blog/uploads/sites/6/2020/05/26131624/Upwork_EconomistReport_FWR_052020.pdf},
  year = {2020},
  journal = {SSRN Electronic Journal}
}

@article{jacks_2021_research,
  author = {Jacks, Tim},
  month = {04},
  pages = {93-97},
  title = {Research on Remote Work in the Era of COVID-19},
  doi = {10.1080/1097198x.2021.1914500},
  volume = {24},
  year = {2021},
  journal = {Journal of Global Information Technology Management}
}

@article{galanti_2021_work,
  author = {Galanti, Teresa and Guidetti, Gloria and Mazzei, Eleonora and Zappal√†, Salvatore and Toscano, Ferdinando},
  month = {04},
  pages = {426-432},
  title = {Work from Home during the COVID-19 Outbreak},
  doi = {10.1097/jom.0000000000002236},
  url = {https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8247534/},
  volume = {63},
  year = {2021},
  journal = {Journal of Occupational & Environmental Medicine}
}

@article{brynjolfsson_2020_covid19,
  author = {Brynjolfsson, Erik and Horton, John and Ozimek, Adam and Rock, Daniel and Sharma, Garima and TuYe, Hong-Yi},
  month = {06},
  title = {COVID-19 and remote work: An early look at US data},
  doi = {10.3386/w27344},
  year = {2020},
  journal = {National Bureau of Economic Research}
}

@article{tomi_2023_effects,
  author = {Tomiƒá, Damir and Vizinger, Karla},
  month = {01},
  pages = {1‚Äì13},
  title = {Effects of Remote Business During the Covid-19 Pandemic - A Literature Review},
  doi = {10.54536/ajebi.v2i1.1088},
  url = {https://journals.e-palli.com/home/index.php/ajebi/article/view/1088/483},
  urldate = {2023-01-21},
  volume = {2},
  year = {2023},
  journal = {American Journal of Economics and Business Innovation}
}

@article{fan_2023_ongoing,
  author = {Fan, Wen and Moen, Phyllis},
  month = {01},
  pages = {002214652211502},
  title = {Ongoing Remote Work, Returning to Working at Work, or in between during COVID-19: What Promotes Subjective Well-being?},
  doi = {10.1177/00221465221150283},
  urldate = {2023-02-28},
  year = {2023},
  journal = {Journal of Health and Social Behavior}
}

@misc{gupta_2020_accelerating,
  author = {Gupta, Arpit},
  month = {04},
  title = {Accelerating Remote Work After COVID-19},
  url = {https://www.thecgo.org/research/accelerating-remote-work-after-covid-19/},
  year = {2020},
  organization = {The CGO}
}

@article{tursunbayeva_2021_remote,
  author = {Tursunbayeva, Aizhan and Di Lauro, Stefano and Antonelli, Gilda},
  month = {12},
  pages = {127-169},
  title = {Remote Work at the Time of COVID-19 Pandemic and Beyond: A Scoping Review},
  doi = {10.1007/978-981-16-7099-2_6},
  year = {2021},
  journal = {HR Analytics and Digital HR Practices}
}

@article{battisti_2022_remote,
  author = {Battisti, Enrico and Alfiero, Simona and Leonidou, Erasmia},
  month = {06},
  title = {Remote working and digital transformation during the COVID-19 pandemic: Economic‚Äìfinancial impacts and psychological drivers for employees},
  doi = {10.1016/j.jbusres.2022.06.010},
  volume = {150},
  year = {2022},
  journal = {Journal of Business Research}
}

@misc{parker_2020_how,
  author = {Parker, Kim and Horowitz, Juliana and Minkin, Rachel},
  month = {12},
  title = {How Coronavirus Has Changed the Way Americans Work},
  url = {https://www.pewresearch.org/social-trends/2020/12/09/how-the-coronavirus-outbreak-has-and-hasnt-changed-the-way-americans-work/},
  year = {2020},
  organization = {Pew Research Center‚Äôs Social & Demographic Trends Project}
}

@misc{_2023_google,
  author = {, Google},
  month = {02},
  title = {Google Trends},
  url = {https://trends.google.com/trends/explore?date=today%205-y&geo=US&q=remote%20work},
  urldate = {2023-02-28},
  year = {2023},
  organization = {Google Trends}
}

@misc{coate_2021_remote,
  author = {Coate, Patrick},
  month = {01},
  title = {Remote Work Before, During, and After the Pandemic},
  url = {https://www.ncci.com/SecureDocuments/QEB/QEB_Q4_2020_RemoteWork.html},
  year = {2021},
  organization = {www.ncci.com}
}

@article{goldberg_2022_a,
  author = {Goldberg, Emma},
  month = {03},
  title = {A Two-Year, 50-Million-Person Experiment in Changing How We Work},
  url = {https://www.nytimes.com/2022/03/10/business/remote-work-office-life.html},
  year = {2022},
  organization = {The New York Times},
  journal = {The New York Times}
}
![image](https://user-images.githubusercontent.com/122700704/223400778-a66b17a9-8a52-4eff-bdc7-1431c17a7c9a.png)

```

Thank you!
