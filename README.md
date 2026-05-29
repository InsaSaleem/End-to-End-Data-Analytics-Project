📊 CodeAlpha Data Analytics Internship Portfolio



Welcome to my Data Analytics internship repository! This repository showcases the projects and data-driven solutions developed during my internship at CodeAlpha. It features a comprehensive lifecycle of data analysis—ranging from raw automated web data collection to advanced data cleaning, interactive visualizations, and applied machine learning (Natural Language Processing).

🔗 Project Links



Live Deployed Dashboard: https://insasaleem.github.io/CodeAlpha_Data_Analytics/

Source Code Repository: https://github.com/InsaSaleem/CodeAlpha_Data_Analytics

📂 Repository Architecture

CodeAlpha_Data_Analytics/
├── docs/
│   └── index.html                         # Main interactive telemetry portal
├── Task 1_CodeAlpha_WebScraping/
│   ├── books_scraped.csv                  # Harvested tabular dataset log
│   └── CodeAlpha_WebScraping.ipynb        # Automated web harvester engine script
├── Task 2_CodeAlpha_EDA/
│   ├── CodeAlpha_EDA.ipynb                # Exploratory script and outlier checks
│   ├── eda_analysis.png                   # Rendered dataset distribution map
│   └── missing_values.png                 # Cleansed field metrics chart
├── Task 3_CodeAlpha_DataVisualization/
│   ├── chart1_line.png                    # Line graph component image
│   ├── chart2_bar.png                     # Age density histogram image
│   ├── chart3_pie.png                     # Ticket class allocation donut image
│   ├── chart4_heatmap.png                 # Correlation array metric matrix image
│   ├── CodeAlpha_DataVisualization.ipynb  # Visual data transformation script
│   ├── interactive_dashboard.html         # Standalone layout engine layer
│   └── interactive_dashboard.png          # Visual preview tracking image
├── Task 4_CodeAlpha_SentimentAnalysis/
│   ├── CodeAlpha_SentimentAnalysis.ipynb  # Dual-Engine NLP token text script
│   ├── sentiment_dashboard.png            # Polar layout distribution plot image
│   └── wordclouds.png                     # Frequency string text map image
└── README.md                              # Comprehensive repository documentation


🛠️ Core Technology Stack
Core Engine & Automation: Python 3.x
Data Engineering & Manipulation: Pandas, NumPy, Regular Expressions (re)
Web Data Extraction: BeautifulSoup4, Requests
Data Visualization & Analytics: Matplotlib, Seaborn, Plotly Express
Natural Language Processing & AI: VADER (SentimentIntensityAnalyzer), TextBlob, WordCloud

🚀 Detailed Project breakdown
🧩 Task 1: Automated Web Scraping Pipeline
Objective: Architect an automated parsing algorithm to pull catalog data directly from a live web server architecture.
Implementation: Leveraged Requests to handle HTTP requests alongside BeautifulSoup to map out and navigate DOM elements. Handled pagination dynamically to automatically loop across multiple store pages.
Output: Extracted and compiled 1,000+ records of books containing titles, pricing data, and stock status into a clean production-ready database: books_scraped.csv.

🔍 Task 2: Exploratory Data Analysis (EDA)
Objective: Perform end-to-end data diagnostics, data quality checks, and statistical profiling using the historical Titanic Dataset.
Implementation: Implemented dynamic tracking matrices to map out complex patterns of missing values. Resolved critical missing variables through custom feature engineering (median-imputation and data structure mapping).
Insights Extracted: Successfully identified survival multi-collinearity, indicating that ticket class (Pclass) and gender played a highly deterministic role in passenger rescue priorities.

🎨 Task 3: Data Visualization & Dashboarding
Objective: Translate complex multi-dimensional metrics into intuitive visual reports through static and interactive dashboard interfaces.
Implementation: - Static Layer: Used Matplotlib and Seaborn to output custom grid matrices mapping continuous age vs. fare density variables.
Interactive Web Layer: Deployed an advanced dark-themed analytical dashboard utilizing Plotly Subplots that allows users to seamlessly slice, zoom, and mouse-hover live over metrics.
Output Available: Live browser element saved as interactive_dashboard.html.

🧠 Task 4: Sentiment Analysis & NLP Engine
Objective: Build an automated Natural Language Processing framework to read, clean, and classify qualitative feedback from e-commerce customers.
Implementation: Built a custom text pre-processing pipeline to scrub text (casing normalization and regex token stripping). Utilized a dual-engine algorithmic evaluation tracking VADER's token-rule system against TextBlob's semantic polarity scoring.
Output Framework: Built cross-metric dashboards charting polarity vs. subjectivity scatter plots alongside conditional WordCloud arrays mapping dominant consumer phrasing.

📈 Key Technical Highlights & Deliverables
Cross-Model Validation: Task 4's evaluation engine demonstrated a high 92% consensus agreement metric between VADER and TextBlob sentiment predictions.
Web-Ready Assets: The dashboard architecture is fully exported into web standards, meaning the interactive dashboards can be launched natively inside any Google Chrome or standard web-browser interface instantly.
