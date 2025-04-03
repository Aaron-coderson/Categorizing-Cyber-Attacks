# Categorizing Cyber Attacks
**Analysis of Industry, Event-Type, Economic and Criminological Factors**

## What is here?  
This repository contains the majority of my data, code, and results for my project. 
(GSDSEF poster, slides, and notebook included in folder)

## Where is this project going?  
So far: **GSDSEF** in the Behavioral and Social Sciences category. 
Won **second place** award in category.

## Details about my research project:

### 1. Abstract  
This work determines which **industries** are most affected by **cyber-attacks**, which **types of attacks** are most prevalent, and their **underlying causes**.  

The **hypothesis** is that the **healthcare industry** experiences the **greatest number of cyber-attacks** due to a **large concentration of personal data**, **recurrent access** to the data by numerous individuals, and **potentially outdated systems**.  

First, **data** was obtained from the publicly available **Center for International and Security Studies at Maryland (CISSM)** website. Then, **data analysis** and **visualization** were performed using **Python programming** in the **Google Colab** environment to identify insights and classify cyber-attacks based on **economic** and **criminological factors**.  

The **analysis** indicates that in **recent years**, the **healthcare and social assistance industry** has been the **most targeted** by cyber-attacks due to the increasing adoption of **Electronic Health Records**. However, across the **entire decade**, the **public administration industry** had the **highest number of cyber-attacks**. This finding is **close but not exactly consistent** with the research **hypothesis**. The work then proceeded with a **detailed analysis** of cyber-attacks, their classification by **attack type, motive, and actors**, and an explanation for the **discrepancy** with the **hypothesis**.  

The **conclusion** of the detailed analysis is that:  
1. When considering **exploitative attacks** or those with a **financial motive**, **healthcare** has the **greatest number of cyber-attacks**.  
2. **Politically motivated disruptive attacks** resulted in **public administration** having the **greatest number of cyber-attacks**.  

Such **classification of attacks** is expected to assist **industries** and **governments** in safeguarding against **cyber-attacks**. Furthermore, this study illustrates the **efficacy of data science** and **data visualization** in understanding **social science**.  


From an applications perspective, such classification of attacks is expected to assist industries and governments in setting policies and implementing procedures to help safeguard against cyber-attacks. Further, such a study illustrates the efficacy of data science and data visualization in understanding social science.

