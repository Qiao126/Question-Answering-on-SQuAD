# Question Answering with BERT and HuggingFace 🤗 (Fine-tuning)

You've seen how to use BERT, and other transformer models for a wide range of natural language tasks, including machine translation, summarization, and question answering. Transformers have become the standard model for NLP, similar to convolutional models in computer vision. And all started with Attention!

In practice, you'll rarely train a transformer model from scratch.  Transformers tend to be very large, so they take time, money, and lots of data to train fully. Instead, you'll want to start with a pre-trained model and fine-tune it with your dataset if you need to.

[Hugging Face](https://huggingface.co/) (🤗) is the best resource for pre-trained transformers. Their open-source libraries simplify downloading and using transformer models like BERT, T5, and GPT-2. And the best part, you can use them alongside either TensorFlow, PyTorch and Flax. 
