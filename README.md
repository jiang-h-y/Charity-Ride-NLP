# Charity Ride Exploratory Analysis

This program uses web scraping and Natural Language Processing (NLP) techniques to gain customer insights on charity bike rides. This program is intended to supplement exploratory and descriptive marketing research.

Three forums are analyzed:
* Opinions on charity bike rides from bikers aged 50+
* Opinions on charity bike rides with minimum fundraising requirements
* Experience and impact of charity bike rides

## 1. Polarity Scores

📄 Description:\
From these forums, I used web scraping to extract the text from user posts. Then, I calculated the polarity scores, which assess how negatively or positively users feel about a subject from a scale of -1 (negative) to 1 (positive). Scores near 0 are considered neutral.

📈 Results:
| Forum                                  | Polarity Score |
|----------------------------------------|----------------|
| Bikers over 50                         | 0.12           |
| Minimum fundraising requirements       | 0.16           |
| Experience and impact of charity rides | 0.19           |

These scores indicate neutral to slightly positive reactions from users about charity bike rides.

Note: Polarizing opinions on the forum posts may have balanced out to an overall neutral score.

## 2. Latent Dirichlet Allocation (LDA) Analysis

📄 Description:

LDA is a technique for identifying the main topics in a collection of documents through the distribution of words.

📈 Results:
| Forum                                  | Main Topic Keywords                      |
|----------------------------------------|------------------------------------------|
| Bikers over 50                         | food support century club course         |
| Minimum fundraising requirements       | minimum fee costs money people           |
| Experience and impact of charity rides | community personal social change fitness |

* Bikers over 50 focused on the logistics of charity bike rides, such as the food or support they would receive.
* The fundraising requirements discussion focuses on money and costs. Since the keywords mirror the forum topic, these results are relatively ambiguous.
* Charity bike riders seem to associate positive personal and community growth with charity bike riders.

## Sources
https://www.bikeforums.net/fifty-plus-50/1193362-charity-rides.html 

https://www.bikeforums.net/charity-events/1176088-charity-rides-minimum-fundraising-requirements.html 

https://www.cyclingforums.com/threads/have-you-participated-in-charity-rides-before-if-yes-could-you-share-your-experience-and-its-impact-on-yourself-as-well-as-others.488013/ 
