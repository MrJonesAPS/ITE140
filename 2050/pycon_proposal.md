See guidelines, FAQ, etc here:
https://us.pycon.org/2025/speaking/tutorials/
Due December 19

# From Words To Insights: Hands-On NLP for Open-Ended Survey Data Analysis

## DESCRIPTION
An overview of strategies to make sense of open-ended survey data. Attendees
will leave with an understanding of natural language processing (NLP) theory 
and experience using popular Python packages to clean text data, identify themes,
cluster similar responses, and make visualizations. 

## AUDIENCE
Some experience: We'll expect that attendees are comfortable with basic Python
but have no knowledge of data science or natural language processing. We'll give 
thorough introductions to all the packages we use - and folks who are already 
experienced with them will have an opportunity to play beyond our presentation.

## FORMAT
Very Interactive! We'll divide the tutorial into several small sections. For
each section, we'll start with a brief overview of theory, then we'll provide a
working Jupyter Notebook (via Google Collab) with some sample data and code, and
then we'll give time for everyone to explore parameters and share their results.

Each of these topics can be very technical. We'll focus on making sure that our
audience understands how and why to use these tools, with an emphasis on how
they all fit together into a broader strategy. 
We will not spend a ton of time on the underlying math, or going through
strategies for tuning hyperparameters. We'll be sure to provide links to
resources for folks who want to dive deeper!

## OUTLINE

### Introduction (30 minutes) 
- Survey researchers rely on open-ended, qualitative questions to add depth and
nuance. Traditional methods for text analysis are labor-intensive, subjective,
and challenging to audit. 
- We'll tell the story of a research project we did this year where we used our
Python skills to help our county government understand some survey data. 
- We'll briefly discuss the traditional process of manually reviewing survey responses 
(called "coding," but not in the Python sense), challenges such as inter-rater
reliability, and ways that this traditional process can be scaled with Python tools like
[potato](https://github.com/davidjurgens/potato) and websites like
[Prolific](https://www.prolific.com/).

### Text Pre-processing (30 minutes) 
- [Example Jupyter Notebook for this segment](https://github.com/jackaaburk/ITE140/blob/main/Notes/NLP.ipynb) 
- Ingestion into Pandas, Lemmatization, stop word removal, spell checking. 
- We'll share brief theory, then work through an example using Pandas and spaCy.

### N-Grams, Word Clouds, and Co-occurrence (30 minutes) 
- [Example Jupyter Notebook for this segment](https://github.com/MrJonesAPS/ITE140/blob/main/word_cloud_sample.ipynb)
- We can get far with some simple analysis based on word frequency. Everyone
likes a word cloud!
- Co-occurrence helps us understand how frequently different words appear together,
and there are some interesting visualizations we can make to help understand and communicate co-occurrences.

### Vector Embeddings (1 hour)
- [Example Jupyter Notebook for this segment](https://github.com/1bMedina/ite140/blob/main/notebooks/word2vec.ipynb)
- This is the exciting part of the tutorial! We'll discuss vectorization, how we
can use vectorization to convert natural language into quantified values that we can do math on.
- We'll show you you can use this to build searchable databases and calculate document
similarty. We'll briefly compare vectorization algorithms (eg word2vec vs BART).
- As a fun aside, we'll tell the story of the 
[Earth Species Project](https://www.earthspecies.org/what-we-do/technology), a 
nonprofit which hopes to use this technique to talk to animals!

### Dimensionality Reduction, Clustering, and Visualization (30 minutes) 
- [Example Jupyter Notebook About Dimensionality Reduction](https://github.com/aelliott26/ITE140/blob/main/Jupyter_Notebooks/Dimensionality-Reduction.ipynb)
- [Example Jupyter Notebook About Clustering](https://github.com/lehiem/ITE140/blob/main/k_means_clustering.ipynb)
- Vectorization is great, but it's really hard to imagine what a 300-dimension
dataset looks like. We'll go over strategies to visualize and make sense of this
data.
- We'll use Seaborn for visualization.

### Audience Choice (If any remaining time)
- There are a lot of topics that we can explore from here, but we won't
necessarily have time for all of it. We'll provide starter code for each of
these topics, and if there's time, we'll take audience input on which we should 
work through together:
    - Naive-Bayes Categorization: If we've manually categorized some comments,
    how can we automatically categorize the rest?
    - LLM's for Survey Analysis: How can we use LLMs to help categorize
    comments, synthesize future responses, or even personalize surveys?

## PAST EXPERIENCE
Chris Jones is a teacher at a public high school in Arlington, Virginia, and Blu
Medina is one of Chris's students. Chris and Blu studied this topic together
this school year as part of a survey research project organized by Arlington
County. As part of this project, Chris attended a conference at University of
Maryland about the role of AI in survey research.

Before teaching, Chris worked at Mastercard, first as a Data Engineer, then as a
Director of Product Management for data privacy platforms. Chris has a MS in
Systems Engineering from Virginia Tech and is working on an MS in Computer
Science from CU Boulder.

Blu presented a poster at PyCon 2024, and plans to present a poster again this
year as part of a club at our school called 'ACC Django Girls'

## Notes
- The “sample Jupyter Notebooks” provided above were each produced by students in
Chris's/Blu's class this school year, and each student gave their permission for
their notebook to be shared in this proposal. For the actual tutorial, we would revise
these to use new sample data and have a cohesive style and format.
- This tutorial is inspired by a project that we did this year for Arlington
County. We do not have permission to share the survey data that we used, so
we'll use a variety of relevant data that we've identified and cleaned ahead of time 
(we can provide specific examples if that helps!)
- We have no affiliation with pandas, spacy, potato, or any of the other
projects highlighted in this talk. All of the sample code that we share will be
our own.

## Requests/Accessibility

Chris and Blu are both only available on Thursday, May 15. We would not be able
to attend a tutorial on Wednesday, May 14.