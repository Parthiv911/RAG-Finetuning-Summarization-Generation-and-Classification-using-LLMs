# RAG-Finetuning-Summarization-Generation-and-Classification-using-LLMs

The above .ipynb notebooks contain the code for the respective LLM tasks.

RAG:
1. Used ChromaDB, Gemini and Langchain to perform retrieval augmented generation and answer questions on a folder of research papers.
2. Simply modify the code containing the path to the research papers and run the script.

Text Classification: 
1. Fine-tuned the Distilbert model for emotion classification.
2. Performed Error analysis by sorting the error scores and identified the most confused, most mislabelled predictions.

Text Generation:
1. Used the GPT-2 model for text generation.
2. Compared Greedy and Beam Decoding by log probability of generated sentences.
3. Experimented with Sampling Temperatures and compared them qualitatively
4. Qualitatively analyzed the text generated by top-k and Nucleus Sampling (Top-p)

Text Summarization:

1. Compared the summaries generated by GPT-2, BART, T5 and PEGASUS with a baseline. The baseline is created by creating the summary by considering the first 3 sentences of the input text. The dataset used is CNN/DailyMail.
2. Evaluated PEGASUS on a subset of the dataset.
3. Fine-tuned PEGASUS on the SamSUM dataset and improved the ROUGE metric

