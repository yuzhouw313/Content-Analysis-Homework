## Project Pitch

Potential research question: How do public sentiments and thematic concerns regarding COVID-19 evolve in online discussions throughout 2020 on YouTube, and what does this reveal about the impact of pandemic-related news on viewer perceptions and attitudes?

Data: All comments scraped from a set of COVID-19 related YouTube news videos' comment section during 2020. This will be an exploratory analysis so I don't have true labels (I do have 100 randomly selected comments hand-coded with sentiment labels).

Methods:
1. Clustering and topic modeling to discover underlying topics or hidden thematic concerns, which are perfect for dataset without pre-defined categories.
2. ML: Now that I have a set of topics from the previous clustering/topic modeling, I can use them as my true label in addition to human-coded labels to perform multi-class classification using machine learning models.
3. LLM: Build on classification machine learning models, I expect to use pre-trained LLM such as BERT for labeling tasks. I could also fine-tune LLM for sentiment analysis.

