# llm-powered-rinsight-scraper-analyzer
Automate secondary research by scraping articles and analyzing them using AI and ML techniques to generate actionable insights. This includes scraping articles from KPMG, performing comparative analysis using language models, and summarizing findings in a report or dashboard.
1. Scraping Articles
Scrape insights articles from KPMG websites.
Extract key information such as:
1. Title
2. Article URL
3. title_description
4. Content (Full text)
5. pdf_content: If an article has an associated PDF, download the PDF and extract its content.

2. Comparative Analysis
Utilize AI and ML models along with Prompt Engineering to analyze and compare the content.
1. Preprocessing - Clean and normalize the text data 
2. Classify Articles by Industry - Use large language models such as facebook/bart-large-mnli to classify the articles into specific industries.
3. Extract Themes, Topics, or Keywords - Use facebook/bart-large-mnli to identify the key themes, recurring topics, or significant keywords from the articles.
4. Cluster Themes using HDBSCAN for clustering.
5. Vectorize the articles using Sentence transformer embeddings.
6. Apply clustering to group similar themes.
7. Link each cluster back to its source articles to ensure traceability.
 
3. Create a report
Approach along with the models, algorithms & tools used.
Key industries covered by each firm.
Top themes and topics highlighted by KPMG.
Visualizations of the findings.
