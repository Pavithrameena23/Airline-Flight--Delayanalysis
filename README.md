# Airline Flight Delay analysis

This project analyzes a massive dataset of over 5 million commercial flights to uncover the primary drivers of delays and cancellations in the aviation industry. Using Power BI, I transformed raw flight logs into an interactive executive dashboard that identifies seasonal trends, underperforming carriers, and airport congestion hotspots.

📊 Key Insights
Operational Bottlenecks: Approximately 64% of total delay minutes are caused by controllable operational factors like carrier issues and late aircraft arrivals.

Peak Delay Periods: Summer months (June–August) and late evening hours consistently show the highest delay rates across all major carriers.

Hub Congestion: A small group of major hubs (e.g., Chicago O'Hare and Dallas/Fort Worth) contribute nearly 40% of all national delays.

Reliability Leaders: Identified the top 5 most reliable airlines based on on-time performance (OTP) and low cancellation rates.

🛠️ Technical Toolkit
Data Cleaning & ETL: Handled 5.8M+ rows of data; used Power Query to standardize airport codes and handle missing delay values.

Data Modeling: Implemented a Star Schema for optimized performance with over 12,000 metadata files.

DAX Calculations: Created custom measures for On-Time Performance (OTP %), Average Delay Duration, and Delay Attribution Rates.

Large File Management: Utilized Git LFS to manage 700MB+ raw datasets within the repository.

📂 Repository Structure


├── .Report/                   # Power BI report metadata and layout

├── .SemanticModel/            # Data model and DAX measures

├── Project 1 Airlines/        # Raw datasets (CSV/Excel) managed via Git LFS

├── airline-flight-delay.pbip   # Main Power BI Project file

└── README.md                  # Project documentation

<img width="653" height="368" alt="1) Airline Flight Delay Analysis" src="https://github.com/user-attachments/assets/d475e051-bab2-4a1f-b600-185ebf128e21" />

