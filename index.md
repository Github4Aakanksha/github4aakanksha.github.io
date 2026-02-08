<div style="display: flex; align-items: center;">
    <h1 style="color: #2774ae ; margin-right: 10px;">DATA SCIENCE PROJECTS</h1>
</div>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #fffbf0;
        background-color: #640D14; 
    ">
    Reproducing MIT’s Winning Solution to the Amazon Last-Mile Routing Challenge
  </summary>
    
<div style="padding: 20px; color: #222; text-align: justify;">
<em><strong>Business Problem:</strong> How can we accurately predict and optimize last-mile delivery routes by combining real driver behavior patterns with route optimization algorithms?</em>
 <br><br>
  <div style="text-align: justify;color:  #222;">
  Last-mile delivery is one of the most expensive and operationally complex challenges in logistics. This project reproduces and evaluates a top-performing solution from the Amazon Last Mile Routing Challenge, where researchers from MIT developed a data-driven approach to improve delivery route efficiency using real-world logistics data.

Using historical delivery sequences, I implemented a hybrid framework that predicts delivery zone transitions using probabilistic modeling and converts those predictions into optimized delivery routes using <strong>Traveling Salesman Problem (TSP)</strong> optimization. The project demonstrates how combining machine learning with classical optimization can replicate human-like routing behavior and improve delivery planning efficiency.

<li>Reproduced MIT’s Amazon Last Mile Routing solution, showing that predicting the right set of delivery stops (71% accuracy) drives more value than perfecting the order of stop sequencing (10% accuracy), enabling faster and cheaper route planning</li>
<li>Demonstrated that focusing on neighborhood-level delivery patterns can significantly improve routing efficiency while reducing computational and operational complexity</li>
</div>
<div style="text-align: center;">
  <img src="https://img.shields.io/badge/Last_Mile_Routing-4479A1?style=for-the-badge&logo=delivery&logoColor=white" alt="Last Mile Routing" title="Last-Mile Routing"/>
  <img src="https://img.shields.io/badge/Probabilistic_Modeling-FF6F00?style=for-the-badge&logo=python&logoColor=white" alt="Probabilistic Modeling" title="Probabilistic Modeling"/>
  <img src="https://img.shields.io/badge/Spatial_Hierarchies-FF2D55?style=for-the-badge&logo=mapbox&logoColor=white" alt="Spatial Hierarchies" title="Spatial Hierarchies"/>
  <img src="https://img.shields.io/badge/Traveling_Salesman_Problem-a77dbd?style=for-the-badge&logo=graph&logoColor=white" alt="Traveling Salesman Problem" title="Traveling Salesman Problem"/>
</div>

<a href="https://github.com/Github4Aakanksha/Amazon-Last-Mile-Route-Optimization"
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
    <div style="width: 45%; padding-right: 10px;">
      <p><strong>Figure 1:</strong> Model Framework from Amazon Team’s Paper </p>
      <img src="images/Screenshot 2025-05-24 183544.png" alt="Model Framework" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 50%; padding-right: 10px;">
      <p><strong>Figure 2:</strong> TSP Solution Flow Diagram </p>
      <img src="images/Screenshot 2025-06-04 024603.png" alt="TSP Solution Flow Diagram" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 45%; padding-right: 10px;">
      <p><strong>Figure 3:</strong> Route Comparison Map: Actual Vs Predicted</p>
      <img src="images/Screenshot 2025-05-24 124627.png" alt="Route Comparison Map: Actual Vs Predicted" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 45%; padding-right: 10px;">
      <p><strong>Figure 4:</strong> Illustration of the Predicted Stop Route Via TSP </p>
      <img src="images/Screenshot 2025-05-24 123800.png" alt="Illustration of the Predicted Stop Route Via TSP" style="width: 100%; height: auto;"/>
    </div>
  </div>
</div>
</details>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #222;
        background-color: #fff; 
    ">
    AI Workflow Automation with N8N
  </summary>
    
