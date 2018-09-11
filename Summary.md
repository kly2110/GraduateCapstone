# Summary


## Situation
My graduate capstone was a semester long project where my team and I worked as consultants for a major media conglomerate. We designed and created a topic modeling augmentation algorithm to facilitate topic selection for content generation and management. We scraped external closed captioning data and used sentiment analysis, unstructured text analysis, time series analysis, etc. to identify trends in topics and potential topics for news coverage, generate revenue, and create opportunities for improved studio usage.


## Timeline

The intial data was given after the first week of classes. Halfway through the semester, we presented a proposal to to our client about possible directions we could take the project: 

https://github.com/kly2110/GraduateCapstone/blob/master/Presentation%20Proposal%20Censored.pdf

Based on feedback received from the client, we proceeded to refine our direction over the next month. We then submitted a proof of concept of our solution: 

https://github.com/kly2110/GraduateCapstone/blob/master/Proof%20of%20Concept%20Censored.pdf

Our final solution, along with the data analysis and market research of our project, was presented in the final presentation: 

https://github.com/kly2110/GraduateCapstone/blob/master/Final%20Presentation%20-%20Censored.pdf

Note that for all material, the name of our client and its competitors have been censored for confidentiality reasons. 


## Challenges
From the very beginning of the project, the media company could not articulate what they wanted us to do. They had a lot of issues they wanted solved, such as wanting to increase viewership, optimize their studio space, and help producers identify new topics to report on, but no specific direction. The dataset that we were given consisted of the output of a model that was developed using closed captioning data for one of their shows in 2017. This dataset was given to us with no context on how it was built, and the team told us that we could not receive any further information. 

We basically had to define the scope of the project ourselves and gather data for our analysis, and somehow connect it to the model they gave us. A lot of the difficulty in the project was less about the technical analysis, but was more in managing the scope of the project.

There were definite technical challenges within our analysis as well. The data scraped from different sources were formatted differently and had to be consolidated and cleaned, and processed with techniques such as sentiment analysis and word associations, which were techniques that some of us had little experience with in the past. The use of unstructured text data was also challenging, since sentiment analysis can be inaccurate.  

## Solution

We designed and created a topic modeling augmentation algorithm to facilitate topic selection for content generation and management. Essentially, our algorithm would read in news from stocktwits on Twitter and other new sources, find out what people were or weren’t talking about, and compare this to our company’s caption data. The changes in the words associated with our chosen key words (key topics we were interested in) would be analyzed by the algorithm and then outputted with a certain volatility score. Then producers and other decision makers could come in and decide what they wanted to talk about on that day’s broadcast based on the list and volatility scores received. 

We also included an analysis on the business monetary impact our algorithm would have on the company and market research information.

I believe that we were very successful in taking something that was previously undefined and delivering a project with a tangible monetary impact.

