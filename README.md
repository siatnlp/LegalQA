# LegalQA
A Chinese question answering dataset for legal advice.

## Description ##

 - The corpus contains legal question answer pairs from Chinese online forums. The questions are raised by netizens and the answer are provided by licensed lawyers. 
 - It contains 4 data fields: question subject, question body, answer and label. 
 - The positive question answer pairs are the ground truth pair provided online. For all the questions, we select answers to other questions of the same category as negative answers. 
 - We manually annotate part of the dataset to ensure correctness. Manually annotated subsets are named as ''LegalQA-manual-train.csv'', ''LegalQA-manual-dev.csv'', ''LegalQA-manual-test.csv''.
 - For more QA pairs, please refer to the full dataset as ''LegalQA-all-train.csv'', ''LegalQA-all-dev.csv'', ''LegalQA-all-test.csv''.
 - Any further questions, contact as by raising issues.
