# Comparative Sentiment Analysis in Traditional vs. Digital Banking: The Case of Deutsche Bank and N26
## Project Overview
### Objective: 
Analyzed and compared employee sentiment in traditional and digital banking environments to understand differences in job satisfaction and organizational culture.

### Methodology:
- Conducted Exploratory Data Analysis (EDA) to understand review distribution and ratings.

- Employed Topic Modeling and K-means Clustering to identify key themes and group similar sentiments.

- Performed Sentiment Analysis on Glassdoor reviews to assess employee satisfaction across various work aspects.

### Tools: 
Python (Pandas, NLTK, Scikit-learn), R (tidyverse, ggplot2), Glassdoor API, Jupyter Notebook.

### Key Findings:
- **Exploratory Data Analysis:** Identified distinct organizational structures and reviewed distributions between Deutsche Bank and N26.

- **Clustering Classification:** Revealed key areas of positive and negative feedback for both organizations.

- **Sentiment Analysis:**
  
- ***Overall Sentiment:*** N26 exhibited higher positive sentiment in compensation and career progression.

- ***Work Aspects:***
  Compensation - Higher satisfaction at N26
  
  Collaboration - Positive sentiment towards teamwork at both companies

  Management and Leadership - Mixed reviews, with N26 facing more negative sentiment
  
  Work-Life Balance - More positive sentiment at Deutsche Bank

  Company Culture - High satisfaction at both companies

  Career Progression - More positivity at N26, with mixed feelings at Deutsche Bank.
  
### Impact: 
Provided actionable insights for Deutsche Bank to improve compensation structures and career advancement pathways, aligning with progressive practices observed in FinTech companies like N26.

## Executive Summary
Germany leads the global FinTech landscape as the fourth-largest market worldwide and the largest within the EU, driven by its robust digital infrastructure (ITA, 2023). Traditional banks and emerging FinTechs exhibit divergent organizational cultures, highlighting the importance of understanding employee sentiment for maintaining a competitive edge. Through systematic exploration, data preprocessing, topic modeling, K-means clustering, and sentiment analysis of Glassdoor reviews, the project, titled “Comparative Sentiment Analysis in Traditional vs. Digital Banking: The Case of Deutsche Bank and N26”, aims to uncover differences in job satisfaction and organizational culture, providing insights into the banking sector's dynamics.

**Key Findings:**

**-	Exploratory Data Analysis (EDA):** Deutsche Bank has multiple office locations, while N26 is centralized in Berlin. Job titles at Deutsche Bank vary widely, whereas N26 reviews mainly come from anonymous employees and software engineers. Deutsche Bank receives 4-star ratings, whereas N26 ratings range from 3 to 5 stars.

**-	Clustering Classification:** At Deutsche Bank, positive feedback centers on teamwork and work opportunities, while negative comments focus on compensation and career progression. Conversely, N26 employees are satisfied with flexible team dynamics and development opportunities but express concerns about internal politics and management practices.

**-	Employee Sentiment Analysis:** N26 exhibits higher positive sentiment across all aspects, particularly in compensation and career progression, compared to Deutsche Bank.

**-	Employee Sentiment Through Work Aspects:** 

***o	Compensation:*** While Deutsche Bank receives mixed sentiment regarding salary, N26's employees overwhelmingly express satisfaction with both salary and benefits.

***o	Collaboration:*** Both organizations exhibit strong positive sentiments towards colleagues and teamwork, indicating supportive workplace cultures.

***o	Management and Leadership:*** Satisfaction with managers and leaders is generally high at both companies, but negative sentiment towards management is more prevalent at N26.

***o	Work-Life Balance:*** Deutsche Bank employees perceive a higher level of positivity regarding work-life balance compared to N26.

***o	Company Culture:*** Employees at both companies report high satisfaction with the company culture and the work environment.

***o	Career Progression:*** N26 employees express more positivity toward career opportunities compared to Deutsche Bank, where there are mixed feelings, especially about promotions.

