# Services

This folder contains the core prompt optimization logic.

These modules analyze and improve prompts before sending them to an LLM.

## Planned Modules

- prompt_classifier.py  
  Detects whether the input is text, code, or another format.

- text_optimizer.py  
  Optimizes natural language prompts.

- code_optimizer.py  
  Optimizes prompts related to programming tasks.

- token_counter.py  
  Calculates token usage before and after optimization.

- summarizer.py  
  Generates context summaries from previous prompts.
