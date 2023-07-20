# A Human Annotated Dataset for the Quality Assessment of Emotion Translation (HADQAET) for Chinese-English Machine Translation


This repository contains the HADQAET Dataset in our paper submitted to EAMT 2023. For details of the dataset, please see our paper [*Evaluation of Chinese-English Machine Translation of Emotion-Loaded Microblog Texts: A Human Annotated Dataset for the Quality Assessment of Emotion Translation*](https://events.tuni.fi/uploads/2023/06/11678752-proceedings-eamt2023.pdf) or [at arXiv](https://arxiv.org/abs/2306.11900). To use the dataset, please see our [License](#license). 


## Citation

- Shenbin Qian, Constantin Orăsan, Félix do Carmo, Qiuliang Li and Diptesh Kanojia. 2023. Evaluation of Chinese-English Machine Translation of Emotion-Loaded Microblog Texts: A Human Annotated Dataset for the Quality Assessment of Emotion Translation. In *Proceedings of the 24th Annual Conference of the European Association of Machine Translation*, Finland, Tempere. European Association for Machine Translation.

```
@inproceedings{qian2023,
    title = "Evaluation of Chinese-English Machine Translation of Emotion-Loaded Microblog Texts: A Human Annotated Dataset for the Quality Assessment of Emotion Translation.",
    author = "Qian, Shenbin  and
      Orasan, Constantin  and
      Félix do Carmo  and
      Qiuliang Li  and
      Diptesh Kanojia",
    booktitle = "Proceedings of the 24th Annual Conference of the European Association of Machine Translation",
    month = june,
    year = "2023",
    address = "Tampere, Finland",
    publisher = "European Association for Machine Translation",
    abstract = "In this paper, we focus on how current Machine Translation (MT) tools perform on the translation of emotion-loaded texts by evaluating outputs from Google Translate according to a framework proposed in this paper. We propose this evaluation framework based on the Multidimensional Quality Metrics (MQM) and perform a detailed error analysis of the MT outputs. From our analysis, we observe that about 50% of the MT outputs fail to preserve the original emotion. After further analysis of the errors, we find that emotion carrying words and linguistic phenomena such as polysemous words, negation, abbreviation etc., are common causes for these translation errors.",
}
```


## Data

The annotated dataset for the quality assessment of emotion translation can be found in the "data" folder. The inter and intra-annotator agreement data can be seen under the "IAA" folder. Detailed annotation guidelines can be seen in the "annotation_guidelines.txt" file.


## License

This resource is built on top of the dataset in the [SMP2020-EWECT shared task](https://smp2020ewect.github.io/), provided by the [Social Computing and Information Retrieval Research Center of Harbin Institute of Technology](http://ir.hit.edu.cn/) and sourced from [Sina Weibo](https://weibo.com/). The MT output was generated from [Google Translate](https://translate.google.co.uk/) on the 30th of May, 2022, and distributed under the [Terms of Service](https://policies.google.com/terms?hl=en-US) of Google.

Though the SMP2020-EWECT dataset does not have license information, the distribution of the public content of Sina Weibo needs to follow its [Terms of Service (Clause 1.3)](https://m.weibo.cn/c/regagreement?from=h5), which allows itself and developers to use and distribute any published posts including texts, pictures or videos etc. The source text of this dataset, hence, remains under Sina Weibo's [developer license](https://open.weibo.com/wiki/%E5%BC%80%E5%8F%91%E8%80%85%E5%8D%8F%E8%AE%AE).

To use this dataset also needs to cite our paper. 
