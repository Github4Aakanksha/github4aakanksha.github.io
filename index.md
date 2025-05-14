<div style="display: flex; align-items: center;">
    <h1 style="color: #2774ae ; margin-right: 10px;">DATA SCIENCE PROJECTS</h1>
</div>

<div style="background-color: #fff ; padding: 20px; border-radius: 8px; margin-bottom: 30px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
  <h3 style='color:#222;'>Monetary Policy Impact Analysis: SQL-Driven Sector Performance Evaluation</h3>
<em><strong>Business Problem:</strong> How does an expansionary monetary policy (interest rate cuts) affect different economic sectors, and can we quantify its asymmetric impact?</em>
 <br><br>
  <div style="text-align: justify;color: #727272;">
  
  For the Central Bank of Gondwana, I analyzed whether their 2023–2024 rate cuts boosted manufacturing sector returns while inadvertently harming financial firms—a critical question for future policy design. Using SQL-based time-series analysis, I evaluated the impact of Gondwana’s monetary policy across key sectors. By segmenting data into Pre-Policy, During-Policy, and Post-Policy periods, I identified:

<li><strong>38% surge in manufacturing returns</strong> during the rate cuts, sustained at <strong>6% above pre-policy levels</strong></li>
<li><strong>Declining financial sector performance</strong> due to compressed bank profit margins from lower interest rates</li>
<li><strong>Validated policy timing</strong> through inflation/interest rate trends using moving averages (2-week to 6-month windows)</li>


The analysis combined 280K+ corporate records with macroeconomic indicators to isolate sector-specific effects, leveraging:
    <li>SQL window functions</li>
    <li>Multi-table joins</li> 
    <li>Dynamic aggregations</li>
  </div>

  <div style="text-align: center;">
      <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" title="Advanced SQL Analytics"/>
    <img src="https://img.shields.io/badge/Time_Series_Analysis-6f42c1?style=for-the-badge&logo=grafana&logoColor=white" alt="Time Series" title="Time Series Analysis"/>
    <img src="https://img.shields.io/badge/Data_Visualization-FF6F00?style=for-the-badge&logo=tableau&logoColor=white" alt="Data Viz" title="Data Visualization"/>
    <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white" alt="Snowflake" title="Snowflake"/>
  </div>

  <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
    <div style="width: 45%; padding-right: 10px;">
      <p><strong>Figure 1:</strong> Macro Economic Indicator </p>
      <img src="images/Inflation Trend (Moving Averages).png" alt="Macro Economic Indicator" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 50%; padding-right: 10px;">
      <p><strong>Figure 2:</strong> Pre-During-Post Analysis </p>
      <img src="images/Pre-Post Table.png" alt="Pre-During-Post Analysis" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 30%; padding-right: 10px;">
      <p><strong>Figure 3:</strong>Correlation: Daily Sector Returns & Interest Rate</p>
      <img src="images/Corr.png" alt="Daily Sector Returns & Interest Rate Correlation" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 30%; padding-right: 10px;">
      <p><strong>Figure 4:</strong> Daily Avg Manufacturing Returns </p>
      <img src="images/Daily Avg Manufacturing Returns.png" alt="Daily Avg Manufacturing Returns" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 30%; padding-right: 10px;">
      <p><strong>Figure 5:</strong> Interest rate Vs Daily Avg Return </p>
      <img src="images/Interest rate Vs Daily Avg Return.png" alt="Interest rate Vs Daily Avg Return" style="width: 100%; height: auto;"/>
    </div>
  </div>
</div>

