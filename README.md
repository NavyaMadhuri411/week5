# Experiment 5: Zero-Shot vs Few-Shot Prompting

## Aim
To compare zero-shot and few-shot prompting for customer review sentiment classification using a Large Language Model (LLM).

## Problem Statement
Classify customer reviews into Positive, Neutral, or Negative categories and compare accuracy, format adherence, and prediction agreement.

## Algorithm
1. Define five customer reviews with ground-truth labels.
2. Create a zero-shot prompt without examples.
3. Create a few-shot prompt with three labeled examples.
4. Classify the same five reviews using both methods.
5. Compare model predictions with ground-truth labels.
6. Calculate accuracy and format adherence.
7. Display the results in comparison tables.

## Technologies Used
- Python
- Google Colab
- Google Gemini API
- Pandas

## Execution
1. Add `GEMINI_API_KEY` to Google Colab Secrets.
2. Open `zero_shot_vs_few_shot.ipynb`.
3. Run the notebook cells.
4. Observe the comparison table.
5. Save the execution screenshot in the `outputs` folder.

## Evaluation
Accuracy = (Correct Predictions / Total Reviews) × 100

Format Adherence = (Responses Containing Only a Valid Label / Total Reviews) × 100

Results depend on the model responses and API availability.

## Conclusion
The experiment compares zero-shot and few-shot prompting using the same test reviews and evaluation criteria. Few-shot prompting may improve classification consistency, but actual performance must be determined from the observed results.
