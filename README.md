# An Annotated Corpus for Gender Stereotype Detection in French Tweets

This repository contains the first French corpus annotated for gender stereotype detection (see [corpus_GenderStereotypes.csv](https://github.com/patriChiril/An-Annotated-Corpus-for-Gender-Stereotype-Detection-in-French-Tweets/blob/main/corpus_GenderStereotypes.csv)) composed of about 9,200 tweets. The file [nonAnnotated.csv](https://github.com/patriChiril/An-Annotated-Corpus-for-Sexism-Detection-in-French-Tweets/blob/master/nonAnnotated.csv) contains all the collected data (the gender stereotype corpus is a subset of it).

Gender stereotypes are schematic and globalizing representations that attribute supposedly *natural* and *normal* characteristics (psychological traits, behaviours, social roles or activities) to women and men. Gender stereotypes have different and independent components (i.e., trait descriptors, physical characteristics, role behaviours and occupational status). Both these definitions lead us to the creation of the three categories of stereotypes presented in the following. Below, in order to better protect the privacy of the Twitter users, instead of presenting direct quotations from the French tweets, we only provide their English translations.

* **Physical characteristics** are related to physical strength or aspect. For example, the message:
```
 Short hair for a girl it's a bad idea  
```
conveys the stereotype *Girls must have long hair*.

* **Behavioural characteristics** are related to intelligence, emotions, sensibility or behaviour.
```
Am I supposed to recognize myself in the "Just Fab" ad with a screaming hysterical bitch?
```

* **Activities** are activities, jobs, hobbies that are stereotypically assigned to women. 
```
Never marry a woman who cannot cook (which implies that a woman's place is in the kitchen).

No woman understands football.
```

A tweet is annotated as **non-stereotype** when the tweet does not contain a stereotype.


Note that when a stereotype is present, it can be expressed explicitly, implicitly (i.e., one can infer a content such as *(all) women are...*) or it can be a denunciation/criticism of a gender stereotype.


## Ethical Approval

This dataset conforms to the Twitter Developer Agreement and Policy that allows unlimited distribution of the numeric identification number of each tweet.The data have been annotated with respect to certain types of stereotypical language, (e.g., commenting on physical appearance of a certain gender), however, we are not making any strong claims about the authors of the tweets, neither share a large numbers of tweets from the same users. 

Additionally, if any of the users want to opt out from having their data being used for research, they can request that they be removed from the dataset (without having to delete their own messages) by sending an email to *patricia.chiril@irit.fr*.

By releasing this dataset we hope to spur innovation and encourage new developments for the task of stereotype detection which can have positive effects for an extremely wide variety of tasks and applications. This dataset is not intended to be used for collecting user information which could potentially raise ethical issues. Relying on models flagging posts as sexist/conveying stereotypes based on user statistics might be biased towards certain users which eventually could limit freedom of speech on the platform.



