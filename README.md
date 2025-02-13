# Categorizing Cyber Attacks
**Analysis of Industry, Event-Type, Economic and Criminological Factors**

## What is here?  
This repository contains the majority of my data, code, and results for my project. 

## Where is this project going?  
So far: GSDSEF in the Behavioral and Social Sciences category.

## Details about my research project:

### 1. Abstract  
My research problem is to determine which industries are most affected by cyber-attacks, which types of attacks are most prevalent, and understanding potential causes for such industries being more vulnerable and attacked. Then, comparing with other industries with lower cyber events to find unique causes.

My hypothesis is that healthcare would be the victim with the greatest number of cyber-attacks, with the primary type being exploitative due to a large concentration of personal data, recurrent access to the data by numerous individuals, and potentially outdated systems.

First, I obtained data from the publicly available Center for International and Security Studies at Maryland (CISSM) website. I then performed data analysis and data visualization in Python programming using the Google Colab environment to arrive at insights and classify cyber-attacks based on underlying economic and criminological factors.

The analysis indicates that the **public administration** industry has the highest number of cyber-attacks, followed by **health care and social assistance**. This finding is close but not exactly consistent with the research hypothesis. The work then proceeded with a detailed analysis of cyber-attacks and their classification by attack type, motive, and actors, to explain the discrepancy versus the hypothesis.

From an applications perspective, such classification of attacks is expected to assist industries and governments in setting policies and implementing procedures to help safeguard against cyber-attacks. Further, such a study illustrates the efficacy of data science and data visualization in understanding social science.

### 2. Data Used  
This data science project uses data sourced from the **Center for International and Security Studies at University of Maryland (CISSM)**. The data, *Cyber Events Database*, is a record of scraped publications of cyber-attack events occurring since 2014 to 2024 with over 14,000 recorded events.  
I downloaded the cyber events dataset from this link:  
[Cyber Events Database](https://cissm.umd.edu/cyber-events-database)

I also used data from **The World Bank’s Poverty & Inequality Indicators (PIP)**, which include various economic describing variables per country, including GDP, wealth gap, Gini coefficient, etc.  
I downloaded the PIP dataset from this link:  
[Poverty & Inequality Indicators](https://pip.worldbank.org/poverty-calculator)

### 3. Discussion/Key Findings  
The **public administration** industry has the highest number of cyber-attacks, followed by **health care and social assistance**. This finding is close but not exactly consistent with the research hypothesis that healthcare would have the highest number of attacks.

The work then proceeded with a detailed analysis of cyber-attacks and their classification by attack type, motive, and actors. The findings indicate that attacks on **public administration**, and **health care & social assistance** differ in terms of these underlying factors:
- **Public administration** has approximately 20% more disruptive attacks than exploitative attacks.
- **Health care and social assistance** is dominated by exploitative attacks, which are about three times higher than disruptive attacks.
- In terms of actor type, **public administration** is attacked by criminals (56%), whereas attacks on **health care and social assistance** are dominated by criminals (96%).
- Regarding motive, **51% of attacks** on public administration had a non-financial motive, while **97%** of attacks on health care and social assistance had a financial motive.
- The **motive/actor profiles** differ between the exploitative and disruptive attack types:
  - Exploitative attacks are mostly financial (78%), with a majority of non-political criminal actors (85%).
  - Disruptive attacks have a slight majority of non-financial motives (52%), with a larger number of political actors (40%).

When considering **cyber-attacks only by non-political actors** (i.e., not by nation-states or hacktivists), **health care and social assistance** have the highest number of cyber-attacks, supporting the research hypothesis.

Additionally, countries with higher **GDP** and those with greater **equality (using Gini coefficient)** are attacked more frequently. This is because such countries have more economic goods to capture and are more likely to be targets of political actors due to their greater global influence.

Based on my **ARIMA time-series model** of the cyber-attack data, it is clear that trends in cyber-attacks are predictable. This finding could be used to enhance security during periods of increased vulnerability.

### 4. Conclusion  
My hypothesis that healthcare would be the victim with the greatest number of cyber-attacks was not entirely accurate. However, when considering only exploitative attacks or those with financial motives, healthcare has the greatest number of cyber-attacks. This is due to the large concentration of personal data, recurrent access to the data by numerous individuals, and potentially outdated systems.

The only industry that surpassed health care in the number of cyber-attacks was **public administration** due to a large number of politically motivated disruptive attacks.

This research identifies the industry with the greatest number of cyber-attacks and criminological and economic factors, unlike prior studies found in my literature review:
- Politically motivated disruptive attacks resulted in **public administration** having the greatest number of cyber-attacks.
- Financially motivated attacks resulted in a large number of attacks on the **health care industry**.
- Using **GDP**, countries with higher economic resources are attacked more frequently, as attackers see a greater reward and are more likely to be politically targeted.
- Using **Gini coefficient**, countries with less inequality are attacked more frequently, as those countries generally have greater overall prosperity to exploit.

My **time-series analysis** finds that there are predictable trends in cyber-attacks that can help enhance security at high-risk moments.

Application-wise, my research can help identify where and why cyber-attacks occur, allowing government policy and private cybersecurity efforts to focus on solving the problems where they exist.

Also, my work demonstrates the efficacy of using **data science** to recognize patterns in records of social science events.