The comparative analysis of employee sentiment reveals that N26 stands out with higher levels of employee satisfaction regarding salary, benefits, and career opportunities compared to Deutsche Bank, reflecting a company culture that prioritizes and supports employee development. While employees from both institutions appreciate the collaborative environment, work-life balance, and company culture, N26 faces challenges in management perception. Conversely, Deutsche Bank displays a wider spectrum of sentiments, particularly regarding negative feedback on career progression. To remain competitive, Deutsche Bank should reevaluate its compensation structures and career advancement pathways, aligning them with the progressive practices observed in FinTechs like N26, which resonate better with employees.

## Introduction and Motivation

According to the official websites of the International Trade Administration (ITA) and Germany Trade and Invest (GTAI), Germany leads the global financial technology (FinTech) landscape, positioned as the fourth-largest market worldwide and the largest within the European Union. Germany's FinTech demand and market size are expected to grow continuously, as the country offers a robust digital infrastructure to meet customers’ growing demand for innovative financial services (ITA, 2023). As Germany’s financial sector rapidly evolves through digital transformation, traditional banks and FinTech firms exhibit distinct organizational structures and cultures. Understanding employee sentiment is vital to maintaining operational efficiency for competitive advantage. This leads to my research question: how do employee reviews reflect the differences in job satisfaction and organizational culture between traditional banks (Deutsche Bank) and FinTech companies (N26)?

The hypothesis is that analyzing employee reviews will reveal distinct sentiment trends and themes related to job satisfaction, management practices, and work-life balance across traditional banks, exemplified by Deutsche Bank, and FinTech companies such as N26. The paper by Ramanathan and Thirunavukkarasu (2019) mentions the Maslow theory, describing 5 hierarchy stages of needs (psychological needs, safety needs, social belonging needs, esteem needs, and self-actualization needs) which can help me identify the direction of employee sentiment within the organizations. Regarding my assumption, N26, one of the FinTech companies, will exhibit more positive employee sentiment compared to Deutsche Bank, one of the traditional banks. Contrasting theories suggest that traditional banks’ stability may foster equally positive employee sentiment. However, this project aims to provide actionable insights into organizational culture and areas for improvement.

The motivation behind this research comes from the contrasting organizational structures and cultures between traditional banks and emerging FinTech firms through the rapid evolution of the financial sector. Employee satisfaction significantly influences banks’ operational efficiency, particularly in Germany's rapidly digitizing financial service industry. This research is crucial for understanding which organizational structure aligns with my professional goals in both traditional and digital banking. In addition, analyzing employee reviews from Deutsche Bank and N26 can also  enhance industry knowledge on talent retention and organizational development. 

## Sample, Data, Corpus
The qualitative data consists of employee reviews extracted by web scraping from the Glassdoor platform, representing two distinct entities within the financial service sector: Deutsche Bank, a traditional bank, and N26, a FinTech company. 

Each dataset (“db” and “n26”) has 200 observations of job reviews from Deutsche Bank and N26 for ensuring a balanced representation to mitigate potential biases arising from dataset size discrepancies. 

Each dataset has six features, including five categorical variables: ‘Employee Title’, ‘Location’, ‘Pros’, ‘Cons’, and ‘Company Name’. Additionally, a numerical variable is the ‘Rating’ of employees. The ‘Pros’ and ‘Cons’ columns consist of positive and negative sentiments based on the respective organizations' work environments, facilitating comparative analysis between Deutsche Bank and N26 across various dimensions such as work-life balance, compensation, organizational culture, and more.

I intend to analyze only the most recent Glassdoor reviews to ensure that my findings reflect the organization’s current status. Core sampling characteristics include the review's sentiment, specific mentions of organizational aspects, and overall employee satisfaction. 

## Conclusion