<div style="padding: 20px; color: #222; text-align: justify;">
<em><strong>Business Problem:</strong> How can AI-powered workflow automation streamline business operations by reducing manual communication, scheduling, and data management overhead while improving response speed and decision efficiency?</em>
 <br><br>
  <div style="text-align: justify;color:  #222;">
  This project showcases a collection of intelligent automation workflows built using <strong>n8n</strong> designed to streamline communication, scheduling, and data management through AI-powered agents. The workflows integrate multiple third-party platforms and leverage AI capabilities to enable natural language interaction, automated task execution, and real-time data synchronization.

<li><strong>AI Voice Agent Workflow:</strong> Processes user voice inputs and converts them into actionable workflows</li>
<li><strong>Email + Calendar Assistant:</strong> Automates email classification, response drafting, and meeting scheduling. Syncs with calendar services to automatically create or modify events. Reduces manual scheduling overhead and improves response time.</li>
<li><strong>Google Sheets Assistant:</strong> Automates data extraction, updating, and reporting within Google Sheets. New input is appended using a looping feature for sanity checks.</li>
</div>
<div style="text-align: center;">
  <img src="https://img.shields.io/badge/LLM_based_Automation-10A37F?style=for-the-badge&logo=openai&logoColor=white" alt="LLM-based Automation" title="LLM-based Automation"/>
  <img src="https://img.shields.io/badge/API_Integrations-a77dbd?style=for-the-badge&logo=fastapi&logoColor=white" alt="API Integrations" title="API Integrations"/>
  <img src="https://img.shields.io/badge/Workflow_Design-3776AB?style=for-the-badge&logo=apacheairflow&logoColor=white" alt="Workflow Design" title="Workflow Design"/>
  <img src="https://img.shields.io/badge/AI_Agents-a77dbd?style=for-the-badge&logo=openai&logoColor=white" alt="AI Agents" title="AI Agents"/>
</div>


<a href="https://github.com/Github4Aakanksha/n8n-workflows/blob/main/README.md"
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
    <div style="width: 45%; padding-right: 10px;">
      <p><strong>Figure 1:</strong> AI Voice Agent Workflow </p>
      <img src="https://raw.githubusercontent.com/Github4Aakanksha/n8n-workflows/main/n8n%20Workflow.png" alt="AI Voice Agent Workflow" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 50%; padding-right: 10px;">
      <p><strong>Figure 2:</strong> Email + Calendar Assistant Workflow </p>
      <img src="https://raw.githubusercontent.com/Github4Aakanksha/n8n-workflows/main/Email%20%2B%20Calendar%20Assistant%20Workflow.png" alt="Email + Calendar Assistant Workflow" style="width: 100%; height: auto;"/>
    </div>
    <div style="width: 45%; padding-right: 10px;">
      <p><strong>Figure 3:</strong> Google Sheets Assistant Workflow </p>
      <img src="https://raw.githubusercontent.com/Github4Aakanksha/n8n-workflows/main/Google%20Sheets%20Assistant%20Workflow.png" alt="Google Sheets Assistant Workflow" style="width: 100%; height: auto;"/>
    </div>
  </div>
</div>
</details>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #222;
        background-color: #fff; 
    ">
    Monetary Policy Impact Analysis: SQL-Driven Sector Performance Evaluation
  </summary>
    
<div style="padding: 20px; color: #222; text-align: justify;">
<em><strong>Business Problem:</strong> How does an expansionary monetary policy (interest rate cuts) affect different economic sectors, and can we quantify its asymmetric impact?</em>
 <br><br>
  <div style="text-align: justify;color:  #222;">
  
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
</details>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #222;
        background-color: #fff; 
    ">
    SumZero Investment Thesis Driven Trading Strategy
  </summary>
    
<div style="padding: 20px; color: #222; text-align: justify;">
  <em><strong>Business Problem:</strong> How can we make sense of text-based investment ideas on our website to create trading strategies and improve stock market returns?</em>
 <br><br>
  <div style="text-align: justify;color:  #222;">
  At SumZero, Inc., I led a team to develop a trading strategy by integrating NLP and ChatGPT with S&P 500 stock price data from Yahoo Finance. I analyzed over 1,000 investment theses from SumZero using OpenAI’s API, achieving a sentiment analysis accuracy of 95.51%. By assigning trading signals (1 for bullish, -1 for bearish, 0 for neutral) and incorporating a stop-loss mechanism, our strategy delivered strong performance metrics, including a high Profit/Max Equity ratio and a positive Sharpe Ratio. We also explored the extraction of non-GAAP metrics for further analysis.
  </div>

  <div style="text-align: center;">
  <img src="https://img.shields.io/badge/OpenAI_API-10A37F?style=for-the-badge&logo=openai&logoColor=white" alt="OpenAI API" title="OpenAI API"/>
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
</details>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #222;
        background-color: #fff; 
    ">
    Seismic Insights: Real-Time Earthquake Tracking with Google Cloud
  </summary>
    