### 2. Data Used  
This data science project uses data sourced from the **Center for International and Security Studies at University of Maryland (CISSM)**. The data, *Cyber Events Database*, is a record of scraped publications of cyber-attack events occurring since 2014 to 2024 with over 14,000 recorded events.  
I downloaded the cyber events dataset from this link:  
[Cyber Events Database](https://cissm.umd.edu/cyber-events-database)

I also used data from **The World Bank’s Poverty & Inequality Indicators (PIP)**, which include various economic describing variables per country, including GDP, wealth gap, Gini coefficient, etc.  
I downloaded the PIP dataset from this link:  
[Poverty & Inequality Indicators](https://pip.worldbank.org/poverty-calculator)

### 3. Discussion/Key Findings  
- **Consistent with the hypothesis**, two out of three of the most recent full years, i.e., 2021 and 2023, attacks on healthcare were highest. The increasing trend of attacks on healthcare and its correlation with the adoption of electronic health records agrees with the basis of the hypothesis.  

- **Considering the whole decade (2014–2024)**, the public administration industry has the highest number of cyber-attacks, followed by health care and social assistance.  
  - This finding is close but not exactly consistent with the research hypothesis that health care would have the highest number of attacks.  
  - The work then proceeded with a **detailed analysis** of cyber-attacks and their classification by **attack type, motive, and actors**.  

- **Key findings on attack characteristics**:  
  - **Public administration vs. health care & social assistance**:  
    - Public administration experiences approximately **20% more disruptive attacks** than exploitative attacks.  
    - Health care & social assistance is dominated by **exploitative attacks, which are about 3 times higher** than disruptive attacks.  

  - **Actor types**:  
    - **Public administration**:  
      - Attacked **56% by criminals** and **42% by politically or ideologically motivated nation-states and hacktivists**.  
    - **Health care & social assistance**:  
      - **96% of attacks** come from criminals.  

  - **Attack motives**:  
    - **Public administration**:  
      - **51% of attacks** had a **non-financial** motive.  
    - **Health care & social assistance**:  
      - **97% of attacks** had a **financial** motive.  

  - **Motive and actor differences between exploitative and disruptive attacks**:  
    - **Exploitative attacks**:  
      - **78% had financial motives**.  
      - **85% were committed by non-political criminal actors**.  
    - **Disruptive attacks**:  
      - **52% had non-financial motives**.  
      - **60% were committed by criminal actors**, but with a **larger presence of political actors**.  

- **Key insight supporting the hypothesis**:  
  - When considering **cyber-attacks only by non-political actors** (i.e., excluding nation-states and hacktivists), **health care & social assistance has the highest number of cyber-attacks**, supporting the research hypothesis.  

- **Economic and geopolitical factors**:  
  - Countries with **higher GDP** and **greater equality (Gini coefficient)** experience **more frequent cyber-attacks**.  
  - This is because such countries:  
    - Have **more economic goods to capture**.  
    - Are **more likely to be targeted by political actors** due to their global influence.  

- **Predictability of cyber-attacks**:  
  - Based on **my ARIMA time-series model** of cyber-attack data, trends in cyber-attacks are **predictable**.  
  - This finding could be used to **enhance security during periods of increased vulnerability**.  

### 4. Conclusion  
- **Validation of Hypothesis**:  
  - My hypothesis that **healthcare would be the most targeted industry for cyber-attacks** was proven accurate in recent years.  
  - This is due to the **recent adoption of Electronic Health Records (EHRs)**, mandated by legislation passed in **2016**, which came into effect in **2023**.  
  - A **clear spike in cyber-attacks on the healthcare industry** was observed in 2023.  

- **Decade-long Observations**:  
  - Over the entire decade, **public administration** experienced the **highest number of cyber-attacks**.  
  - However, when considering **only exploitative attacks** or **attacks with financial motives**, **healthcare had the greatest number of cyber-attacks**.  

- **Reasons for Healthcare's Vulnerability**:  
  - **Large concentration of personal data**.  
  - **Frequent access by numerous individuals**, increasing exposure.  
  - **Potentially outdated systems**, making it easier for attackers to exploit.  

- **Comparison with Public Administration**:  
  - **Public administration had more total cyber-attacks** due to a **large number of politically motivated disruptive attacks**.  

- **Key Research Insights**:  
  - This research identifies **the industry with the greatest number of cyber-attacks** based on **criminological and economic factors**, unlike prior studies in the literature.  
  - **Politically motivated disruptive attacks** led to **public administration having the highest number of cyber-attacks**.  
  - **Financially motivated attacks** resulted in a **large number of attacks on the healthcare industry**.  

- **Economic and Political Influences on Cyber-Attacks**:  
  - **GDP Factor**:  
    - Countries with **higher economic resources** experience **more frequent attacks**.  
    - Attackers see these countries as having **greater financial rewards** and **higher global influence**, making them prime targets for **both financial and political attacks**.  
  - **Gini Coefficient Factor**:  
    - Countries with **less inequality** (higher prosperity) face **more cyber-attacks**, as they offer **greater economic opportunities to exploit**.  

- **Predictability of Cyber-Attacks**:  
  - **Time-series analysis** reveals **predictable trends in cyber-attacks**, which can help enhance security during high-risk periods.  

- **Practical Applications of This Research**:  
  - Helps **identify where and why cyber-attacks occur**, aiding **government policy** and **private cybersecurity efforts**.  
  - Demonstrates the **efficacy of data science in recognizing patterns** in records of social science events.  
