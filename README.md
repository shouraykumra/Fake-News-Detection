# Fake-News-Detection

About the data
The dataset I am using was acquired from IEEE Data Port available at https://ieee-dataport.org/open-access/fnid-fake-news-inference-dataset. The dataset includes 15212 training samples, 1058 validation samples, and 1054 test samples. 

The DataSet columns:

id: matches the id in the PolitiFact website API (unique for each sample)

date: The time each article was published in the PolitiFact website

speaker: The person or organization to whom the Statement relates

statement: A claim published in the media by a person or an organization and has been investigated in the PolitiFact article.

sources: The sources used to analyze each Statement

paragraph_based_content: content stored as paragraphed in a list

fullText_based_content: Full text using pasted paragraphs

label: The class for each sample
