# T5-Finetuning-Chat-Summarization
* Finetuned the T5-Small Pretrained model for Dialogue/Chat Summarization achieving:
  * Evaluation Set Loss: 1.6551
  * Evaluation Set Rouge1: 43.6894
  * Evaluation Set Rouge2: 21.0711
  * Evaluation Set Rougel: 36.7865
  * Evaluation Set Rougelsum: 40.2927
* The Dataset used is the SAMSum Dataset consisting of chats/dialogues and their respective summaries. It is available on HuggingFace via - https://huggingface.co/datasets/Samsung/samsum
* Finetuned Model available for use on HuggingFace via - https://huggingface.co/koppolusameer/t5-finetuned-summarization-samsum
* Python Notebook also compares the dialogue summarization task results between T5-Small vs. BART-Large-CNN vs. PEGASUS/XSum (All of which are have only undergone pretrainig without any finetuning) on randomly chosen dialogues.
* Python Notebook also compares the dialogue summarization task results between finetuned version of T5-Small and pre-finetuned version of T5-Small
* Finetuning was done with T4 GPU on Colab Pro
