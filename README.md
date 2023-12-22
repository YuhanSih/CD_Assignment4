# CD_Assignment4

This is a corpus of 20 highest rated poems written by T. S. Eliot. (Ranked by poetry experts on Poem Analysis, see the [link](https://poemanalysis.com/t-s-eliot/poems/). It can be used by anyone interested in his poems and modernist poetry. 

To get the texts, I searched the title of the 20 highest-rated poems on [Poetry Foundation](https://www.poetryfoundation.org/) and copied and pasted each poem into a txt file. Then I use SpaCy to generate annotation and save the results into the CSV file. I used the code from [the Corpus Analysis with SpaCy](https://github.com/yevgenm/corpus-analysis-spacy/blob/main/corpus-analysis-with-spacy.ipynb) tutorial written by Megan S. Kane and slightly adapted by Yevgen Matusevych. 

The CSV file includes the following variables:

| Header      | Description                                                                               |
|------------|-------------------------------------------------------------------------------------------|
| `Filename` | The filename of each txt file which is the title of the poem                              |
| `Year`      | The year when Eliot wrote this poem.                                                      |
| `Text`      | The text of the poem.                                                                     |
| `Doc`       | The text processed by the SpaCy trained models and Pipelines which will be used to perform tokenization, part-of-speech tagging, and other text enrichment tasks. |
| `Tokens`    | The individual words and punctuation markers of the document.                               |
| `Lemmas`    | The dictionary root word of each word.                                                    |
| `POS`       | The part-of-speech of each word.                                                          |
