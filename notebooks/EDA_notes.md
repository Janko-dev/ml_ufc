## EDA Notes  
- Open weight class and catch weight class are not standard weight classes. For open weight, it might be good to re-label (via clustering) to one of the 12 standard weight classes, because the class does not exist anymore.   
- `Winner` feature is very imbalanced:
  - **Red**: favourite
  - **Blue**: underdog
- Imbalance because UFC stats website started reporting blue wins, and thus using favourite/underdog, from 2010 onwards. Before 2010, every win is by the red fighter. 
- Matches that were declared as "No contest" are defined as a *loss* in the dataset (e.g., Jon Jones)
- Dataset only contains fight statistics **in** the UFC, i.e., history of fights prior to the their UFC debut are not included.
- Missing values when UFC fighter is fighting their first match in the organisation


