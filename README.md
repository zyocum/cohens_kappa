# Cohen's kappa
## cohen.py
Functions for computing Cohen's kappa (𝜅), a measure of inter-annotator agreement between exactly two annotators.

Cohen's kappa is computed as follows:

        Pr(a) - Pr(e)
    𝜅 = -------------
          1 - Pr(e)
    
Where Pr(a) is the percentage of observed agreement and Pr(e) is percentage of expected agreement.