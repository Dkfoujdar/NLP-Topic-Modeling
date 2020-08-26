# LDA-NLP-Topic-Modeling
This takes free-hand text feedbacks as inputs in varying lengths, utilize the gensim and sklearn's LDA topic modelling libraries to output top topics representing the whole document. Here the document is defined as large number of sentences, each one of which contain string objects along with numeric values, commas, parenthesis, etc. Creating need for pre-processing. 
The LDA (Latent Dirichlet Allocation) works on the concept that document exhibits multiple topics and each topic is a distribution over words. It uses Gibbs sampling for modelling
The Model assessment and visualization part was carried out using pyLDAvis, coherence score, and perplexity.
