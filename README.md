# Scott Dwyer: Final Project Design Writeup

### Project Problem and Hypothesis
#### What's the project about?
* General elections are the premiere opportunity for Americans to participate in government, but they're essentially an endless series of claims by the two candidates. The stakes are extremely high and yet knowing whether candidates are being honest is extremely hard. This project aims to predict the truthfulness of individual claims made during the 2016 presidential ellection. 
* To solve the above problem, I'll be building a classification model that returns a "true" or "false" prediction for any given claim.
* If the model is successful, it could help people and organizations make more thoughtful decisions as they decide who should lead the United States.
* I believe that the most powerful predictors will be: the topic/domain candidates are speaking about, the repetition of particular words, and the sentiment with which a claim is made.

### Datasets
* I will have to scrape the web to build my data set. I will be using written transcripts of oral debates from the primary elections and will cross reference each claim with a truth rating on politifact.com. 

### Domain knowledge
* I have extensive experience as an armchair political scientist. 
* Google [appears](http://arstechnica.com/uncategorized/2006/10/7901/) to be working on this, but I couldn't find anything that's already complete.

### Project Concerns
#### What questions/concerns do I have about my project? 
* My biggest concern right now is that my prediction model will depend on correctly bounding each "claim". Should a claim have a maximum/minimum length? Should a claim be allowed to cover multiple topics? I don't yet know.
* I have a feeling that a decision tree will have the best performance, but I'm concerned that it won't be as useful as a logistic regression prediction model that can assign proabilities to outcomes.
* I'm still unsure how to parse text using NLP software. 
* I'm concerned it will be very difficult to get my data into a discernable format. 

#### What are the assumptions and caveats to my problem?
* I am assuming that each political candidate has detectable, verbal "tells" or patterns that reveal the truthfulness of their claims. This is by far my biggest assumption/caveat.

####What are the risks to my project?
* The risk of my model being wrong is that I could be misleading voters and corrupting the democratic process. 
* The potential benefit of my project is that it can theoretically help arm voters with facts. Unfortunately, facts don't seem to be the primary currency in elections, so the more I can do to emphasize them the better.

### Outcomes
* The output of my model will be either "True" or "False" for any given claim.
* I expect that my most important feature (whatever that turns out to be) will do the majority of the heavy lifting.
* I expect I will have to test many different models and methods, but I would not be surprised if the final model were quite simple.
* How successful does your project have to be in order to be considered a "success"?
* If the final project is a bust, I will use it as an opportunity to start a public conversation about how to improve verbal lie detectors. I'd love it if this project turned into a collaborative, open-source effort (however unlikely that is).
