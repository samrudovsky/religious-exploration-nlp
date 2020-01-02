
# Exploring Religious Texts with NLP

## Project 4 – Metis Data Science Bootcamp (Weeks 7-8)

**Technical Focus**
- Natural Language Processing 
	- Tokenization
	- Vectorization
		- TF-IDF
	- Dimensionality Reduction
		- NMF 
		- Topic Modeling
	- Sentiment Analysis
---
### Project Goals
Growing up without any religious tradition, I have always been curious about religious communities and the texts that bind them. As such, I sought to:
1) Capture common themes across a variety of religious texts (The Old Testament, The New Testament, The Koran, The Book of Mormon, and The Gospel of the Buddha)
	
2) Examine the narrative arc of each text through sentiment analysis
---
### Process
- Clean, tokenize, lemmatize, and account for "olde english" from the King James Bible to set up vectorized TF-IDF matrix  
- Use non-negative matrix factorization for dimensionality reduction to capture distinct, coherent topics across texts
- Using the TextBlob package, perform sentiment analysis in order to establish a basic narrative arc	
	- Compare and contrast each text's propensity to invoke emotions such as joy, fear, hope, and contrition

---
### Results

For most people, the results are intuitive. For me, a religious neophyte, I found them fascinating! 
1) The afterlife was a strong theme throughout each religious text (though addressed in distinct ways, particularly in Buddhist literature).

2) The notion of sacrifice, condemnation, and the "nature of reality" permeated each text.

3) Sentiment analysis was an unreliable tool on older texts, as polarity scores were unduly high, in part due to the outmoded language and idiosyncratic sentence structure of religious texts.
