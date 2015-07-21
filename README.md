# ComputationalEgoLevel

## Project overview

Ego level has been called the "master trait," second only to intelligence in its importance for understanding individual differences in personality (Loevinger, 1966, p. 205). Ego level is typically assessed using one of several versions of the Washington University Sentence Completion Test (WUSCT; Hy & Loevinger, 1996). The WUSCT has been described as the most thoroughly validated projective measure of personality (Lilienfeld, Wood, & Garb, 2000). Because the construct of ego level is assessed by the analysis of samples of speech, and because the relationship between these speech samples and the construct has been extensively validated, ego level is an attractive candidate for applying computational or corpus linguistic methods.  **In this project, we examine the relationship between language use and ego level.**

Ego development is in many ways more akin to a worldview than a simple personality trait, for the construct embodies a way of thinking in which virtues such as authority and fairness are not treated as equal (cf., Haidt's Moral Foundation's Theory), but as sequential waystations towards higher virtues of reflection and, somewhat paradoxically, tolerance.  Ego level is a dynamic construct, not a static one, and can be galvanized by social events (Lanning, Colucci, & Edwards, 2007). If ego development can be scored from everyday language, then the content of texts from Twitter feeds to political speeches, and from childrens' stories to strategic plans, will provide new insights into  our state of moral, social, and cognitive development. 

Our proposed series of analyses is complex. The project involves at least two types of source data, two approaches to coding speech, and three ways of approaching the construct of ego development. 

**Two types of data**. Datasets will include both *exemplars* (the contents of the 1996 scoring manual) and *empirical protocols* (scored sentence completion tests from Lannings' lab and those of others).  The datasets differ in two ways. First, the size of the exemplar dataset is substantially smaller than that of the empirical data (see Table 1).  Second, in the exemplars, we can expect to find a relative oversampling of responses at extreme (particularly high) levels; without this oversampling, the number of sample responses at these levels would be very low, and potential coders could not be expected to reliably recognize and score the rich, complex responses of the highest levels when they do occur.  Third, in the empirical protocols, but not the exemplars, individual sentence completions are nested within persons, requiring a multilevel approach to data analysis.  Because of these differences, the results for the empirical data cannot be expected to simply replicate those for the exemplars.

----------

***Table 1: Current project status***

|  Dataset  | N(persons) | N(responses) | N(distinct 'words') | N(total words) |       Status (7/15)       |
|:---------:|:----------:|:------------:|:-------------------:|:--------------:|:-------------------------:|
| Exemplars |        --- |         7586 |                4912 |          57317 | Analyses largely complete |
| Empirical |       1605 |        26575 |                ---- |         186261 | Data still being compiled |
 *(Note: Since May 2015, we have added 7133 newly coded and cleaned responses)*

----------
**Two approaches to coding speech**.  A distinction may be drawn between closed or dictionary and open approaches to linguistic analysis  (see, e.g., Park, Schwartz, Eichstaedt, Kern, Kosinski, Stillwell, Ungar, & Seligman, 2014). In a closed approach, words are first classified into *a priori* categories, as in the  Linguistic Inquiry and Word Count (LIWC; Pennebaker et al, 2007). This approach has the advantage of reducing a large number of measures (individual words) into a smaller set, but loses the possibility of a fine grained analysis.  We believe that each of these approaches will be informative.

(A third approach to coding speech can also be described, in which words are clustered into phrases or topics based on their co-occurrence or latent meaning; we do not at this point plan on incorporating this into our analyses).

**Three ways of interpreting ego level**.  Ego level is a construct which may be understood in at least three distinct ways, each of which suggests a different approach to the language based assessment (LBA) of personality.  

First, ego level may be treated **as a single dimension**. When correlations between ego level and constructs such as the five factors are examined, ego level is implicitly treated as a single dimension.  Typically, but not invariably, only linear relations are examined (cf. Einstein & Lanning, 1998).  This suggests an approach in which ego development is treated as a simple continuum,  and the LBA is based on the relationship between this continuum and the simple or relative frequency of occurrence of words in speech.  

Second, ego level may be treated **as a set of discrete types**.  This suggests an  approach to LBA in which language at a given level (e.g., Conscientious) is compared to that for all other levels taken together.  This approach is illustrated in Figure 1, in which a word cloud is shown for the words (in the exemplar data) which are differentially characteristic of the Conformist level in contrast to each of the remaining levels of ego development. 

----------

####Figure 1. 
####Words particularly characteristic of the Conformist level 
![](http://i.imgur.com/ZKgq13Z.png)

----------

Finally, ego level may be considered **as a sequence of developmental milestones** (Loevinger, 19xx) or achievements, successively becoming regnant then waning over time. The milestone approach suggests that each ego level should be compared both with those that are higher or lower (e.g., Conscientious versus all lower stages). A related approach is to contrast each level with only adjacent stages, as this may illuminate the differences or developmental transitions between stages.  

It should be noted that this approach has the potential to illuminate psychological theory: For example, in considering the compelling comfort and mutual reinforcement of the Conformist level - a stage characterized by interpersonal loyalty and reciprocity - Loevinger (1993) wondered what could motivate people to grow beyond this, speculating that the transition to higher stages (Self-Aware, then Conscientious) could be stimulated by self-doubt concerning whether one met the idealized image of the group.  An impressionistic look at the limited data of the exemplars (429 unique terms occurring 3 or more times in the Conformist and Self-Aware stages), suggests limited support for this both in words which appear (*decisions, difficult, honest*) and disappear (*essential, wonderful, beautiful*) at the higher stage.


----------
####Figure 2. 
####Words increasing (green) and decreasing in frequency (red) at the Conformist -> Self-aware transition 
![](http://i.imgur.com/YE6AKw3.png)

----------

## An invitation

Small is not always beautiful, and in order to provide a robust dictionary of words characteristic of each ego level, we need to compile as much WUSCT data as possible before moving too much farther in our analyses. More data are needed, in particular, for the fine grained analysis of differences between adjacent stages, as illustrated above.

We invite you to join with us on this project if you have SCT data which includes the following fields:

* an anonymous subject identifier
* an SCT item number or stem
* a coded value of ego level for each stem for one or more judges
* the number of judges used to arrive at the value above

and optionally:

* respondent sex
* year the data were gathered
* respondent age
