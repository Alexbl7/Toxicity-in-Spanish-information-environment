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

- `notebooks/`: contains the jupyter notebooks used in the study.
    - `topics_media`: characterize the five Spanish media outlets.
    - `Data-exploration`: explore data and perform sentiment analysis.
    - `topic_categories`: classify topics into categories .
    - `topic_modelling`: main notebooks with topic modelling.
    - `categories_analysis`: analyze hate, sentiments for each category.
- `data`: contains the data
    - `Human-in-the-loop-topic-labeling`: topics with the entire process of labeling.
    - `topics_media`: topics with distribution for each media outlet.
    - `humantag`: topics with human tag and category.
    - `keywords`: topics with keywords.
    - `id_topics_categories_sentiment`: increase of the dataset and id with respect to the original dataset.

> [!NOTE]
> The full dataset is not accessible.

## License
This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License.

## Acknowledgements
This work has been partially funded by the strategic project CDL-TALENTUM from the Spanish National Institute of Cybersecurity (INCIBE) and the Recovery, Transformation, and Resilience Plan, Next Generation EU, and the University of Murcia by FPU contract.

We thank the Hatemedia project (PID2020-114584GB-I00), financed by MCIN/AEI/10.13039/501100011033, for providing the dataset used in this work.
