See guidelines, FAQ, etc here:
https://us.pycon.org/2025/speaking/tutorials/
Due December 19

# Turning Words Into Insights: NLP Techniques for Open-Ended Survey Analysis

## DESCRIPTION
An overview of strategies to make sense of open-ended survey data. Attendees
will leave with understanding of theory and experience identifying themes,
clustering similar responses, and making visualizations. We’ll also briefly
discuss applications for LLMs.

## AUDIENCE
Some experience: We’ll expect that attendees are comfortable with basic Python
but have no knowledge of data science, natural language processing, or relevant
packages.

## FORMAT
Very Interactive! We’ll divide the tutorial into several small sections. For
each section, we’ll start with a brief overview of theory, then we’ll provide a
working Jupyter Notebook (in Google Collab) with some sample data and code, and
then we’ll give time for everyone to explore parameters and share their results.

## OUTLINE

### Introduction (30 minutes) 
- Survey researchers rely on open-ended, qualitative questions to add depth and
nuance. Traditional methods for text analysis are labor-intensive, subjective,
and challenging to audit. 
- We’ll tell the story of a research project we did this year where we used our
Python skills to our county government understand some survey data. 
- We’ll briefly discuss traditional “coding,” challenges such as inter-rater
reliability, and ways that this can be scaled with Python tools like
[potato](https://github.com/davidjurgens/potato) and websites like
[Prolific](https://www.prolific.com/).

### Text Pre-processing (30 minutes) 
- [Example Jupyter Notebook for this segment](https://github.com/jackaaburk/ITE140/blob/main/Notes/NLP.ipynb) 
- Ingestion into Pandas, Lemmatization, stop word removal, spell checking. 
- We’ll share brief theory, then work through an example using Pandas and spaCy.

### N-Grams, Word Clouds, and Co-occurrence (30 minutes) 
- [Example Jupyter Notebook for this segment](https://github.com/MrJonesAPS/ITE140/blob/main/word_cloud_sample.ipynb)
- We can get far with some simple analysis based on word frequency. Everyone
likes a word cloud!

### Vector Embeddings (1 hour)
- [Example Jupyter Notebook for this segment](https://github.com/1bMedina/ite140/blob/main/notebooks/word2vec.ipynb)
- This is the exciting part of the tutorial! We’ll discuss vectorization, how we
can use vectorization to build searchable databases, and calculate document
similarty. We’ll briefly compare vectorization algorithms (eg word2vec vs BART).
- As a fun aside, we’ll tell the story of the 
[Earth Species Project](https://www.earthspecies.org/what-we-do/technology), a 
nonprofit which
hopes to use this strategy to talk to animals!

### Dimensionality Reduction and Visualization (30 minutes) 
- [Example Jupyter Notebook for this segment](https://github.com/aelliott26/ITE140/blob/main/Jupyter_Notebooks/Dimensionality-Reduction.ipynb)
- Vectorization is great, but it’s really hard to imagine what a 300-dimension
dataset looks like. We’ll go over strategies to visualize and make sense of this
data.

### Audience Choice (Remaining Time)
- There are a lot of topics that we can explore from here, but we won’t
necessarily have time for all of it. We’ll provide starter code for each of
these topics, and we’ll take audience input on which we should work through
together:
    - Clustering: How can we identify similar "species" of comments
    - Naive-Bayes Categorization: If we've manually categorized some comments,
    how can we automatically categorize the rest?
    - Co-occurrence Analysis: Once we've categorized comments, how can we find
    similarities between categories?
    - LLM’s for Survey Analysis: How can we use LLMs to help categorize
    comments, synthesize future responses, or even personalize surveys?

## PAST EXPERIENCE
Chris Jones is a teacher at a public high school in Arlington, Virginia, and Blu
Medina is one of Chris’s students. Chris and Blu studied this topic together
this school year as part of a survey research project organized by Arlington
County. As part of this project, Chris attended a conference at University of
Maryland about the role of AI in survey research.

Before teaching, Chris worked at Mastercard, first as a Data Engineer, then as a
Director of Product Management for data privacy platforms. Chris has a MS in
Systems Engineering from Virginia Tech and is working on an MS in Computer
Science from CU Boulder.

Blu presented a poster at PyCon 2024, and plans to present a poster again this
year as part of a club at our school called ‘ACC Django Girls’

## Notes
- The “sample Jupyter Notebooks” provided above were each produce by students in
Chris’s/Blu’s class this school year, and each student gave their permission for
their notebook to be shared in this proposal. For this tutorial, we would revise
these to use new sample data and have a cohesive style and format.
- This tutorial is inspired by a project that we did this year for Arlington
County. We do not have permission to share the survey data that we used, so
we’ll use a variety of freely-available text datasets, eg from Twitter.
- We have no affiliation with pandas, spacy, potato, or any of the other
projects highlighted in this talk. All of the sample code that we share will be
our own.

## Requests/Accessibility

Chris and Blu are both only available on Thursday, May 15. We would not be able
to attend a tutorial on Wednesday, May 14.