<div style="padding: 20px; color: #222; text-align: justify;">
<em><strong>Business Problem:</strong> How can we automate real-time earthquake tracking and present the updates in a simple, user-friendly way for everyone?</em>
 <br><br>
  <div style="text-align: justify;color:  #222;">
  
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
</details>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #222;
        background-color: #fff; 
    ">
    Sectoral PE Analysis & Trading Strategy with Machine Learning
  </summary>
    
<div style="padding: 20px; color: #222; text-align: justify;">
<em><strong>Business Problem:</strong> How can we use price-to-earnings ratios from different sectors to create a balanced portfolio that improves investment decisions, trading results, and reduces risk?</em>
  <br><br>
  <div style="text-align: justify;  color:  #222;">
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
</details>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #222;
        background-color: #fff; 
    ">
    Flask Application- Instagram Caption Analysis
  </summary>
    
<div style="padding: 20px; color: #222; text-align: justify;">
  <em><strong>Business Problem:</strong> How can we help content creators improve their social media posts?</em>
  <br><br>
  <div style="text-align: justify; color:  #222; ">
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
</details>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #222;
        background-color: #fff; 
    ">
    Sentiment Analysis- Forex Trading Strategy
  </summary>
    
<div style="padding: 20px; color: #222; text-align: justify;">
  <em><strong>Business Problem:</strong> How can we leverage economic news sentiment to create a Forex trading strategy that consistently outperforms the market standards?</em>
  <br><br>
  <div style="text-align: justify; color:  #222; ">
In this project, I used the NY Times API to extract economic news articles and headlines, focusing on content mentioning the British Pound, and then analyzed the text to uncover sentiment trends and patterns that could influence Forex trading decisions. I developed a Forex trading strategy to predict GBP/USD exchange rate movements using NLP and machine learning. I conducted sentiment analysis on economic news extracted via the NY Times API from 2003 to 2024 and created two strategies: Strategy A, which generates trading signals through NLP-based sentiment analysis, and Strategy B, which employs predictive analytics for market trend forecasting. I rigorously optimized both strategies through backtesting and hyperparameter tuning, achieving a 1.4% annualized return and outperforming the HFRI Currency Index.
  </div>

<div style="text-align: center;">
  <img src="https://img.shields.io/badge/Time Series Forecasting-FF9800?style=for-the-badge&logo=git&logoColor=white" alt="Time Series Forecasting" title="Time Series Forecasting"/>
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
</details>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #222;
        background-color: #fff; 
    ">
    Web Scraping Project- Faculty Information from IIM Ahmedabad
  </summary>
    
<div style="padding: 20px; color: #222; text-align: justify;">
  <em><strong>Business Problem:</strong> How can we automate the extraction of detailed faculty information from dynamic websites for efficient data analysis and research? </em>
  <br><br>
  <div style="text-align: justify; color:  #222; ">
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
</details>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #222;
        background-color: #fff; 
    ">
    Macroeconomic Time Series Analysis using VAR Models
  </summary>
    
<div style="padding: 20px; color: #222; text-align: justify;">
  <em><strong>Research Problem:</strong> How do key economic indicators like inflation, unemployment, and the Federal Funds rate interact and influence each other over time, and how can these relationships be used for forecasting? </em>
  <br><br>
  <div style="text-align: justify; color:  #222; ">
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
</details>

<div style="display: flex; align-items: center; margin-top: 40px;">
    <h1 style="color: #2774ae; margin-right: 10px;">RESEARCH PAPERS</h1>
</div>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #222;
    ">
    A Reproduction Study of the Amazon Last Mile Routing Challenge:
