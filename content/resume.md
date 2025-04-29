---
title: "Resume"
# description: "Peter Jiang's Resume"
---

<iframe src="/resume.pdf" width="100%" height="800px">
  <p>Your browser does not support iframes. Please <a href="/resume.pdf">download the PDF</a> instead.</p>
</iframe>

## Contact

**Email:** i@peterjiang.me

**Phone:** +1 (323) 301-3957

**LinkedIn:** [linkedin.com/in/PeterJiangSDE](https://www.linkedin.com/in/PeterJiangSDE)

**Website:** [https://peterjiang.me](https://www.peterjiang.me)

## Education \& Awards

**Rutgers University, New Brunswick, NJ, USA**

*Master of Science in Electrical and Computer Engineering*

Concentration: Computer Engineering
GPA: 3.9
Sep 2015 – Jan 2018

**South China University of Technology (SCUT), Guangzhou, China**

*Bachelor of Science in Engineering*

Award: Third-class Scholarship of SCUT (2013-2014)
Sep 2011 – July 2015

---

## Experience

### Amazon, Seattle, WA

**Software Developer**
Jan 2020 – Present

- Tech lead of a team of 7; launched a critical component of Amazon’s first digital banking product for emerging markets.
    - Designed and delivered 20+ back-end APIs to support in-house banking needs, including full-fledged banking features.
    - Designed and implemented a microservice providing Banking-as-a-Service to internal Amazon clients, seamlessly integrated with existing platforms.
    - Expected to have a US\$500MM business impact in the first launched marketplace.
- Delivered a critical component for external payment processing partners' outage system.
    - Minimized order loss during partner outages, covering 100+ partner integrations.
    - Detected hundreds to several thousand (6,000+) actionable outages monthly.
    - Reduced outage detection time from up to 30 minutes to 5 minutes, increasing system resiliency.
    - Co-authored and filed a US patent.
- Achieved Indian Payment Aggregators and Payment Gateways (PAPG) regulation and data localization compliance.
    - Designed data distribution and localization mechanisms to securely handle regulated data.
    - Decoupled data between Payment Aggregators and Gateways to comply with regulations.
- Implemented an upfront charge mechanism to reduce friction from Europe PSD2 regulation for pre-sale orders.
    - Handled an average of 250k charges daily, with peaks over 500k.
    - Reduced potential loss due to friction in re-authentication, saving millions of euros per day.

---

### Susquehanna International Group (SIG), Philadelphia, PA

**Software Developer**
Feb 2018 – Dec 2019

- Designed and implemented an ultra-low latency C++ gateway (~30% faster than industry average by median latency), handling millions of orders without performance compromise.
- Developed message validation software capable of 30+ sophisticated checks on ~100 million messages/hour, optimized to use only a few GBs of memory (vs. 30–40 GBs and 12+ hours for similar systems).
- Improved multiple components for flexible field handling, simplifying logic for six upstream teams.
- Developed functional and performance testing tools for team and infrastructure health checks, including black box testing.

**Software Developer Intern**
Jun 2017 – Aug 2017

- Optimized a latency analysis system, reducing analysis time from 4–8 hours to 0.6–1.5 hours.
- Improved a core order routing C++ system (handling ~20 million orders/day) by adding mapping logic, removing the need for upstream team changes.
- Developed a NYSE Pillar database validation system in Python to cross-check internal and NYSE databases.
- Profiled core order routing system performance using perf, FlameGraph, and Python; identified and resolved a bottleneck, reducing overall latency by 15%.

---

## Research Experience

**Stock Price Trends Predicting System Based on NLP Sentiment Analysis**
Rutgers University, Jan 2017 – May 2017

- Preprocessed text from Twitter and Stocktwits using NLTK in Python (removing hyperlinks, citations, tickers, stop words, numbers; tokenized sentences).
- Extracted features with bag-of-words and word2vec; trained SGD and ANN models for binary sentiment prediction.
- Trained SVC, GaussianNB, and SGD classifiers for stock price trend prediction.
    - Achieved 0.73 accuracy for sentiment prediction; best accuracy of 0.67 for one-month stock close price trend prediction.
- Led a team of five in designing a stock tracking and prediction system.
- Implemented Bayes, SVM, ANN-based algorithms, and RSI, EMA prediction indicators.

---

## Skills

- **Programming Languages:** Java, C/C++, Python, PHP, JavaScript, Assembly Language, CSS, MySQL, ISPC, CUDA
- **Technologies:** AWS, Android