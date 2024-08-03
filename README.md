# Exploring the topics, sentiments and hate speech in the Spanish information environment

## Authors
- Alejandro Buitrago López ([alejandro.buitrago@um.es](mailto:alejandro.buitrago@um.es)) <sup>M</sup>
- Javier Pastor-Galindo ([javierpg@um.es](mailto:javierpg@um.es)) <sup>M</sup>
- José A. Ruipérez-Valiente ([jruiperez@um.es](mailto:jruiperez@um.es)) <sup>M</sup>

## Affiliation
 <sup>M</sup> Department of Information and Communications Engineering, University of Murcia, Spain

## Abstract
>In the digital era, the internet and social media have revolutionized communication but also facilitated the spread of hate speech and disinformation, provoking radicalization, polarization, and toxicity. This phenomenon is particularly concerning for reputable news sources, as it can undermine public trust and contribute to social discord. To characterize the content surrounding these sources, this paper analyzes the topics, sentiments, and prevalence of hate in 337,807 messages (website comments and tweets) responding to news from five Spanish media outlets (La Vanguardia, ABC, El País, El Mundo, and 20 Minutos) in January 2021.

## Organization
The repository is organized as follows:

- `notebooks/`: contains the jupyter notebooks used in the study
    - `topics_media`: characterize the five Spanish media outlets
    - `Data-exploration`: explore data and perform sentiment analysis
    - `topic_categories`: slassify topics into categories 
    - `topic_modelling`: main notebooks with topic modelling
- `data`: contains the data
    - `Human-in-the-loop-topic-labeling`: topics with the entire process of labeling
    - `topics_media`: topics with distribution for each media outlet
    - `humantag`: topics with human tag and category
    - `keywords`: topics with keywords

> [!NOTE]
> The full dataset is not accessible.

## License
[MIT](https://choosealicense.com/licenses/mit/)