<div style="background-color: #fff ; padding: 20px; border-radius: 8px; margin-bottom: 30px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
  <h3 style='color: #222 ;'>SumZero Investment Thesis Driven Trading Strategy</h3>
  <em><strong>Business Problem:</strong> How can we make sense of text-based investment ideas on our website to create trading strategies and improve stock market returns?</em>
 <br><br>
  <div style="text-align: justify;color: #727272;">
  At SumZero, Inc., I led a team to develop a trading strategy by integrating NLP and ChatGPT with S&P 500 stock price data from Yahoo Finance. I analyzed over 1,000 investment theses from SumZero using OpenAI’s API, achieving a sentiment analysis accuracy of 95.51%. By assigning trading signals (1 for bullish, -1 for bearish, 0 for neutral) and incorporating a stop-loss mechanism, our strategy delivered strong performance metrics, including a high Profit/Max Equity ratio and a positive Sharpe Ratio. We also explored the extraction of non-GAAP metrics for further analysis.
  </div>

  <div style="text-align: center;">
  <img src="https://img.shields.io/badge/OpenAI_API-3776AB?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI API" title="OpenAI API"/>
  <img src="https://img.shields.io/badge/Stop_Loss_Mechanism-a77dbd?style=for-the-badge&logo=datadog&logoColor=white" alt="Stop Loss Mechanism" title="Stop Loss Mechanism"/>
  <img src="https://img.shields.io/badge/Sharpe_Ratio-3776AB?style=for-the-badge&logo=chartdotjs&logoColor=white" alt="Sharpe Ratio" title="Sharpe Ratio"/>
  <img src="https://img.shields.io/badge/GAAP_Metrics-a77dbd?style=for-the-badge&logo=python&logoColor=white" alt="GAAP metrics" title="GAAP Metrics"/>
</div>

  <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: nowrap;">
    <div style="width: 30%; padding-left: 10px; padding-right: 10px;">
      <p><strong>Figure 1:</strong> Sumzero Sentiment Accuracy</p>
      <img src="images/Sumzero sentiment accuracy.png" alt="Sumzero Sentiment Accuracy" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 30%; padding-left: 10px;">
      <p><strong>Figure 2:</strong> Mean Annualized Returns</p>
      <img src="images/Mean Annualized Returns.png" alt="TMean Annualized Returns" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 30%; padding-left: 10px;">
        <p><strong>Figure 3:</strong> Cumulative Profit</p>
        <img src="images/Profit.png" alt="Cumulative Profit" style="width: 100%; height: auto;"/>
    </div>
  </div>
</div>


<div style="background-color: #fff ; padding: 20px; border-radius: 8px; margin-bottom: 30px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
  <h3 style='color:#222;'>Seismic Insights: Real-Time Earthquake Tracking with Google Cloud</h3>
<em><strong>Business Problem:</strong> How can we automate real-time earthquake tracking and present the updates in a simple, user-friendly way for everyone?</em>
 <br><br>
  <div style="text-align: justify;color: #727272;">
  
  I developed a solution to automate the collection and organization of real-time earthquake data from the Southern California Earthquake Data Center (SCEDC) using Google Cloud. I created a Python-based Google Cloud Function that retrieves critical earthquake details—magnitude, location, depth, and timestamp—and updates a Google Sheet in real time, ensuring seamless data synchronization without manual intervention. To make the process even more user-friendly, I built an optional Flask app that provides a simple interface to trigger updates and visualize the data. By integrating tools like gspread and oauth2client, this scalable, cloud-powered project makes tracking seismic activity accessible for both technical users and the general public.
  </div>

  <div style="text-align: center;">
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" alt="Google Cloud" title="Google Cloud"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" title="Flask"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" title="Python"/>
  <img src="https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white" alt="Google Sheets" title="Google Sheets"/>
</div>


 <a href="https://github.com/Github4Aakanksha/Real-Time-Earthquake-Tracking"
     style="
       display: inline-block;
       padding: 10px 20px;
       background-color:#003B5C;
       color: white;
       text-decoration: none;
       border-radius: 10px; /* Curved edges */
       font-size: 0.9em;
       font-family: Arial, sans-serif;
       box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2); /* Optional shadow for button effect */
     ">View project on GitHub</a>

  <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
    <div style="width: 35%; padding-right: 10px;">
      <p><strong>Figure 1:</strong> SCEDC Earthquake Map</p>
      <img src="images/Earthquake Map From SCEDC.gif" alt="SCEDC Earthquake Map" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 60%; padding-right: 10px;">
      <p><strong>Figure 2:</strong> Earthquake Table SCEDC</p>
      <img src="images/Earthquake Table SCEDC.png" alt="Earthquake Table SCEDC" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 100%; padding-right: 10px;">
      <p><strong>Figure 3:</strong> Updated Google Sheets</p>
      <img src="images/CC Final.png" alt="Updated Google Sheets" style="width: 100%; height: auto;"/>
    </div>
  </div>
