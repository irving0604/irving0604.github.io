Lab 2 – YouTube Crawler: University of Washington

## Topic
This project explores how the **University of Washington (UW)** is represented on YouTube by analyzing video descriptions collected through a Selenium-based web crawler.

---

## Search Parameters
I collected YouTube video data using two groups of search terms.

### Group 1: UW Student Life
- UW campus
- University of Washington dorm
- UW student life

### Group 2: UW Academics
- University of washington academics
- UW computer science
- UW business school

Each group was crawled separately, and the results were stored as CSV files.

## Why This Comparison
I wanted to see and compare how UW is discussed in terms of **student life and campus experience** versus **academic reputation and programs**. These two perspectives represent different ways people engage with and talk about the university.

## Word Cloud Results

### Word Cloud – Student Life
![Word Cloud 1](img/wordcloud-1.png)

### Word Cloud – Academics
![Word Cloud 2](img/wordcloud-2.png)

## Comparison of Word Clouds
The student life word cloud emphasizes terms related to campus, dorms, students, and daily experiences. In contrast, the academics word cloud highlights words related to programs, majors, rankings, and academic disciplines.

Both word clouds include the university name and references to UW, but the surrounding language differs based on the focus of the search terms.

## Possible Reasons for the Observed Patterns
These patterns likely occur because different types of videos are created for different audiences. Student life content is often informal and experience-based, while academic-related videos focus more on programs, departments, and reputation. YouTube’s search algorithm and creator tagging behavior also influence which words appear most frequently.

## What REALLY Surprised Me
I expected some overlap between the two groups, but I was surprised by how distinct the vocabulary was between student life and academic-focused videos. The tone and emphasis of the descriptions were more different than I initially expected.

## How This Research Could Be Improved 
This research could be improved by collecting more videos, scrolling further down the search results, running the crawler at different times, or analyzing video transcripts and comments instead of only short descriptions.

## Data Downloads
- [Student Life Search Results](assets/search-result-1.csv)
- [Academic Search Results](assets/search-result-2.csv)
