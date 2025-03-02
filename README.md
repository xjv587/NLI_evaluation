# Analyzing and Mitigating Dataset Artifacts in Natural Language Inference (NLI) Models 

I investigated and improved the robustness of a pre-trained ELECTRA-small model on the Stanford NLI (SNLI) dataset by identifying and addressing dataset artifacts that hinder model performance, particularly in handling linguistic phenomena like negation and numerical reasoning.

## Key Components:

- Baseline Analysis: Analyzed the SNLI dataset using training dynamics to categorize examples into "easy-to-learn," "ambiguous," and "hard-to-learn" regions, identifying ambiguity as a major challenge.

- Error Analysis: Conducted a detailed error analysis on the validation set, revealing model weaknesses in handling negation and numerical reasoning, with neutral examples being the most problematic.

- Data Transformation: Designed and applied six types of data transformations (e.g., adding/reducing negation, changing numbers) to create "stretched contrast sets" that exposed model vulnerabilities.

- Model Improvement: Enhanced the training dataset by adding ~7.58% of transformed examples, resulting in a slight accuracy improvement from 89.08% to 89.26%, demonstrating the potential for further gains with more diverse transformations.

## Impact: 

This project highlights the importance of addressing dataset biases and provides a systematic approach to improving model robustness through targeted data augmentation. The findings suggest that increasing the representation of challenging examples (e.g., negation, numerical reasoning) can further enhance model performance and generalization.

## Skills Demonstrated:

- Data analysis and visualization

- Model evaluation and error analysis

- Data augmentation and transformation

- Natural Language Processing (NLP) and deep learning

- Problem-solving and critical thinking