In summary, my analysis of employee reviews provides clear differences in job satisfaction and organizational culture between Deutsche Bank, a traditional bank, and N26, a FinTech company. While both exhibit strengths in collaboration, work-life balance, and company culture, distinct perceptions emerge in compensation and career progression. N26 employees express predominantly positivity towards salary, benefits, and career opportunities, reflecting a robust emphasis on competitive compensation and a growth-oriented culture. In contrast, while Deutsche Bank receives favorable feedback on benefits, sentiments towards salary are more nuanced, suggesting potential variations in compensation satisfaction. Additionally, perceptions of management and leadership differ, with Deutsche Bank generally exhibiting higher satisfaction levels. Conversely, negative sentiment towards management is more prevalent at N26, suggesting potential challenges in leadership practices. Overall, these insights underscore the imperative for traditional banks to adapt to changing employee expectations and industry dynamics to enhance job satisfaction and foster a positive organizational culture, aligning with the practices seen in innovative FinTech companies like N26.

## Limitations
However, I acknowledge that these findings may not completely represent the experiences of all employees within traditional banks and FinTech companies. Therefore, it is essential to consider the following limitations.

(1)	Bias in Reviews: Glassdoor reviews may be biased, as extreme opinions are more likely to be expressed, potentially skewing the analysis. 

(2)	Temporal Considerations: Employee sentiments can change over time due to various factors. Analyzing reviews at a single point may not capture these variations adequately. 

(3)	Data Quality: Data reliability from Glassdoor reviews varies, and automated sentiment analysis may not always accurately capture nuances.

(4)	Generalizability: Findings from Deutsche Bank and N26 reviews may not apply to all traditional banks or FinTech firms in Germany due to factors like organizational culture and location.

(5)	Limited Scope: Reviews from Glassdoor may not capture all work aspects of the employee experience such as attitudes toward innovation and technology adoption, including diversity and inclusion efforts.

Addressing these limitations will lead to a more comprehensive assessment of the project's constraints and considerations.

## Outlook
To conduct a more comprehensive comparative analysis, it is valuable to explore additional methods for further research and to consider the potential applications of the findings.

(1)	 Further Comparative Analysis: Including more traditional banks and FinTech firms in diverse regions or similar market scales can provide a broader perspective on job satisfaction and organizational culture in Germany's banking sector.

(2)	Longitudinal Study: Tracking changes in employee sentiment over time within Deutsche Bank and N26 could reveal trends or patterns in job satisfaction and organizational culture evolution.

(3)	Impact of External Factors: Exploring how regulations, market trends, and technological advancements interact with job satisfaction and organizational culture can enhance the interpretation of findings.

(4)	Employee Retention and Performance: Analyzing the relationship between employee sentiment, retention rates, and performance metrics could provide actionable insights for human resource management.

(5)	Cross-Cultural Analysis: Conducting cross-cultural analyses on job satisfaction between traditional banks and FinTech companies can assess the impact of cultural factors across diverse contexts.

Exploring these methods can provide valuable insights into job satisfaction, organizational culture, and employee sentiment within the banking sector.

## References

