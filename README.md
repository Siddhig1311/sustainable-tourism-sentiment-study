# sustainable-tourism-sentiment-study
A data-driven analysis of sustainable tourism at Gateway of India, Mumbai, using sentiment analysis of visitor reviews to uncover hidden insights and propose improvements for long-term sustainability.
This project presents a data-driven analysis of sustainable tourism at the Gateway of India, one of Mumbai's most iconic landmarks. Using sentiment analysis on Google Maps reviews, the study identifies patterns in visitor experiences, uncovers sustainability challenges, and proposes actionable insights for urban and tourism policy interventions.

---

## 📌 Objective

To analyze online tourist reviews using sentiment analysis to:
- Identify recurring themes in tourist feedback.
- Assess sustainability-related concerns such as crowding, waste management, and infrastructure.
- Offer data-informed suggestions to improve tourist experience and sustainability outcomes.

---

## 📊 Methods Used

- **Web Scraping** (manually collected ~50+ reviews from Google Maps)
- **Natural Language Processing (NLP)**
  - Text Cleaning
  - Tokenization
  - Sentiment Analysis using TextBlob
  - WordCloud and Frequency Distribution
- **Exploratory Data Analysis** on review metadata

---

## 🧠 Key Insights

- High frequency of keywords like **"dirty"**, **"overcrowded"**, and **"poor management"** reflected common concerns about hygiene and site maintenance.
- **Sentiment scores** showed a skew toward **neutral/negative experiences**, despite the **historical and cultural significance** of the monument.
- Recommendations include:
  - Improved **waste disposal mechanisms**
  - Smarter **visitor capacity management**
  - Implementation of **digital feedback systems** for real-time monitoring

---

## 💡 Technologies Used

- Python
- Jupyter Notebook
- TextBlob / VADER (for sentiment analysis)
- WordCloud, matplotlib (for data visualization)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙋‍♀️ Author

**Siddhi Gholap**  
Master’s in Analytics – Tata Institute of Social Sciences  
[LinkedIn](https://www.linkedin.com/in/siddhi-gholap)

---

## 📁 Project Structure

```bash
.
├── notebooks/                  # Jupyter Notebooks for sentiment analysis
│   ├── sentiment-analysis-1.ipynb
│   └── sentiment-analysis-2.ipynb
├── report/                    # Final PDF report
│   └── Sustainable tourism insights report.pdf
├── data/                      # CSV of scraped reviews
		└── Sustainable tourism insights report.pdf                  
├── README.md
└── LICENSE
