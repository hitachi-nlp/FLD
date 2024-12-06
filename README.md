# Formal Logic Deduction
![deduction example](./images/deduction_example_GPT4.png)

**F**ormal **L**ogic **D**eduction (**FLD**) is a project to teach language models deductive reasoning using synthetically generated examples based on formal logic theory.  

$\color{red}{(2024/11/21)}$ We are working on the resource release for our NeurIPS 2024 paper, "Enhancing Reasoning Capabilities of LLMs via Principled Synthetic Logic Corpus."
The resources will be made available before the conference, i.e., by early December.

## [!] News
* **We released a Japanese logical benchmark [JFLD](https://github.com/hitachi-nlp/FLD-corpus/blob/main/README.JFLD.md).**

## What's Good?
FLD serves as ...

* 👊 **A Challenging Benchmark for Logical Reasoning**: FLD assesses (i) pure reasoning *isolated from knowledge*, and (ii) diverse reasoning patterns. Indeed, even GPT-4 can solve only about half of the problems.
* 🎓 **A Foundation for Learning Logical Reasoning**: The FLD corpus teaches the **fundamentals** of logic, adopting a well-grounded set of atomic deduction rules based on formal logic theory.
* 🚀 **A Basis for Future Experimental Studies**: It encompasses several toolkits as listed below, paving the way for innovative research.

## Contents
* You can use the corpora via 🤗 huggingface hub. See [here](https://github.com/hitachi-nlp/FLD-corpus).
* You can evaluate various LLMs, such as GPT-4 and Llama, by using [lm-evlauation-harness](https://github.com/EleutherAI/lm-evaluation-harness/tree/main/lm_eval/tasks/fld) or [our evaluation scripts](https://github.com/hitachi-nlp/FLD-fewshot-ICL-eval).
* You can fine-tune language models on FLD corpora. You can either use a logical-reasoning framework [LogiTorch/logitorch](https://github.com/LogiTorch/logitorch), or [our training scripts](https://github.com/hitachi-nlp/FLD-prover/).
* You can generate corpora with your own setting using [our corpus generator](https://github.com/hitachi-nlp/FLD-generator/).

## Publications

### International Coneferences
* "Enhancing Reasoning Capabilities of LLMs via Principled Synthetic Logic Corpus", NeurIPS, 2024 (TBD)
* ["JFLD: A Japanese Benchmark for Deductive Reasoning Based on Formal Logic", LREC-COLING, 2024](https://aclanthology.org/2024.lrec-main.832/)
* ["Learning Deductive Reasoning from Synthetic Corpus based on Formal Logic", ICML, 2023](https://arxiv.org/abs/2308.07336)

### Domestic Conferences (Japanese only)
* [「帰納的に多様な巨大論理推論コーパスによりLLMの汎用論理推論能力を向上させる」, 人工知能学会, 2024](https://confit.atlas.jp/guide/event-img/jsai2024/3Xin2-64/public/pdf?type=in)
* [「日本語論理推論ベンチマークJFLDの提案」, 言語処理学会, 2024](https://www.anlp.jp/proceedings/annual_meeting/2024/pdf_dir/A4-1.pdf)
* [「言語モデルの論理推論能力を大きく改善、日立が学習用コーパスの自動生成技術」, 日経ロボティクス, 2024/01](https://xtech.nikkei.com/atcl/nxt/mag/rob/18/012600001/00136)
* [「人工演繹推論コーパスによる学習は言語モデルをどのように強化するか？」, 人工知能学会, 2023](https://www.jstage.jst.go.jp/article/pjsai/JSAI2023/0/JSAI2023_2E5GS605/_pdf)
* [「形式論理学に基づく演繹コーパスによる言語モデルに対する演繹推論能力の付与」, 言語処理学会, 2023](https://www.anlp.jp/proceedings/annual_meeting/2023/pdf_dir/B1-2.pdf)

## Contact
For any reason where a GitHub pull request or an issue is not appropriate, feel free to email terufumi.morishita.wp[at]hitachi.com.

## Citation
```bibtex
@inproceedings{morishita_2024_NeurIPS_FLD_diverse,
  title={Enhancing Reasoning Capabilities of LLMs via Principled Synthetic Logic Corpus}, 
  author={Terufumi Morishita and Gaku Morio and Atsuki Yamaguchi and Yasuhiro Sogawa},
  booktitle={Annual Conference on Neural Information Processing Systems},
  year={2024}
}

@inproceedings{morishita2024jfld,
  title = {JFLD: A Japanese Benchmark for Deductive Reasoning based on Formal Logic},
  author = {Morishita, Terufumi and Yamaguchi, Atsuki and Morio, Gaku and Hikaru, Tomonari and Osamu Imaichi and Sogawa, Yasuhiro},
  booktitle = {Proceedings of the Joint International Conference on Computational Linguistics, Language Resources and Evaluation},
  year = {2024}
}

@inproceedings{morishita2023fld,
  title = {Learning Deductive Reasoning from Synthetic Corpus based on Formal Logic},
  author = {Morishita, Terufumi and Morio, Gaku and Yamaguchi, Atsuki and Sogawa, Yasuhiro},
  booktitle = {Proceedings of the 40th International Conference on Machine Learning},
  year = {2023}
}
```
