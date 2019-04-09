# LegalQA
A Chinese question answering dataset for legal advice.

## Description ##

 - The corpus contains legal question answer pairs from Chinese online forums. The questions are raised by netizens and the answer are provided by licensed lawyers. 
 - It contains 4 data fields: question subject, question body, answer and label. 
 - The positive question answer pairs are the ground truth pair provided online. For all the questions, we select answers to other questions of the same category as negative answers. 
 - We manually annotate part of the dataset to ensure correctness. Manually annotated subsets are named as ''LegalQA-manual-train.csv'', ''LegalQA-manual-dev.csv'' and ''LegalQA-manual-test.csv''.
 - For more QA pairs, please refer to the full dataset in LegalQA-all.zip which contains  ''LegalQA-all-train.csv'', ''LegalQA-all-dev.csv'' and ''LegalQA-all-test.csv''.
 - Any further questions, contact as by raising issues.

## Statistics ##

 1. LegalQA-manual
 
 | Train | Dev | Test
---- | --- | --- | ---
Number of questions | 783 | 93 | 136
Number of answers | 3121 | 602 | 865
Average length of questions | 160 | 180 | 159
Average length of answers  | 41 | 45 | 43

 2. LegalQA-all
 
 | Train | Dev | Test
---- | --- | --- | ---
Number of questions | 10526 | 1593 | 3035
Number of answers | 21237 | 2866 | 6091
Average length of questions | 160 | 173 | 168
Average length of answers  | 41 | 40 | 42

 3. Details
 
Dataset(train/dev/test) | #Question | #QA Pairs | %Correct
---- | --- | --- | ---
LegalQA(manual) | 783/93/136 | 7,258/816/1,169 | 21.8/23.3/23.9
LegalQA(all) | 10,526/1,593/3,035 | 100,590/11,965/26,913 | 21.8/24.4/22.9


## Experimental Results ##

 - Answer Selection

subset | MAP | MRR | P@1
---- | --- | --- | ---
LegalQA(manual) | 0.8230 | 0.8749 | 0.7868
LegalQA(all) | 0.8287 | 0.8867 | 0.8171