A Traveling Salesman Problem Approach
  </summary>

  <div style="padding: 20px; color: #222; text-align: justify;">
    <em><strong>Research Focus:</strong> Improving the efficiency of last-mile delivery routes using real-world logistics data</em>
    <br><br>
    <p>
      This paper aims to reproduce and analyze the methodology employed by MIT researchers (Chen Wu, Yin Song, Verdi March and Eden Duthie), one of the top-performing team in the challenge. The analysis focuses on three key datasets - actual delivery sequences, route scoring outputs, and package-related metadata - and outlines the preprocessing and analytical framework applied. This paper reproduces the challenge by: (1) Modeling zone transitions using a probabilistic Prediction by Partial Matching (PPM) model, (2)Evaluating sequence prediction accuracy using both exact-match and set-based metrics, and (3) Generating executable routes by integrating zone-level predictions with Traveling Salesman Problem (TSP) optimization.
    </p>
    <a href="https://github.com/Github4Aakanksha/Amazon-Last-Mile-Route-Optimization/blob/main/Research_Capstone.pdf"
       style="
       display: inline-block;
       padding: 10px 20px;
       background-color:#003B5C;
       color: white;
       text-decoration: none;
       border-radius: 10px;
       font-size: 0.9em;
       font-family: Arial, sans-serif;
       box-shadow: 2px 2px 5px rgba(0,0,0,0.2);
     ">
       View Paper
    </a>

  </div>
</details>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #222;
    ">
    A Study of the Incentives Addressing the Demographic Crisis in South Korea
  </summary>

  <div style="padding: 20px; color: #222; text-align: justify;">
    <em><strong>Research Focus:</strong> Evaluating the effectiveness of South Korea’s pro-natalist policies using econometric analysis to identify the socio-economic and demographic drivers influencing fertility decisions</em>
    <br><br>
    <p>
      South Korea is experiencing one of the world’s fastest fertility declines despite extensive government incentives to encourage childbirth. This study analyzes provincial data using econometric modeling and comparative case analysis to examine how factors such as income levels, spousal age, childcare access, and gender dynamics influence fertility rates. The findings highlight significant regional disparities and suggest that long-term structural reforms, rather than financial incentives alone, are critical to addressing the country’s demographic challenges.
    </p>
    <a href="https://github.com/Github4Aakanksha/Amazon-Last-Mile-Route-Optimization/blob/main/Research_Capstone.pdf"
       style="
       display: inline-block;
       padding: 10px 20px;
       background-color:#003B5C;
       color: white;
       text-decoration: none;
       border-radius: 10px;
       font-size: 0.9em;
       font-family: Arial, sans-serif;
       box-shadow: 2px 2px 5px rgba(0,0,0,0.2);
     ">
       View Paper
    </a>

  </div>
</details>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #222;
    ">
    Navigating Turmoil: Unraveling Turkey’s Economic Crisis and Charting
a Path to Resilience
  </summary>

  <div style="padding: 20px; color: #222; text-align: justify;">
    <em><strong>Research Focus:</strong> Analyzing the macroeconomic drivers, policy decisions, and structural vulnerabilities that have contributed to Turkey’s recurring financial crises and evaluating pathways toward long-term economic stability</em>
    <br><br>
    <a href="https://github.com/Github4Aakanksha/Amazon-Last-Mile-Route-Optimization/blob/main/Research_Capstone.pdf"
       style="
       display: inline-block;
       padding: 10px 20px;
       background-color:#003B5C;
       color: white;
       text-decoration: none;
       border-radius: 10px;
       font-size: 0.9em;
       font-family: Arial, sans-serif;
       box-shadow: 2px 2px 5px rgba(0,0,0,0.2);
     ">
       View Paper
    </a>

  </div>
