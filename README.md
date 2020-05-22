# Word2Vec-Analysis-and-Comment-Generation-using-r-Singapore-Data-Singaporean-English-
While there has been an abundance of semantic analysis based on embeddings produced
by Word2Vec, there has been a lack of more thorough analysis, especially for less common
languages. We observe that the English spoken in Singapore as one that exists on a
linguistic spectrum. On one hand, the colloquial form is highly derived from Southern
Chinese languages, as well as Malay. We define this creole language as Singlish. On the
other hand, within more formal contexts, and among those with a higher socio-economic
status, one tends to hear Singaporean Standard English, which is closely mutually intelligible
with other forms of English1.
In this paper, we aim to analyse the language written by Singaporeans online, which
includes both Singlish and Singaporean Standard English. In order to obtain a sufficient
corpus size, we utilised the Pushshift API which allows the retrieval of comments on the
subreddit r/Singapore. This amounted to 3.5 million comments from 2012 to 2019
November.
We performed two different broad analysis of Singaporean English:
1. Historical and bias semantic analysis based on Word2Vec (Daniel)
2. Singaporean text generation with GPT-2 (James)
