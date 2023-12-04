# Legal-Text-Classification

This work was done during Oct 2022 - Dec 2022, as part of a course Project.  
This whole project consisted of attempting on the two subtask of legaleval https://sites.google.com/view/legaleval/home (Part of SemEval 2023 tasks):

- Sub-task A: Rhetorical Roles Prediction (RR)
- Sub-task C: Court Judgement Prediction with Explanation (CJPE)

We were a team of 4. I was fully involved in the subtask-A, which is what this repository consists of.  
  
The data we worked with was given by the organizers accordingly.
  
Summarizing the methods/models we applied, as also mentioned in the 'Final Presentation.pptx':
1. BERT and its variants
2. Various methods of pooling
3. BiLSTM
4. BiLSTM + CRF

### Directory Structure:
- diff_models_pool.ipynb - contains the code in which we tried with various ways of pooling to come up with a sentence level embedding.
- The other two ipynb files are the ones having the codes in which we tried different variants of bert like legalBert, sbert, BERT etc. We found that BERT performed the best hence proceeded with BERT for all further tasks while using lSTM, BiLSTM and BiLSTM + CRF
- outputs folder - It has all different statistics and confusion matrix using all the different models.
- Final_Presentation.pptx - This is the final consolidated work in a ppt. You can refer to this for more details.
