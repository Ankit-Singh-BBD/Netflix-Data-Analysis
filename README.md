# Netflix Data Analysis - Mini Project

This project analyzes the Netflix dataset to uncover insights that can help guide content strategy, user targeting, partnerships, and release planning. The dataset contains information about all movies and TV shows available on Netflix, including their genres, directors, cast, release year, duration, and country of origin.

## 📌 Project Objective
The primary goal is to identify strategic opportunities for Netflix, such as:
- What type of content should be produced.
- Which regions and genres are gaining traction.
- How content releases and preferences are shifting over time.
- Which creators, actors, and content formats drive platform engagement.

---

## 📂 Dataset Details
The dataset includes the following fields:

| Column | Description |
|-------|-------------|
| show_id | Unique ID for each title |
| type | Movie or TV Show |
| title | Name of the content |
| director | Director(s) of the content |
| cast | Actors involved |
| country | Country where content was produced |
| date_added | Date content was added to Netflix |
| release_year | Year of original release |
| rating | Content rating (e.g., TV-MA, PG) |
| duration | Total duration or number of seasons |
| listed_in | Genre classification |
| description | Summary of the content |

---

## 🛠️ Tools & Technologies Used
- **Python**
- **Pandas / NumPy**
- **Matplotlib / Seaborn**
- **Google Colab / Jupyter Notebook**

---

## 🔍 Key Questions Explored

### **Content Strategy**
1. Ratio of Movies vs TV Shows  
2. Most popular global genres  
3. Release year trends  
4. Top content-producing countries  
5. Yearly trend of content added on Netflix  

### **User Targeting & Audience Insights**
6. Most common content ratings  
7. Countries producing more mature content  
8. Genre distribution across Movies vs TV Shows  
9. Genre differences between the US and other countries  
10. Trending genres in the last 3 years  

### **Talent & Partnerships**
11. Top 10 directors with most titles  
12. Most frequently appearing actors  
13. Frequent director–genre combinations  
14. Titles with unknown cast/directors  

### **Duration & Engagement Patterns**
15. Average movie duration  
16. Most common number of seasons  
17. Trend in movie duration over the years  

### **Content Launch Strategy**
18. Months when most content is added  
19. Genre distribution over time  
20. Top countries for each genre  

---

## 📊 Summary of Key Insights (Short & Clear)

| Area | Insight 1 | Insight 2 | Recommendation |
|------|----------|----------|---------------|
| Content Type | Movies still dominate the catalog | TV Shows are growing faster | Invest more in long-form series to boost retention |
| Genres | Drama & International genres lead | Thrillers and Comedies remain strong | Expand global/region-specific productions |
| Countries | US produces most content | India, UK, Japan rising fast | Increase co-productions in growing markets |
| Ratings | TV-MA is most common | Indicates older viewer base | Maintain mature content but diversify family-oriented titles |
| Duration | Movies average around ~90-110 minutes | TV shows often last 1–3 seasons | Maintain optimal duration to match viewer attention |

---

## 🚀 How to Run the Project

```bash
# Clone the repository
git clone <your-repo-url>

# Open the notebook in Google Colab or Jupyter
Netflix_Analysis.ipynb
