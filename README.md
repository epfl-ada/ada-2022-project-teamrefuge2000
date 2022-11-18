## How sexists are movies ?

AK proposition: (How / How much) Are movies subdued to gender diktats/stereotypes?

### Abstract

"If [Marilyn Monroe] still fascinates us so much, it is because her story echoes the diktat that continues to mark out women's lives in a world controlled by the male gaze.”

It is by this powerful observation that the documentary “Becoming Marilyn”, released in 2021 by Arte Cinema, is introduced. This tells us two things: that women characters have failed to be more than projections of men’s expectations, and that the cinema in itself can be consider as a representation of our society and its diktats.

With this project, we would like to tackle the subject of gender representation in movies across time. Strong believers that women are more than gentle creatures and men are not only super strong, we want to investigate if the movies industry followed and still follows these stereotypes, and how does it varies between countries and movies genres.

### Research Questions

A. what is the gender parity across movie genres (are westerns still as male dominated as the stereotype describes it?)

B. what is the evolution of gender parity in films among countries over time (were some countries avant-garde? Are some still behind on this concept?)

C. Is there a variation in the box office revenue depending on the gender parity? Has it change over the years?

D. Is there a variation of the main attributes -agent verbs, patient verbs and attributes- given to each gender across time?

E. Do the mean age of the actors, male and female, evolves over the years? (with the cliché in mind that +40-year-old actresses are “outdated”)

F. Can we built the perfect archetypes of the male and female actor (age, height, ethnicity) over time?

### Additional datasets

AD1 : [Stanford CoreNLP-processed Summaries](http://www.cs.cmu.edu/~ark/personas/data/corenlp_plot_summaries.tar) : The plot summaries from the initial dataset, already pre-processed and ran through the Stanford CoreNLP pipeline. This allows the summaries to be already parsed and structured.

### Methods

**Step 0: Preliminary analysis for Milestone 2.** Initial analyses on our unprocessed datasets to see if our research questions are relevant.

**Step 1: Data scraping, pre-processing and dataset construction.**

Pre-processing of the data set: We first want to clean the data, map the freebase ids to their real names, which will be more simple for us to handle. We then want to proceed as in the paper, constructing for every character a set of words associated with it in the plot summaries (constructing a bag (_w_, _r_) with word lemmas _w_ and _r_ belonging to {agent, patient, attribute}). With this, we can already work to find some features, as for example the average number of bags associated with each gender, what word lemmas are more prevalent (if any are), etc...

Construction of datasets:

Dataset GP : Gender parity dataset containing info about each movie, their release date, their country of origin, their genre, their box office revenue and their calculated gender parity

GP1: subsets by country by origin (to later answer question A)

GP2: subsets by movie genre (to later answer question B)

GP3: subsets by box office revenue (to later answer question C)

_The subsets are built later on during step 2_

Dataset MGC: movie genre dataset containing info for each movie: release date, box office revenue, runtime, country of origin, as well as main topics extracted from the summary(?). Subsets based on movie genre, to later answer question D.

Dataset CC: characters characteristics dataset, containing … question E

Dataset AC: actors characteristics … question F

**Step 2: Investigate gender parity features in movies** based on dataset GP and create its subsets (so regarding countries, movie genres and box office revenue)

**Step 3: Investigate the evolution of movie genres characteristics across time** using MGC dataset

**Step 4: Characters characteristics** build the personas for each of the characters as discussed in the paper. That will help us analyze the typical persona of each gender, and how various each are. If it is too complicated, we can also just compare the lemmas associated with each character and compare it according to their gender, giving us already an idea.

**Step 5: Actors characteristics** More or less the same as step 4, but for actors rather than characters, to see if actors and actresses typically fall in a certain category of roles.

NB : steps 2,3,4 and 5 can be done in parallel

**Step 6**: Reflexion on conclusion and discussion, think if coherent of a conclusion figure

**Step 7: Visualisation**. export of some of our figures into external websites and softwares, for instance Google Data Studio for the results regarding country of origin.

**Step 8: website building, GitHub repository update and redaction of data story.**

### Timeline

| Period                      | Description                                                                                 |
| --------------------------- | ------------------------------------------------------------------------------------------- |
| November 5. - November 13.  | Steps 0 & 1: initial analyses and data pre-processing                                       |
| November 18.                | Milestone 2 Due Date                                                                        |
| November 21. - November 27. | Finish step 1                                                                               |
| November 28. - December 2.  | Pause to finish Homework 2                                                                  |
| December 2.                 | Homework 2 Due Date                                                                         |
| December 3. - December 11.  | Steps 2, 3, 4 & 5: Data processing and analysis                                             |
| December 12. - December 13. | Step 6: Conclusion and Discussion (Team Meeting)                                            |
| December 12. - December 20. | Steps 7 & 8: visualisation, website and GitHub repository construction, datastory redaction |
| December 20. - December 23. | Final modifications and fixes                                                               |
| December 23.                | Project Due Date                                                                            |

### Organization within the team

| Period                      | Augustin                                                                                                 | Maxime | Émilien                                                                                         | Albane                                                                                                   |
| --------------------------- | -------------------------------------------------------------------------------------------------------- | ------ | ----------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------- |
| November 21. - November 27. | Steps 2 and 3: investigation on gender parity features and the evolution of movie genres characteristics | Steps 2 and 3: investigation on gender parity features and the evolution of movie genres characteristics       | Step 1 : Construction of dataset GP                                                             | Step 1: Construction of dataset GP                                                                       |
| December 3. - December 11.  | Step 4 & 5 : studying the characteristics of each gender through the words associated with them          | Step 4 & 5 : studying the characteristics of each gender through the words associated with them       | Step 4 & 5 : studying the characteristics of each gender through the words associated with them | Steps 2 and 3: investigation on gender parity features and the evolution of movie genres characteristics |
| December 12. - December 20. | Redaction of datastory, Visualisation using external softwares and websites                              | Step 8 : building the website       | Step 8 : building the website                                                                   | Redaction of datastory, Visualisation using external softwares and websites                              |

We also decided to work in pair / in a circle format to review each other’s parts at each step: …

### Questions for TAs

...