</div>


<div style="background-color: #fff ; padding: 20px; border-radius: 8px; margin-bottom: 30px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
  <h3 style='color:#222;'>Sectoral PE Analysis & Trading Strategy with Machine Learning</h3>
<em><strong>Business Problem:</strong> How can we use price-to-earnings ratios from different sectors to create a balanced portfolio that improves investment decisions, trading results, and reduces risk?</em>
  <br><br>
  <div style="text-align: justify;  color: #727272;">
  I developed a trading strategy using machine learning based on sectoral price-to-earnings (PE) ratios from the health and industrial sectors. By normalizing the data with Fisher transformations and fine-tuning buy/sell signals, I evaluated the strategy using metrics such as the Sharpe ratio and annual returns. When I combined the best strategies from both the health and industrial sectors into one equally-balanced portfolio, it showed that using data-driven methods can lead to better investment decisions and improved trading results.
  </div>
  
  <div style="text-align: center;">
  <img src="https://img.shields.io/badge/Machine_Learning-F7931E?style=for-the-badge&logo=expertai&logoColor=white" alt="Machine Learning" title="Machine Learning"/>
  <img src="https://img.shields.io/badge/Data_Analysis-4CAF50?style=for-the-badge&logo=databricks&logoColor=white" alt="Data Analysis" title="Data Analysis"/>
  <img src="https://img.shields.io/badge/Financial_Modeling-0A66C2?style=for-the-badge&logo=leetcode&logoColor=white" alt="Financial Modeling" title="Financial Modeling"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" title="Python"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas" title="Pandas"/>
</div>
  
  <a href="https://github.com/Github4Aakanksha/ML/blob/main/Sectoral%20PE%20Analysis%20and%20Trading%20Strategy%20ML.ipynb" style="
       display: inline-block;
       padding: 10px 20px;
       background-color:#003B5C;
       color: white;
       text-decoration: none;
       border-radius: 10px; /* Curved edges */
       font-size: 0.9em;
       font-family: Arial, sans-serif;
       box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2); /* Optional shadow for button effect */
     ">View project on GitHub</a>

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
</div>


<div style="background-color: #fff ; padding: 20px; border-radius: 8px; margin-bottom: 30px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
  <h3 style='color: #222;'>Flask Application- Instagram Caption Analysis</h3>
  <em><strong>Business Problem:</strong> How can we help content creators improve their social media posts?</em>
  <br><br>
  <div style="text-align: justify; color: #727272; ">
At Next Step Projects,  I led the development of a Flask application that analyzes Instagram captions for sentiment and extracts hashtags. The application takes an Instagram caption as input and provides the sentiment polarity, subjectivity, and any hashtags present in the caption. My goal was to develop a tool that helps content creators understand the emotional tone of their captions and identify popular hashtags, ultimately enabling them to craft more engaging and impactful posts on Instagram.
  </div>

<div style="text-align: center;">
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" alt="Google Cloud" title="Google Cloud"/>
  <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask" title="Flask"/>
  <img src="https://img.shields.io/badge/Instaloader-8A3AB9?style=for-the-badge&logo=instagram&logoColor=white" alt="Instaloader" title="Instaloader"/>
  <img src="https://img.shields.io/badge/VADER_Analysis-4CAF50?style=for-the-badge&logo=codeforces&logoColor=white" alt="VADER Sentiment" title="VADER Sentiment Analysis"/>
