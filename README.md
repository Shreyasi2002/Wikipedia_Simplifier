# Wikipedia Simplifier

This project examines the problem of synthesizing articles for
Simple English Wikipedia. The latter is a project extending the power of
Wikipedia to kids, students of foreign languages, and people with learning disabilities by means of using simplified vocabulary, punctuation,
and sentence structures. The task of converting Wikipedia articles into
Simple English is hard because it falls in the gap between translation
and summarization: articles in Simple English are neither the shortened
versions of main Wikipedia, nor they maintain the one-on-one sentence
correspondence needed to train a translation system. To tackle this challenge, we employ a transformer-based text generation model directly
constrained for the output embeddings, and demonstrate that it can be
effective in simplifying the English text conditioned on context coverage
acquired in training.
