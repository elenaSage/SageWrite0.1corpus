# SageWrite corpus, version 0.1

## Structure of the dataset

Version 0.1 contains 100 manually annotated excerpts extracted from various academic articles. For each of the 100 excerpts, the corpus contains: 
(i) three different corresponding draft versions of the excerpt;
(ii) a list of tags that describe the quality of the excerpt. 

## The Drafts
When writing an article or an essay, authors generally start out by writing up a rough draft of what they want to say. This draft generally contains abbreviations, is schematic in nature and contains colloquial language. We asked three different annotators to read each excerpt and try to reverse-engineer what the draft version
of that excerpt might have looked like, and to write that down. 
Since we were interested in exploring individual differences in the way drafts are constructed, our annotators all annotated the same excerpts. This means that for each excerpt in the corpus there are 3 corresponding drafts, each authored by a different annotator.

## The Tags
We asked our annotators to evaluate the stylistic and linguistic merits of each excerpt by selecting dedicated tags. There were 19 tags in total. You find the full list below. 
In the corpus, each excerpt is associated with each of the 19 tags, and for each excerpt each of the 19 tags has a value ranging from “0” to “3”: “3” if that tag was selected for that excerpt by all three annotators, “0” if it was selected by no annotator. 

#### Tag description
The 19 tags we used were the following: 
- **Colloquial Language**: annotators were instructed whenever overly colloquial language is used;
- **Formal Language**: whenever excessively formal language is used, e.g. when expressions like et ceteris paribus are used (too often); 
- **Unnecessary jargon**;
- **Verbosity**;
- **Opaque writing**: for text that is obscure, hard to understand;
- **Overly long sentences**; 
- **Abuse of passive sentences**: e.g. "It has been found that there had been many …";
- **Excessively complex syntax**: e.g. “It is expected that an exploration of the variables affecting the effectiveness of reading aloud will support us in designing lessons (…)”;
- **Clear Structure**: to mark text that is clear and well-structured,  text that clearly communicates the writer's intentions, data or results;
- **Pretentiousness**;
- **Engaging Writing**: text that is compelling, witty and makes one want to read more;
- **Dull writing**: text that is dry, boring and not engaging
- **Redundant (content)**: to be used for words, phrases or clauses that are superfluous;  
- **Repetition (style)**: for anaphoric repetitions, epiphoric repetitions and anytime sentence structure or vocabulary is not diverse enough; 
- **Poor flow**: if the logical flow of a text is whacky, or whenever there are no clear threads to follow;
- **Non-sequitur**: sentences that do not follow logically from anything that was said before;
- **Unclear/vague**: for unclear referents, ambiguous statements and anything that should have been explained in more detail;
- **Fragment**: for sentences/ paragraphs that feel excessively telegraphic in style.
- **Word choice**: to be used for any questionable lexical choice, whether at the sentence level or at the level of single words.
 
When selecting which tags to include in our inventory, we tried to include tags that refer to different linguistic dimensions. For example, tags 1 to 5 relate to the
lexical dimension, tags 7 to 10 capture syntactic properties, tag 10 relates to pragmatics and tag 11 to 13 relate to the perceived stylistic merits or demerits of a
text. We also tried to balance the number of positive and negative tags.

## Notes on this version
Annotators were given the option to select tags either globally or locally. Locally selected tags referred to specific sub-parts of an excerpt, e.g. to specific words, 
phrases, paragraphs. An example would be the tag “overly long sentences”, that could apply to a single sentence. A tag that was selected globally meant that the specific
characteristic that the tag singled out applied to the entire excerpt; an example would be the tag “poor flow”. 
To simplify the structure of the corpus, in version 0.1 we eliminated the distinction between global and local tags: if a tag was selected by an annotator, it is associated
with a “1” value, regardless of whether the tag was selected globally or locally. The same holds for cases in which the same tag was selected locally more than twice within
the same excerpt. In future versions of the corpus, we plan on making the distinction between global and local tags accessible.  


