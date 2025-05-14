# Charity-Ride-NLP

This program uses web scraping and Natural Language Processing (NLP) techniques to gain customer insights on charity bike rides. This program is intended to supplement exploratory and descriptive marketing research.

Three forums are analyzed:
* Opinions on charity bike rides from bikers aged 50+
* Opinions on charity bike rides with minimum fundraising requirements
* Experience and impact of charity bike rides

## 1. Polarity Scores

📄 Description:\
From these forums, I used web scraping to extract the text from user posts. Then, I calculated the polarity scores, which assess how negatively or positively users feel about a subject from a scale of -1 to Scores closer to 0 are considered neutral.

📈 Results:\
The polarity scores for each of the three forums were 0.12, 0.16, and 0.19. These scores indicate neutral to slightly positive reactions from users about charity bike rides.

## 2. Latent Dirichlet Allocation (LDA)

📄 Description:\
LDA is a technique for identifying the main topics in a collection of documents.

📈 Results:
| Forum                                  | Main Topic                               |
|----------------------------------------|------------------------------------------|
| Bikers over 50                         | food support century club course         |
| Minimum fundraising requirements       | minimum fee costs money people           |
| Experience and impact of charity rides | community personal social change fitness |
