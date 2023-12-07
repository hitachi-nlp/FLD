# Formal Logic Deduction
![deduction example](./images/deduction_example_GPT4.png)

**F**ormal **L**ogic **D**eduction (**FLD**) is a project to teach language models deductive reasoning using synthetically generated examples based on formal logic theory.
FLD project originates from the paper [Learning Deductive Reasoning from Synthetic Corpus based on Formal Logic](https://arxiv.org/abs/2308.07336).

## What's good?
FLD serves as ...

* 👊 **A challenging benchmark** of logical reasoning, as it assesses pure logical reasoning *isolated from knowledge*. Indeed, even GPT-4 can solve only half of the problems.
* 🎓 **A foundation for learning logical reasoning**. FLD corpus teaches *fundamentals* of logic, as it adopts a well-grounded set of deduction rules based on formal logic theory.
* 🚀 **A basis for future experimental studies**, as it includes several toolkits listed below.

## Contents
* You can [use FLD corpora](https://github.com/hitachi-nlp/FLD-corpus) via [🤗 huggingface hub](https://huggingface.co/datasets/hitachi-nlp/FLD.v2).
* You can [evaluate various LLMs](https://github.com/hitachi-nlp/FLD-fewshot-ICL-eval), such as GPT-4 and Llama, in few-shot in-context learning settings.
* You can fine-tune language models on FLD corpora. You can either use a logical-reasoning framework [LogiTorch/logitorch](https://github.com/LogiTorch/logitorch), or [our Transformers-based script](https://github.com/hitachi-nlp/FLD-prover/).
* You can generate corpora with your own setting using [a corpus generator](https://github.com/hitachi-nlp/FLD-generator/).

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

Japan's internal conferences:
```bibtex
@inproceedings{morishita2023NLP-FLD,
  title={形式論理学に基づく演繹コーパスによる言語モデルに対する演繹推論能力の付与},
  author={森下皓文 and 森尾学 and 山口篤季 and 十河泰弘},
  booktitle={言語処理学会予稿集},
  year={2023}
}

@inproceedings{morishita2023JSAI-FLD,
  title={人工演繹推論コーパスによる学習は言語モデルをどのように強化するか?},
  author={森下皓文 and 森尾学 and 山口篤季 and 十河泰弘},
  booktitle={人工知能学会全国大会論文集},
  year={2023}
}
```
