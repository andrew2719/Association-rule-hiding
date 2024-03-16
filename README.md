# Association-rule-hiding

## Evaluation Notebook
To view the evaluation notebook and see the results, please refer to the [evaluation.ipynb](evaluation.ipynb) file.

## Results Folder
The results folder contains the before and after analysis results. You can find it [here](results/).

### Initial Transactions
The `initial_transactions.csv` file contains 2500 rows randomly selected from the `Assignment-1_Data.csv` file. These transactions were used for the analysis.

### Modified Transactions
The `modified_transactions.csv` file was generated using genetic algorithms with DEAP. It contains the modified transactions used for the analysis.To view the GA and its code [Rule_hiding.ipynb](Rule_hiding.ipynb)

### How the GA is applied
The GA is done by considering 3 params (0,1,2,3) where 0 -> no change, 1->remove LHS part, 2->remove RHS part, 3->remove both LHS and RHS and  finding fitness. by this ```combined_score = (1 - avg_penalty) * alpha + utility_score * beta```
Please refer to the evaluation notebook for a detailed analysis using these files.
