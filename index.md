## Data Science Projects

---
### SumZero Investment Thesis Driven Trading Strategy

At SumZero, Inc., I led a team to develop a trading strategy by integrating NLP and ChatGPT with S&P 500 stock price data from Yahoo Finance. We analyzed over 1,000 investment theses from SumZero using OpenAI’s API, achieving a sentiment analysis accuracy of 95.51%. By assigning trading signals (1 for bullish, -1 for bearish, 0 for neutral) and incorporating a stop-loss mechanism, our strategy delivered strong performance metrics, including a high Profit/Max Equity ratio and a positive Sharpe Ratio. We also explored the extraction of non-GAAP metrics for further analysis.

![OpenAI API](https://img.shields.io/badge/OpenAI_API-lightgrey?style=flat-square&logo=openai)
![Stop Loss Mechanism](https://img.shields.io/badge/Stop_Loss_Mechanism-lightgrey?style=flat-square)
![Sharpe Ratio](https://img.shields.io/badge/Sharpe_Ratio-lightgrey?style=flat-square)
![GAAP metrics](https://img.shields.io/badge/GAAP_metrics-lightgrey?style=flat-square&logo=python)

<div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: nowrap;">
  <div style="width: 30%; padding-right: 10px;">
    <p><strong>Figure 1:</strong> Investment Timeline</p>
    <img src="images/Timeline.png" alt="Investment Timeline" style="width: 100%; height: auto;"/>
  </div>
  <div style="width: 30%; padding-left: 10px; padding-right: 10px;">
    <p><strong>Figure 2:</strong> Sumzero Sentiment Accuracy</p>
    <img src="images/Sumzero sentiment accuracy.png" alt="Sumzero Sentiment Accuracy" style="width: 100%; height: auto;"/>
  </div>
  <div style="width: 30%; padding-left: 10px;">
    <p><strong>Figure 3:</strong> Mean Annualized Returns</p>
    <img src="images/Mean Annualized Returns.png" alt="TMean Annualized Returns" style="width: 100%; height: auto;"/>
  </div>
</div>
<div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: nowrap;">
  <div style="width: 45%; padding-left: 10px;">
    <p><strong>Figure 4:</strong> Top Performing Stocks</p>
    <img src="images/Top Stocks.png" alt="Top Performing Stocks" style="width: 100%; height: auto;"/>
  </div><div style="width: 45%; padding-left: 10px;">
    <p><strong>Figure 5:</strong> Cummulative Profit</p>
    <img src="images/Profit.png" alt="Cummulative Profit" style="width: 100%; height: auto;"/>
  </div>
</div>

---

### Seismic Insights: Real-Time Earthquake Tracking with Google Cloud
This project automates the collection and organization of real-time earthquake data from the Southern California Earthquake Data Center (SCEDC) using Google Cloud. A Python-based Google Cloud Function retrieves critical earthquake details—magnitude, location, depth, and timestamp—and updates a Google Sheet for seamless, real-time data synchronization. Users can easily append or replace data without manual intervention. An optional Flask app provides a simple interface to trigger updates and visualize the data. With the integration of gspread and oauth2client, this scalable, cloud-powered solution makes seismic activity accessible to both technical users and the general public.

![Google Cloud](https://img.shields.io/badge/Google_Cloud-lightgrey?style=flat-square&logo=google-cloud)
![Flask](https://img.shields.io/badge/Flask-lightgrey?style=flat-square&logo=flask)

<div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
  <div style="width: 45%; padding-right: 10px;">
    <p><strong>Figure 1:</strong> SCEDC Earthquake Map</p>
    <img src="images/Earthquake Map From SCEDC.gif" alt="SCEDC Earthquake Map" style="width: 100%; height: auto;"/>
  </div>
  <div style="width: 45%; padding-right: 10px;">
    <p><strong>Figure 2:</strong> Earthquake Table SCEDC</p>
    <img src="images/Earthquake Table SCEDC.png" alt="Earthquake Table SCEDC" style="width: 100%; height: auto;"/>
  </div>
</div>

<a href="https://github.com/your-repo-link" style="color:#6a0dad;">View project on GitHub</a>

---

### Sectoral PE Analysis & Trading Strategy with Machine Learning
This project developed a trading strategy using machine learning based on sectoral price-to-earnings (PE) ratios from the health and industrial sectors. By normalizing data with Fisher transformations and fine-tuning buy/sell signals, the strategy was evaluated using metrics like the Sharpe ratio and annual returns. Combining the top-performing strategies from both sectors into an equally weighted portfolio showed the effectiveness of data-driven techniques for improving financial decision-making and trading performance.

![Machine Learning](https://img.shields.io/badge/Machine_Learning-lightgrey?style=flat-square)
![Data Analysis](https://img.shields.io/badge/Data_Analysis-lightgrey?style=flat-square)
![Financial Modeling](https://img.shields.io/badge/Financial_Modeling-lightgrey?style=flat-square)
![Python](https://img.shields.io/badge/Python-lightgrey?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-lightgrey?style=flat-square&logo=pandas)

<a href="https://github.com/Github4Aakanksha/ML/blob/main/Sectoral%20PE%20Analysis%20and%20Trading%20Strategy%20ML.ipynb" style="color:#6a0dad;">View project on GitHub</a>

<div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
  <div style="width: 45%; padding-right: 10px;">
    <p><strong>Figure 1:</strong> Health Sector Trading Strategy</p>
    <img src="images/portfolio1.png?raw=true" alt="Health Sector Trading Strategy" style="width: 100%; height: auto;"/>
  </div>
  <div style="width: 45%; padding-right: 10px;">
    <p><strong>Figure 2:</strong> Industrial Sector Trading Strategy</p>
    <img src="images/portfolio 2.png?raw=true" alt="Industrial Sector Trading Strategy" style="width: 100%; height: auto;"/>
  </div>
</div>

---

### Flask Application- Instagram Caption Analysis
This project involves creating a Flask application that analyzes Instagram captions for sentiment and extracts hashtags. The application takes an Instagram caption as input and provides the sentiment polarity, subjectivity, and any hashtags present in the caption. The primary goal is to create a tool that assists content creators in understanding the emotional tone of their captions and identifying popular hashtags, ultimately helping them craft more engaging and impactful posts on Instagram.

![Google Cloud](https://img.shields.io/badge/Google_Cloud-lightgrey?style=flat-square&logo=google-cloud)
![Flask](https://img.shields.io/badge/Flask-lightgrey?style=flat-square&logo=flask)
![Instaloader](https://img.shields.io/badge/Instaloader-lightgrey?style=flat-square)
![VADER](https://img.shields.io/badge/VADER-lightgrey?style=flat-square)

<div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: nowrap;">
  <div style="width: 45%; padding-right: 10px;">
    <p><strong>Figure 1:</strong> Sentiment Polarity</p>
    <img src="images/Sentiment polarity.png" alt="Sentiment Polarity" style="width: 100%; height: auto;"/>
  </div>
  <div style="width: 45%; padding-left: 10px; padding-right: 10px;">
    <p><strong>Figure 2:</strong> Top 10 Hashtags</p>
    <img src="images/Hashtags.png" alt="Top 10 Hashtags" style="width: 100%; height: auto;"/>
  </div>
</div>

---

### Sentiment Analysis- Forex Trading Strategy
This project involves developing a Forex trading strategy to predict GBP/USD exchange rate movements using NLP and machine learning. By conducting sentiment analysis on economic news extracted via the NY Times API from 2003 to 2024, we created two strategies: Strategy A generates trading signals through NLP-based sentiment analysis, while Strategy B employs predictive analytics for market trend forecasting. Both strategies were rigorously optimized through backtesting and hyperparameter tuning, achieving a 1.4% annualized return and outperforming the HFRI Currency Index. 

![Regex](https://img.shields.io/badge/Regex-lightgrey?style=flat-square)
![TextBlob](https://img.shields.io/badge/TextBlob-lightgrey?style=flat-square)
![NLP](https://img.shields.io/badge/NLP-lightgrey?style=flat-square)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-lightgrey?style=flat-square)

<a href="https://github.com/athk13/FX-Sentiment-Analysis-Trading-Strategy" style="color:#6a0dad;">View project on GitHub</a>

<div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: nowrap;">
  <div style="width: 30%; padding-right: 10px;">
    <p><strong>Figure 1:</strong> Trading Signal Chart</p>
    <img src="images/Screenshot%202024-04-16%20122044.png" alt="Trading Signal Chart" style="width: 100%; height: auto;"/>
  </div>
  <div style="width: 30%; padding-left: 10px; padding-right: 10px;">
    <p><strong>Figure 2:</strong> Strategy Equity Curve</p>
    <img src="images/Screenshot%202024-04-16%20122058.png" alt="Equity Curve" style="width: 100%; height: auto;"/>
  </div>
  <div style="width: 30%; padding-left: 10px;">
    <p><strong>Figure 3:</strong> Hyperparameter Optimization Heatmap</p>
    <img src="images/hyperparameter-heatmap.png" alt="Hyperparameter Optimization Heatmap" style="width: 100%; height: auto;"/>
  </div>
</div>

---

### Web Scraping Project- Faculty Information from IIM Ahmedabad
In this project, I developed a web scraping tool using Selenium, Regex, and BeautifulSoup to extract faculty information from the dynamic IIM Ahmedabad website. The script automates the process of navigating the site, interacting with various elements, and extracting relevant data such as faculty names, professions, areas of expertise, educational qualifications, and research areas from individual profile cards. It efficiently handles multiple pages by clicking through to next pages until all faculty profiles are scraped, ultimately storing the data in a Pandas DataFrame for further analysis.

![Selenium](https://img.shields.io/badge/Selenium-lightgrey?style=flat-square&logo=selenium)
![Regex](https://img.shields.io/badge/Regex-lightgrey?style=flat-square)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-lightgrey?style=flat-square)
![Python](https://img.shields.io/badge/Python-lightgrey?style=flat-square)

<div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
  <div style="width: 45%; padding-right: 10px;">
    <p><strong>Figure 1:</strong> IIMA Homepage</p>
    <img src="images/IIMA Webscrape.png?raw=true" alt="IIMA Homepage" style="width: 100%; height: auto;"/>
  </div>
  <div style="width: 45%; padding-right: 10px;">
    <p><strong>Figure 2:</strong> IIMA Faculty Page</p>
    <img src="images/IIMA Faculty page.png?raw=true" alt="IIMA Faculty Page" style="width: 100%; height: auto;"/>
  </div>
</div>

<a href="https://github.com/Github4Aakanksha/ML/blob/main/Webscraping%20Assessment.ipynb" style="color:#6a0dad;">View project on GitHub</a>

---

## Consulting Projects

**M&A Prospecting and Analysis:**
- Employed Finviz and scraping tools for thorough financial research, pinpointing prospective companies for mergers and acquisitions
- Performed risk assessment, competitor and SWOT analysis, for selected companies, offering an overview of their financial landscape
- Identified high debt and insider trading, in an energy industry company, favoring mergers and acquisitions despite financial risks
  
**Accenture Strategy Consulting Virtual Internship:**
- Led the redesign of a fictional grant program website, focusing on improving User Experience (UX) to deliver client solutions
- Applied the "Ease vs. Impact" matrix as an innovative approach to prioritize tasks
- Leveraged data through Excel, extracting performance insights to provide recommendations on budget-aligned initiatives


---




---

