# GradeInsights: Analysis of University Results

# Exactscore: Automated University Result Analysis

## About

Result analysis is a crucial aspect of university administration as it provides insights into student academic performance and informs strategies for improvement. This analysis helps to:

* Identify strengths and weaknesses in teaching methods and curriculum design.
* Track student progress and provide targeted support.
* Make informed decisions about academic policies and program effectiveness.

## Problem Statement

The traditional method of result analysis in universities is predominantly manual, relying heavily on faculty members for data collection, entry, and analysis. This manual process presents several drawbacks:

* **Time-Consuming:** Manually extracting data from websites, inputting it into spreadsheets, and performing calculations is highly inefficient, consuming valuable faculty time that could be allocated elsewhere.
* **Frustrating:** The repetitive nature of manual data entry and the potential for errors can lead to frustration among faculty members.
* **Error-Prone:** Manual data handling increases the likelihood of errors, compromising the accuracy and reliability of the analysis.
* **Limited Insights:** Manual analysis often restricts the scope of insights that can be derived from the data, hindering a comprehensive understanding of student performance trends.

## How "Exactscore" Works

**Exactscore** is a proposed system designed to automate and streamline the process of university result analysis. The system leverages a combination of technologies to achieve this:

1. **Data Input:** Users provide the URL of the university's result page and define the range of student hall ticket numbers to be analyzed.
2. **Automated Navigation & Data Extraction:** Utilizing **Puppeteer JS**, the system automatically opens the specified URL, inputs each hall ticket number, and scrapes only the essential data required for analysis.
3. **Data Cleaning & Storage:** The extracted data is cleansed by removing irrelevant information and then stored in a **MongoDB** database, a NoSQL database chosen for its ability to efficiently handle unstructured data.
4. **Analysis & Presentation:** **MongoDB Query** functions are used to analyze the stored data based on pre-defined parameters. The analysis results are then presented on the user interface, created using **HTML5, CSS, and JavaScript**, in an organized and easily understandable format. The user interface's design is enhanced using **Bootstrap**, a framework providing pre-built design templates.

## Why Use "Exactscore"?

"Exactscore" offers several advantages over traditional manual result analysis methods:

* **Efficiency:** Automating the process significantly reduces the time required for result analysis, allowing faculty to focus on other important tasks.
* **Accuracy:** By eliminating manual data handling, Exactscore minimizes the risk of human error, ensuring greater data accuracy and reliability.
* **Comprehensive Analysis:** The system enables a more comprehensive analysis by considering various parameters and presenting data in an organized format, facilitating a deeper understanding of student performance.
* **Data-Driven Decision Making:** Provides real-time access to analyzed data, empowering educators and administrators to make more informed decisions about teaching methodologies, curriculum development, and student support.
* **User-Friendly Interface:** Features a simple and intuitive user interface, making it easy for users to interact with the system and interpret the results.
* **Scalability:** Designed to handle large datasets, making it suitable for universities of all sizes.

Overall, Exactscore aims to transform result analysis in universities, making it more efficient, accurate, and insightful. The system's goal is to provide educators with the tools they need to improve student outcomes and enhance the overall quality of education.

## Results

**Figure 8** shows the user interface of the **Exactscore** application. The data scraped by **Exactscore** is shown in **Figure 9**. **Figure 10** is a snapshot of the database where the scraped data is stored. Only the data necessary for analysis is scraped, and each subject is a different entry. **Exactscore** uses **MongoDB** for its database.

**MongoDB** is a non-relational document database that stores JSON-like data. It has a flexible data model for storing unstructured data, full indexing support, replication, and rich and intuitive APIs. **MongoDB** is designed for easy data access, rarely needing joins or transactions; however, it is capable of complex querying and analytics pipelines.

## Conclusion

The study analyzed student results to help formulate future teaching pedagogy based on student performance. The goal of the project is to make result analysis and evaluation easier. The developers plan to create a platform for all OU-affiliated colleges. The project used **Puppeteer**, a JavaScript framework, and **MongoDB** to store the scraped data for analysis.
