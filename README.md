# gaps-answers-dataset

This repository comprises of the data used for evaluation and testing purposes in the paper ‘Directed Graph-alignment approach towards Identification of Gaps in Short Answers’.

1. Files have been attached corresponding to each of the datasets namely, University of North Texas, ScientsBank and Beetle.
2. Each of the files consists of the following fields:

   -	**student_answer_id:** Answer ID of the student answer in which gap is to be identified   
    
   -	**question_paper:** The dataset that each student answer belongs to. ScientsBank dataset comprises of Train, Unseen Answer (UA), Unseen Question(UQ) and Unseen Domain(UD) subsets. They have been denoted as Scients_Train, Scients_UA, Scients_UQ and Scients_UD, respectively. Similarly, Beetle dataset comprises of Train, Unseen Answer (UA) and Unseen Question (UQ) subsets. They have been indicated as Beetle_Train, Beetle_UA and Beetle_UQ, respectively.   
    
   -  **question_text:** Question corresponding to the student answer
    
   -	**student_answer:** Student answer in which gap is to be identified
    
   -	**model_answer:** Model answer associated with the student answer
    
   -	**gap:** Actual gap in the student answer 
3. It is to be noted that all the sentences in both student and model answers are presented in corresponding active forms. 
    