</div>


  <a href="https://github.com/your-repo-link" style="
       display: inline-block;
       padding: 10px 20px;
       background-color:#003B5C;
       color: white;
       text-decoration: none;
       border-radius: 10px; /* Curved edges */
       font-size: 0.9em;
       font-family: Arial, sans-serif;
       box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2); /* Optional shadow for button effect */
     ">View project on GitHub</a>

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
</div>


<div style="background-color: #fff ; padding: 20px; border-radius: 8px; margin-bottom: 30px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
  <h3 style='color: #222;'>Sentiment Analysis- Forex Trading Strategy</h3>
  <em><strong>Business Problem:</strong> How can we leverage economic news sentiment to create a Forex trading strategy that consistently outperforms the market standards?</em>
  <br><br>
  <div style="text-align: justify; color: #727272; ">
In this project, I used the NY Times API to extract economic news articles and headlines, focusing on content mentioning the British Pound, and then analyzed the text to uncover sentiment trends and patterns that could influence Forex trading decisions. I developed a Forex trading strategy to predict GBP/USD exchange rate movements using NLP and machine learning. I conducted sentiment analysis on economic news extracted via the NY Times API from 2003 to 2024 and created two strategies: Strategy A, which generates trading signals through NLP-based sentiment analysis, and Strategy B, which employs predictive analytics for market trend forecasting. I rigorously optimized both strategies through backtesting and hyperparameter tuning, achieving a 1.4% annualized return and outperforming the HFRI Currency Index.
  </div>

<div style="text-align: center;">
  <img src="https://img.shields.io/badge/Regex-FF9800?style=for-the-badge&logo=git&logoColor=white" alt="Regex" title="Regex"/>
  <img src="https://img.shields.io/badge/TextBlob-9C27B0?style=for-the-badge&logo=python&logoColor=white" alt="TextBlob" title="TextBlob"/>
  <img src="https://img.shields.io/badge/NLP-3F51B5?style=for-the-badge&logo=openai&logoColor=white" alt="Natural Language Processing" title="Natural Language Processing"/>
  <img src="https://img.shields.io/badge/Machine_Learning-4CAF50?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Machine Learning" title="Machine Learning"/>
</div>

  <a href="https://github.com/athk13/FX-Sentiment-Analysis-Trading-Strategy" style="
       display: inline-block;
       padding: 10px 20px;
       background-color:#003B5C;
       color: white;
       text-decoration: none;
       border-radius: 10px; /* Curved edges */
       font-size: 0.9em;
       font-family: Arial, sans-serif;
       box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2); /* Optional shadow for button effect */
     ">View project on GitHub</a>

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
</div>


<div style="background-color: #fff ; padding: 20px; border-radius: 8px; margin-bottom: 30px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
  <h3 style='color: #222;'>Web Scraping Project- Faculty Information from IIM Ahmedabad</h3>
  <em><strong>Business Problem:</strong> How can we automate the extraction of detailed faculty information from dynamic websites for efficient data analysis and research? </em>
  <br><br>
  <div style="text-align: justify; color: #727272; ">
To streamline the process of gathering faculty information for research or organizational needs, I developed a web scraping tool using Selenium, Regex, and BeautifulSoup to extract faculty information from the dynamic IIM Ahmedabad website. The script automates the process of navigating the site, interacting with various elements, and extracting relevant data such as faculty names, professions, areas of expertise, educational qualifications, and research areas from individual profile cards. It efficiently handles multiple pages by clicking through to next pages until all faculty profiles are scraped, ultimately storing the data in a Pandas DataFrame for further analysis.
  </div>

<div style="text-align: center;">
  <img src="https://img.shields.io/badge/Regex-FF5722?style=for-the-badge&logo=git&logoColor=white" alt="Regex" title="Regex"/>
  <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium" title="Selenium"/>
  <img src="https://img.shields.io/badge/BeautifulSoup-964B00?style=for-the-badge&logo=python&logoColor=white" alt="BeautifulSoup" title="BeautifulSoup"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" title="Python"/>
