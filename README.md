Self-attention-based architectures, in particular Transformers, have become the model of choice in natural language processing (NLP).
Inspired by the Transformer scaling successes in NLP, we experiment with applying a standard Transformer directly to images, with the fewest possible modifications. 
To do so, we split an image into patches and provide the sequence of linear embeddings of these patches as an input to a Transformer.
Image patches are treated the same way as tokens (words) in an NLP application
