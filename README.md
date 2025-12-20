# Laboratory-3-Transformer-Adaptation-for-Fun-and-Profit
In this laboratory, we explore different strategies for adapting a pre-trained Transformer model to a downstream Natural Language Processing (NLP) task using the Hugging Face ecosystem. The assignment focuses on sentiment analysis using the Rotten Tomatoes dataset and DistilBERT, a compact and efficient variant of BERT.
The following adaptation strategies are compared:
1. Feature extraction baseline, where the Transformer is used as a frozen encoder.
2. Full fine-tuning, where all model parameters are updated.
3. Parameter-Efficient Fine-Tuning (PEFT) approaches, including:
    - Partial fine-tuning
    - LoRA (Low-Rank Adaptation)

During the experiments, I observed that the original setup did not clearly highlight the advantages of PEFT methods. For this reason, I extended the analysis by repeating the experiments on a BERT-base model using the IMDB dataset. Since IMDB is larger and more complex, it better illustrates the trade-offs between full fine-tuning and parameter-efficient approaches.
All experiments are logged and compared using Weights & Biases (W&B). A detailed analysis of the results is available in the following W&B report: https://wandb.ai/matteo-piras-universit-di-firenze/Lab-3/reports/Untitled-Report--VmlldzoxNTM1MTU5MQ/edit?draftId=VmlldzoxNTM1MTU5MQ%3D%3D&importPanel= .