</div>

  <a href="https://github.com/Github4Aakanksha/ML/blob/main/Webscraping%20Assessment.ipynb" style="
       display: inline-block;
       padding: 10px 20px;
       background-color:#003B5C;
       color: white;
       text-decoration: none;
       border-radius: 10px; /* Curved edges */
       font-size: 0.9em;
       font-family: Arial, sans-serif;
       box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2); /* Optional shadow for button effect */
     ">View project on GitHub</a>

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
</div>


<div style="background-color: #fff ; padding: 20px; border-radius: 8px; margin-bottom: 30px; box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);">
  <h3 style='color: #222;'>Macroeconomic Time Series Analysis using VAR Models</h3>
  <em><strong>Research Problem:</strong> How do key economic indicators like inflation, unemployment, and the Federal Funds rate interact and influence each other over time, and how can these relationships be used for forecasting? </em>
  <br><br>
  <div style="text-align: justify; color: #727272; ">
In this project, I conducted time series analysis using Vector Auto-regression (VAR) models to replicate the findings of Stock and Watson’s 2001 paper. By analyzing key economic indicators like Inflation, Unemployment, and the Federal Funds Rate, I use tools like PACF plots, Granger Causality tests, and Factor Error Variance Decomposition (FEVD) to understand their interrelationships. These included exploring the direction of influence between them and understanding the contributions of each variable to forecast error variance. I also conducted impulse response analysis to evaluate the short-term impact of shocks to the system. The models forecast these indicators two years forward, providing insights into how economic factors influence each other and enhancing the accuracy of macroeconomic forecasting and policy analysis.
  </div>

<div style="text-align: center;">
  <img src="https://img.shields.io/badge/VAR_Models-4A90E2?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="VAR Models" title="VAR Models"/>
  <img src="https://img.shields.io/badge/Granger_Causality_Test-9C27B0?style=for-the-badge&logo=python&logoColor=white" alt="Granger Causality Test" title="Granger Causality Test"/>
  <img src="https://img.shields.io/badge/PACF_Plots-00BCD4?style=for-the-badge&logo=chartdotjs&logoColor=white" alt="PACF Plots" title="PACF Plots"/>
  <img src="https://img.shields.io/badge/Factor_Error_Variance_Decomposition-F57C00?style=for-the-badge&logo=databricks&logoColor=white" alt="Factor Error Variance Decomposition" title="Factor Error Variance Decomposition"/>
</div>

  

  <a href="https://github.com/Github4Aakanksha/ML/blob/main/Time%20Series%20VAR%20Forecasting.ipynb" style="
       display: inline-block;
       padding: 10px 20px;
       background-color:#003B5C;
       color: white;
       text-decoration: none;
       border-radius: 10px; /* Curved edges */
       font-size: 0.9em;
       font-family: Arial, sans-serif;
       box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2); /* Optional shadow for button effect */
     ">View project on GitHub</a>

  <div style="display: flex; justify-content: space-between; align-items: flex-start; flex-wrap: wrap;">
    <div style="width: 45%; padding-right: 10px;">
      <p><strong>Figure 1:</strong> Impulse Response Plots</p>
      <img src="images/Impulse Response Plot.png?raw=true" alt="Impulse Response Plots" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 45%; padding-right: 10px;">
      <p><strong>Figure 2:</strong> PI Forecast Plot</p>
      <img src="images/PI Forecast Plot.png?raw=true" alt="PI Forecast Plot" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 45%; padding-right: 10px;">
      <p><strong>Figure 3:</strong> Inflation Forecast Plot</p>
      <img src="images/Inflation Forecast Plot.png?raw=true" alt="Inflation Forecast Plot" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 45%; padding-right: 10px;">
      <p><strong>Figure 4:</strong> Unemployment Forecast Plot</p>
      <img src="images/unemployment forecast plot.png?raw=true" alt="Unemployment Forecast Plot" style="width: 100%; height: auto;"/>
    </div>
  </div>
</div>




<style>
  body {
    font-family: 'Noto Sans', sans-serif;
  }
  /* Font style for headings */
  h1, h2, h3, h4, h5, h6 {
    font-family: \"La Gagliane\", sans-serif;
  }
</style>
