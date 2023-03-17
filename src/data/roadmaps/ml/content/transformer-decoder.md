# Transformer Decoder in ML

1.In machine learning, a transformer decoder is a type of neural network architecture that is commonly used in natural language processing (NLP) tasks such as language translation, text summarization, and sentiment analysis.

# Transformer decorder with NN

The transformer decoder is a component of the Transformer model, which was introduced in the paper "Attention Is All You Need" by Vaswani et al. in 2017. The Transformer model is a neural network architecture that uses self-attention mechanisms instead of recurrent neural networks (RNNs) to process sequential data.

The decoder component of the Transformer model is responsible for generating the output sequence, given the input sequence and the context information provided by the encoder. It does this by attending to the encoder's output and generating one token at a time. The decoder has multiple layers of self-attention and feed-forward neural networks, allowing it to model complex relationships between the input and output sequences.

# advantages
Transformer uses exclusively attention building blocks and gives very good results with far less engineering time required to tune it. Transformer suffers from neither of the problems that encoder-decoder architecture encounters (vanishing or exploding gradients).


# Conclusion
The transformer decoder has several advantages over traditional sequence-to-sequence models, such as RNNs. It allows for parallel processing of input sequences, which speeds up training and inference. Additionally, it can handle longer input sequences without suffering from the vanishing gradient problem that can occur in RNNs.

Overall, the transformer decoder has proven to be a powerful tool in NLP and has achieved state-of-the-art results on several benchmark datasets.


# Learning Source

[paragraph](https://towardsdatascience.com/7-things-you-didnt-know-about-the-transformer-a70d93ced6b2)
[Reference video](https://video.search.yahoo.com/search/video;_ylt=AwrO.hQU1xRkLIIMLhtXNyoA;_ylu=Y29sbwNncTEEcG9zAzEEdnRpZAMEc2VjA3BpdnM-?p=transformer+decoder+resources&fr2=piv-web&type=E211US714G0&fr=mcafee#id=1&vid=7ad8b79aa277035f9eceda4fa20f7db4&action=view)
[Transformer decoder video](https://video.search.yahoo.com/search/video;_ylt=AwrO.hQU1xRkLIIMLhtXNyoA;_ylu=Y29sbwNncTEEcG9zAzEEdnRpZAMEc2VjA3BpdnM-?p=transformer+decoder+resources&fr2=piv-web&type=E211US714G0&fr=mcafee#id=1&vid=7ad8b79aa277035f9eceda4fa20f7db4&action=view)