</details>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #222;
    ">
    Review Paper on Wassily Leontief's Paradox
  </summary>

  <div style="padding: 20px; color: #222; text-align: justify;">
    <em><strong>Research Focus:</strong> Evaluating the validity of classical international trade theories through an analytical review of Wassily Leontief’s Paradox and its global empirical evidence</em>
    <br><br>
    <p>
      This review paper examines the Leontief Paradox, a landmark challenge to the Heckscher–Ohlin theory of international trade, which posits that countries export goods that intensively use their abundant factors of production. By analyzing Leontief’s original input–output framework and reviewing empirical studies across economies such as the United States, Japan, Canada, Germany, and India, the paper explores inconsistencies between theoretical predictions and real-world trade patterns. The study highlights how evolving global trade dynamics, factor productivity, and structural economic variations contribute to deviations from classical trade models, offering deeper insights into modern international trade theory.
    </p>
    <a href="https://github.com/Github4Aakanksha/Amazon-Last-Mile-Route-Optimization/blob/main/Research_Capstone.pdf"
       style="
       display: inline-block;
       padding: 10px 20px;
       background-color:#003B5C;
       color: white;
       text-decoration: none;
       border-radius: 10px;
       font-size: 0.9em;
       font-family: Arial, sans-serif;
       box-shadow: 2px 2px 5px rgba(0,0,0,0.2);
     ">
       View Paper
    </a>

  </div>
</details>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #222;
    ">
    Impacts of COVID-19 on Consumer Behaviour & Preferences
  </summary>

  <div style="padding: 20px; color: #222; text-align: justify;">
    <em><strong>Research Focus:</strong> Analyzing how the COVID-19 pandemic reshaped consumer spending patterns, financial priorities, and adoption of digital commerce in India</em>
    <br><br>
    <p>
      Using a combination of primary survey data and secondary sources such as RBI and IBEF reports, the study evaluates changes in spending priorities, financial sentiment, and digital purchasing adoption. The analysis highlights a significant transition toward essential and health-related consumption, increased savings and investment awareness, and accelerated e-commerce and digital payment usage. The findings provide insights into long-term consumer adaptation and emerging market trends in a post-pandemic economy.
    </p>
    <a href="https://github.com/Github4Aakanksha/Amazon-Last-Mile-Route-Optimization/blob/main/Research_Capstone.pdf"
       style="
       display: inline-block;
       padding: 10px 20px;
       background-color:#003B5C;
       color: white;
       text-decoration: none;
       border-radius: 10px;
       font-size: 0.9em;
       font-family: Arial, sans-serif;
       box-shadow: 2px 2px 5px rgba(0,0,0,0.2);
     ">
       View Paper
    </a>

  </div>
</details>

<details style="
    margin-bottom: 20px; 
    border-radius: 8px; 
    background-color: #fff; 
    box-shadow: 0 8px 20px rgba(0,0,0,0.2), 0 10px 20px rgba(0,0,0,0.15);
    overflow: hidden;
">
  <summary style="
        cursor: pointer; 
        padding: 10px 15px; 
        font-size: 1.1em; 
        font-weight: bold; 
        color: #222;
    ">
    Review Paper on "Basel III in International and
Indian Context by D.
Subbarao"
  </summary>

  <div style="padding: 20px; color: #222; text-align: justify;">
    <em><strong>Research Focus:</strong> Analyzing the implementation and economic implications of Basel III banking regulations in global and Indian financial systems</em>
    <br><br>
    <p>
      This paper reviews the Basel III regulatory framework through the lens of Dr. D. Subbarao’s policy perspectives, examining its role in strengthening banking sector stability following the 2007–08 global financial crisis. The study evaluates Basel III’s capital adequacy, liquidity, and leverage reforms while analyzing their impact on the Indian banking system, particularly public sector banks. By reviewing policy initiatives such as the Government of India’s Indradhanush program and global empirical research, the paper highlights the trade-off between short-term profitability pressures and long-term financial resilience. The research also emphasizes the importance of data-driven policy calibration and improved risk assessment frameworks in maintaining banking sector stability.
    </p>
    <a href="https://github.com/Github4Aakanksha/Amazon-Last-Mile-Route-Optimization/blob/main/Research_Capstone.pdf"
       style="
       display: inline-block;
       padding: 10px 20px;
       background-color:#003B5C;
       color: white;
       text-decoration: none;
       border-radius: 10px;
       font-size: 0.9em;
       font-family: Arial, sans-serif;
       box-shadow: 2px 2px 5px rgba(0,0,0,0.2);
     ">
       View Paper
    </a>

  </div>
</details>




<style>
  body {
    font-family: 'Noto Sans', sans-serif;
  }
  /* Font style for headings */
  h1, h2, h3, h4, h5, h6 {
    font-family: \"La Gagliane\", sans-serif;
  }
</style>
