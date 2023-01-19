# FLD
This is the entry-point repository for the FLD (**F**ormal **L**ogic **D**eduction) project, which aims to teach language models deductive reasoning by synthetic corpus based on formal logic theory.

## Using the FLD corpora
See [here](https://github.com/hitachi-nlp/FLD-corpus).

## Generating new corpora
See [here](https://github.com/hitachi-nlp/FLD-generator/).

## Train language models on FLD corpora
The model used in the paper is a simple step-wise prover of [the previous study](https://github.com/princeton-nlp/NLProofS), which generates one proof step at once until the given hypothesis is (dis)proved.
However, since the codebase includes the code for other verifier, it is a little complex.
Thus, we will re-implement the prover with minumul lines of codes.
Please wait for moments.
