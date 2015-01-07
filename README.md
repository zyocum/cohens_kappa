# Cohen's kappa
## cohen.py
Functions for computing Cohen's kappa (𝜅), a measure of inter-annotator  agreement between exactly two annotators.

Cohen's kappa is computed as follows:

        Pr(a) - Pr(e)
    𝜅 = -------------
          1 - Pr(e)
    
Where Pr(a) is observed agreement and Pr(e) is expected agreement.