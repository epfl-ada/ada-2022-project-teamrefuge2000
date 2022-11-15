## How sexists are movies ?

AK proposition: (How / How much) Are movies subdued to gender diktats/stereotypes? 

### Abstract

"If [Marilyn Monroe] still fascinates us so much, it is because her story echoes the diktat that continues to mark out women's lives in a world controlled by the male gaze.”

It is by this powerful observation that the documentary “Becoming Marilyn”, released in 2021 by Arte Cinema, is introduced. This tells us two things: that women characters have failed to be more than projections of men’s expectations, and that the cinema in itself can be consider as a representation of our society and its diktats.

With this project, we would like to tackle the subject of gender representation in movies across time. Strong believers that women are more than gentle creatures and men are not only super strong, we want to investigate if the movies industry followed and still follows these stereotypes, and how does it varies between countries and movies genres.

### Research Questions

 - What is the gender parity across movie genres (are westerns still as male dominated as the stereotype describes it?)
 - What is the evolution of gender parity in films among countries over time (were some countries avant-garde? Are some still behind on this concept?)
 - Is there a variation of the main attributes -agent verbs, patient verbs and attributes- given to each gender across time?
 - Is there a variation in the box office revenue depending on the gender parity? Has it change over the years?
 - Do the mean age of the actors, male and female, evolves over the years? (with the cliché in mind that +40-year-old actresses are “outdated”)
 - Can we built the perfect archetypes of the male and female actor (age, height, ethnicity) over time?


### Additional datasets

AD1 : [Stanford CoreNLP-processed Summaries](http://www.cs.cmu.edu/~ark/personas/data/corenlp_plot_summaries.tar) : The plot summaries from the initial dataset, already pre-processed and ran through the Stanford CoreNLP pipeline. This allows the summaries to be already parsed and structured.

### Methods

#### Preprocessing (21/11 - 27/11)

We first want to clean the data and create the datasets we will use during the project. We want to proceed as in the paper, constructing for every character a set of words associated with it in the plot summaries (constructing a bag (*w*, *r*)  with word lemmas *w* and *r* belonging to {agent, patient, attribute}). With this, we can already work to find some features, as for example the average number of bags associated with each gender, what word lemmas are more prevalent (if any are), etc... 

#### Building personas (28/11 - 11/12)

We then want to build personas for each of the characters as discussed in the paper. That will help us analyze the typical persona of each gender, and how various each are. We can also compare box office revenue with the presence/absence of the personas, and draw conclusions with those results. 

#### Creating the website (12/12 - 23/12)

We will build the website then, or at least the shell of it, and start plotting the results we already have. From the preprocessed data we already have, we can already answer questions about gender parity across the countries and through time. We can also see how the typical personas have evolved throughout the years, and how well films have performed based on their gender parity.

### Timeline

### Organization within the team