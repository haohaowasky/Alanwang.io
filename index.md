## Dog Walking Project with Swifto



### What is Swifto ?

Swifto is a NYC based dog walking company who has 60 active walkers and hundreds of clients. 





### What is the challenges they have? 

-  Time consuming to schedule walks on the phone for clients. 
-  Reaching peak point for customer aquisition. 
-  Weak relationship bond between customers. 






### Reseach First! 

We did quantitative research along with qualitative user interviews. 





### Quantitative research - Twitter's API

#### Scriping through twitter


- How many twitts about Dogwalking in New York City last two years ?

- How people feel about Dogwalking ?

- What is the top ten popular words people say about dog walking ?




**Sample code for web craping**

```
#### Use Twitter's API to do consumer research

api = tweepy.API(auth)
public_tweets = api.search('DogWalking' and 'NYC ')

#### Loop thru to get maximum results

for tweet in public_tweets:
    print(tweet.text)
    analysis = TextBlob(tweet.text)
    print(analysis.sentiment)
```





***Result

<img src="2.png" width="500" height="300">

- Safty is the biggest concern
- People talk about Dogwalking **more than** using dog walk service








### Qualitative research - User interview

<img src="3.png" width="600" height="450">









### Solutions

- A mobile App is needed for customer aquisition and efficiency improvement 
- Adding GPS function to track dogs while they are being walked will solve safety issue
- A loyalty program can enhance merchant and consumer relationship







### The Design

<img src="4.png" width="700" height="450">








