# Sentiment-Analysis-of-YouTube-Comments-Galaxy-A57
This project aims to analyze audience sentiment toward a YouTube review of the Samsung Galaxy A57 using Natural Language Processing (NLP). The analysis focuses on understanding how users express opinions through comments and how different sentiments relate to engagement.

## Objectives
- Analyze audience sentiment (positive, negative, neutral)
- Understand audience behavior in online discussions
- Measure engagement based on sentiment (likes)

---

## Dataset
- Source: YouTube comments  
- Channel: Gadgetin  
- Data collected using YouTube Data API  
- Fields:
  - `text` → original comment  
  - `likes` → number of likes  
  - `published_at` → comment timestamp  

## Methodology

### 1. Data Collection
- Scraped comments using YouTube Data API

### 2. Data Preprocessing
- Text cleaning (remove symbols, lowercase, etc.)
- Handling missing values

### 3. Sentiment Analysis
- Model: IndoBERT (Indonesian sentiment classifier)
- Approach: Hybrid (Model + Keyword-based refinement)

### 4. Visualization
- Sentiment distribution (Bar & Pie Chart)
- Engagement analysis (Average likes by sentiment)
- WordCloud
- 
##  Results

### Sentiment Distribution
- Neutral: 41%
- Negative: 36%
- Positive: 23%

### Key Findings
- Most comments are neutral, indicating informative discussions rather than strong opinions.
- Negative sentiment is relatively high, suggesting active audience criticism.
- Positive sentiment is lower, showing that appreciation is less frequently expressed.
- Comments with negative sentiment tend to attract higher engagement.

---

## Key Insight
> Audience engagement is primarily neutral, reflecting informative discussions. However, users are more likely to express criticism than appreciation, which aligns with common behavior in online platforms.

## Limitations
- NLP model may misinterpret informal language and slang
- Some sentiment classifications are not fully accurate
- Context understanding is limited
  
## Tools & Technologies
- Python (Pandas, Matplotlib)
- Google Colab
- NLP (Transformers / IndoBERT)
- Canva (for visualization design)
  
## Output
- Clean dataset (CSV)
- Visualizations (charts & poster)

## Author
Rozak Limbong

## Note
This project is created for educational and portfolio purposes.