Bordoloi, M., & Biswas, S. K. (2023). Sentiment analysis: A survey on design framework, applications and future scopes. Artificial intelligence review, 1–56. *Advance online publication*. [https://doi.org/10.1007/s10462-023-10442-2](https://doi.org/10.1007/s10462-023-10442-2)

Chin, Chiew. (2020). Text Analytics On Company Reviews In Jobstreet. *European Proceedings of Social and Behavioural Sciences*. [https://www.researchgate.net/publication/340293535_Text_Analytics_On_Company_Reviews_In_Jobstreet](https://www.researchgate.net/publication/340293535_Text_Analytics_On_Company_Reviews_In_Jobstreet)

Feng, S. (2023). Job satisfaction, management sentiment, and financial performance: Text analysis with job reviews from indeed.com. *International Journal of Information Management Data Insights*. [https://www.sciencedirect.com/science/article/pii/S2667096823000022](https://www.sciencedirect.com/science/article/pii/S2667096823000022#section-cited-by) 

Frank, F. F., & Whittle, T. E. (n.d.). Predicting company ratings through Glassdoor Reviews. *Department of Management Science and Engineering Stanford University*. [https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1184/reports/6880837.pdf](https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1184/reports/6880837.pdf)

H. Yadav, K. Dwivedi and G. Abirami. (2022). Sentiment Analysis of company reviews using Machine Learning. *2022 3rd International Conference for Emerging Technology (INCET), Belgaum, India*. [https://ieeexplore.ieee.org/document/9824505](https://ieeexplore.ieee.org/document/9824505)

Höllig, C. E. (2021). Online Employer Reviews: Text-Mining Analyses of Contents, Effects, and Employer Responsiveness. *TUM School of Management*. [https://mediatum.ub.tum.de/doc/1594000/1594000.pdf](https://mediatum.ub.tum.de/doc/1594000/1594000.pdf)

Jung, Y., & Suh, Y. (2019). Mining the voice of employees: A text mining approach to identifying and analyzing job satisfaction factors from online employee reviews. *Decis. Support Syst., 123*. [https://api.semanticscholar.org/CorpusID:196185822](https://api.semanticscholar.org/CorpusID:196185822)

Luo, N., Zhou, Y., & Shon, J. (2016). Employee Satisfaction and Corporate Performance: Mining Employee Reviews on Glassdoor.com. *International Conference on Interaction Sciences*. [https://core.ac.uk/download/pdf/301370386.pdf](https://core.ac.uk/download/pdf/301370386.pdf)

Martinez, L. D. (2019). Improving employee satisfaction through text analytics. *SESUG Paper*. [https://www.lexjansen.com/sesug/2019/SESUG2019_Paper-243_Final_PDF.pdf](https://www.lexjansen.com/sesug/2019/SESUG2019_Paper-243_Final_PDF.pdf)

Morshed Adib, Muhammed & Chakraborty, Sovon & Waishy, Mashiwat & Mehedi, Md Humaion Kabir & Rasel, Annajiat Alim. (2023). BiLSTM-ANN Based Employee Job Satisfaction Analysis from Glassdoor Data Using Web Scraping. *Procedia Computer Science*. [https://www.researchgate.net/publication/373570703_BiLSTM-ANN_Based_Employee_Job_Satisfaction_Analysis_from_Glassdoor_Data_Using_Web_Scraping](https://www.researchgate.net/publication/373570703_BiLSTM-ANN_Based_Employee_Job_Satisfaction_Analysis_from_Glassdoor_Data_Using_Web_Scraping)

Ramanathan, V. & Thirunavukkarasu, M. (2019). Prediction of Individual’s Character in Social Media Using Contextual Semantic Sentiment Analysis. Mobile Networks and Applications. 24. [https://doi.org/10.1007/s11036-019-01388-3](https://doi.org/10.1007/s11036-019-01388-3)

Uchida, E., Kino, Y. (2021). Study on the relationship between employee satisfaction and corporate performance in Japan via text mining. *Procedia Computer Science*.  [https://www.sciencedirect.com/science/article/pii/S1877050921016732](https://www.sciencedirect.com/science/article/pii/S1877050921016732) 

Uyeno, L. (2020). An empirical analysis of company culture: Using Glassdoor data to measure the impact of culture and employee satisfaction on performance. *Scholarship @ Claremont*. [https://scholarship.claremont.edu/cmc_theses/2293/](https://scholarship.claremont.edu/cmc_theses/2293/)

Young, L. M., & Gavade, S. R. (2018). Translating emotional insights from hospitality employees’ comments: Using sentiment analysis to understand job satisfaction. *International Hospitality Review*. [https://www.emerald.com/insight/content/doi/10.1108/IHR-08-2018-0007/full/html](https://www.emerald.com/insight/content/doi/10.1108/IHR-08-2018-0007/full/html)






