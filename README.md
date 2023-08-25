# Formal Logic Deduction
![framework_overview](./images/framework_overview.PNG)

**F**ormal **L**ogic **D**eduction (**FLD**) is a project to teach language models deductive reasoning using synthetically generated examples based on formal logic theory.
FLD project originates from the paper [Learning Deductive Reasoning from Synthetic Corpus based on Formal Logic](https://proceedings.mlr.press/v202/morishita23a.html).

## What's good?
FLD serves as ...

* 🎓 **A foundation for learning logical reasoning**. FLD corpus teaches *fundamentals* of logic, as it adopts a well-grounded set of deduction rules based on formal logic theory.
* 👊 **A challenging benchmark** of logical reasoning, as a fully fine-tuned T5 language model cannot solve *even half* of the problems from the most difficult variant of FLD corpora.
* 🚀 **A basis for future experimental studies**, as it includes several toolkits as follows:
    - the corpora easily used via [🤗 the huggingface hub](https://huggingface.co/datasets/hitachi-nlp/FLD.v2).
    - [a simple training script](https://github.com/hitachi-nlp/FLD-prover/), which is a minimal adaptation of huggingface's script.
    - [a flexible corpus generator](https://github.com/hitachi-nlp/FLD-generator/), with which one can generate one's own corpus with a desired setting.

See [our paper](https://proceedings.mlr.press/v202/morishita23a.html) for details.

## Contents
* [Using the released FLD corpora](https://github.com/hitachi-nlp/FLD-corpus).
* [Train a language model based prover on a FLD corpus](https://github.com/hitachi-nlp/FLD-prover/).
* [Generating a new FLD corpus](https://github.com/hitachi-nlp/FLD-generator/).

## Contact
For any reason where a GitHub pull request or an issue is not appropriate, feel free to email terufumi.morishita.wp[at]hitachi.com.

## Citation
```bibtex
@InProceedings{pmlr-v202-morishita23a,
  title = 	 {Learning Deductive Reasoning from Synthetic Corpus based on Formal Logic},
  author =       {Morishita, Terufumi and Morio, Gaku and Yamaguchi, Atsuki and Sogawa, Yasuhiro},
  booktitle = 	 {Proceedings of the 40th International Conference on Machine Learning},
  pages = 	 {25254--25274},
  year = 	 {2023},
  editor = 	 {Krause, Andreas and Brunskill, Emma and Cho, Kyunghyun and Engelhardt, Barbara and Sabato, Sivan and Scarlett, Jonathan},
  volume = 	 {202},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {23--29 Jul},
  publisher =    {PMLR},
  pdf = 	 {https://proceedings.mlr.press/v202/morishita23a/morishita23a.pdf},
  url = 	 {https://proceedings.mlr.press/v202/morishita23a.html},
}
```
