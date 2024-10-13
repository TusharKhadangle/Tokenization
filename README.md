In this project, we analyze and compare the tokenization capabilities of two leading natural language processing libraries: Hugging Face Transformers and SpaCy, using the open-source IMDB dataset, which contains movie reviews and sentiment labels. We begin by loading the dataset and initializing the tokenizers from both libraries. After tokenizing the dataset, we extract the top 1000 tokens based on their information value and entropy to evaluate their significance. We then compare the two sets of tokens using metrics such as Jaccard similarity and entropy, and visualize the results to illustrate the similarities and differences. Finally, we draw conclusions on which tokenizer produces better tokens for sentiment classification tasks and discuss whether the results align with our initial expectations. This analysis provides valuable insights into the effectiveness of different tokenization approaches, informing future applications in sentiment analysis and text processing.
