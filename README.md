# Using LoRA to Fine-tune Llama-3.2-3B on Addition Scratchpad Data
For Masters Dissertation at City University of London  
All files are notebook files and optimized to run on google colab  
Thank you to Unsloth for providing an easy to use PEFT library  
**NOTE: Huggingface token be provided and have access to Llama-3.2 Family to download model**  

Files:
- Finetune: Loads, Fine-tunes and saves a Llama-3.2-3B Model
  - Dataset Generation functions included here
- Evaluate: Loads fine-tuned model and evaluates by prompting the model with 50 questions for each digit combination and determining accuracy
