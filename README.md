# Machine_L_DecisionTrees
This is the first project of the Machine Learning course. 
Problem Description:
Splice junctions are points on a DNA sequence at which `superfluous' DNA is removed during the process of protein creation in higher organisms. The problem posed in this dataset is to recognize, given a sequence of DNA, the boundaries between exons (the parts of the DNA sequence retained after splicing) and introns (the parts of the DNA sequence that are spliced out). This problem consists of two subtasks: recognizing exon/intron boundaries (referred to as EI sites), and recognizing intron/exon boundaries (IE sites). (In the biological community, IE borders are referred to as ``acceptors'' while EI borders are referred to as ``donors''.)

Attributes predicted: given a position in the middle of a window 60 DNA sequence elements (called "nucleotides" or "base-pairs"), decide if this is a

a) "intron -> exon" boundary (IE) [These are sometimes called "donors"]
b) "exon -> intron" boundary (EI) [These are sometimes called "acceptors"]
c) neither (N)

Tasks:
1. Implement the ID3 decision tree learner.
2.Implement both Gini-index and Information Gain (entropy impurity) for evaluation criterion.
3. Implement split stopping using the chi-square test. 
4. Use your algorithm to train a decision tree classifier using the training data and report accuracy on the validation data. Compare accuracies by varying the evaluation criteria and confidence level in determining split stopping. For the latter, use 99%, 95% and 0% (i.e., you always grow the full tree).
