#Lexical Ambiguity Resolver: Prompt-Based Word Sense Disambiguation (WSD)

##Overview
This repository contains the implementation and resources for the paper: "Prompt-Based Word Sense Disambiguation using Few-Shot Techniques". The project focuses on addressing lexical ambiguity in computational linguistic tasks by leveraging advanced prompting techniques for Word Sense Disambiguation (WSD). Unlike traditional fine-tuning approaches, our method employs few-shot Chain of Thought (COT) prompts with GPT-4-Turbo and a knowledgebase retriever to achieve state-of-the-art results.

##Key Contributions
No Fine-Tuning Required: Utilizes prompt engineering instead of model fine-tuning for task-specific adaptations.
Few-Shot Chain of Thought (COT): Employs advanced COT prompting to enhance reasoning for sense prediction.
Knowledgebase Integration: Incorporates external knowledgebases as retrievers for enriching context and supporting sense definitions with synonyms.
State-of-the-Art Results: Breaks the 90% F1 score barrier on the FEWS dataset and demonstrates competitive performance on SemEval and Senseval datasets.

##Features
Prompt Design: Advanced contextual parameters crafted for guiding the model's inference towards accurate sense prediction.
Dataset Compatibility: Pre-configured for the following datasets:
FEWS
SemEval
Senseval
Efficiency: Reduces the computational overhead associated with fine-tuning while delivering superior results.
