# COVID-19 Contact Tracing App Reviews Reveal Concerns and Motivations around Adoption

Background: Google and Apple’s Exposure Notifications System (ENS) was developed early in the COVID-19 pandemic to complement existing contact tracing efforts while protecting user privacy. An analysis by the Associated Press released in December 2020 estimated approximately 1 in 14 people had downloaded apps in states one was available. In this study, we assessed the motivation and experience of individuals who downloaded ENS apps from the Google Play and Apple App Stores.

Methods: We collected review text, star rating, and date of rating for all the reviews on ENS apps in the Google Play and Apple App stores. We extracted the relative frequency of single words and phrases from reviews and created an open vocabulary language, with themes categorized by the research team, to study the salient themes around reviews with high (3-5 stars), neutral (3 stars), and negative (1-2 stars) ratings using logistic regression. 

1) We used review data from 04/07/2020 to 03/31/2021 (Sample review data found in Google/Apple Reviews Folder). We used a python webscraping script to extract the review data in an organized manner.

2) CTM_NMF_Coherence_Scores_Code: We used techniques besides LDA such as Combined Topic Modeling and Non-Negative Matrix Factorization to extract the top 25 topics from our review data. Then, we found out each method's coherence score and chose to use LDA as it had the highest coherence score.

3) LDA Analysis: We used DLATK extract topics and ngrams from each review category (high, neutral, negative) and generated the word cloud figures (https://dlatk.wwbp.org/).

Results: Of 7622 reviews obtained from 26 states between 04/07/2020 to 03/31/2021, 6364 were from Google Play Store, and 1258 were from Apple App Store. We obtained reviews for a total of 38 apps, with 25 apps from the Google Play Store and 13 apps from the Apple Play Store. 78% of the reviews are either 1 star or 5 stars. Positive reviews were driven by ease of use, support for the state government in creating the app, and encouragement for others to download, as well as engage in other COVID-19 precautions. Negative and neutral reviews focused on issues with app functionality (i.e., installation and tracking errors). 

Conclusions: Uptake was the largest barrier to success for ENS apps, but states can use insight from app store reviews to better position themselves if they choose to develop further public health apps. 

Citation:

    @article{
        title={COVID-19 Contact Tracing App Reviews Reveal Concerns and Motivations around Adoption},
        author={Erica L. Dixon, Sukanya M. Joshi, William Ferrell, Kevin G. Volpp, Raina M. Merchant, Sharath Chandra Guntuku},
        journal={Public Library of Science (PLOS) One}, 
        year={2022}
    }
    
```
APA
Dixon, E. L., Joshi, S. M., Ferrell, W., Volpp, K. G., Merchant, R. M., & Guntuku, S. C. (2022). COVID-19 Contact Tracing App Reviews Reveal Concerns and Motivations around Adoption. Public Library of Science (PLOS) One
```
