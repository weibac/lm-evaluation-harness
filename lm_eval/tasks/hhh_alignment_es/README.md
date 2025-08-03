# hhh_alignment_es

hhh_alignment_es (Helpful, Honest, & Harmless - a Pragmatic Alignment Evaluation - Spanish) is a question answering dataset in Spanish, professionally translated from the main version of the [hhh_alignment](https://huggingface.co/datasets/HuggingFaceH4/hhh_alignment) dataset in English. It is designed to evaluate language models on alignment, pragmatically broken down into the categories of helpfulness, honesty/accuracy, harmlessness, and other. The dataset comprises 61 honesty, 59 helpfulness, 58 harm, and 43 other categorized instances. Each instance contains an input prompt with two possible target answers.

- **Curated by:** [Language Technologies Unit | BSC-CNS](https://www.bsc.es/discover-bsc/organisation/research-departments/language-technologies-unit)
- **Funded by:** [ILENIA](https://proyectoilenia.es/en/)
- **Language(s) (NLP):** Spanish (`es-ES`)
- **License:** [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/deed) ([Original](https://huggingface.co/datasets/HuggingFaceH4/hhh_alignment)) **

### Groups, Tags, and Tasks

#### Groups

* `hhh_alignment_es`: `The full hhh_alignment_es benchmark`

#### Tasks

* `hhh_alignment_es_harmless`: `harmless subset of the hhh_alignment_es prompt dataset`
* `hhh_alignment_es_helpful`:  `helpful subset of the hhh_alignment_es prompt dataset`
* `hhh_alignment_es_honest`:  `honest subset of the hhh_alignment_es prompt dataset`
* `hhh_alignment_es_other`:  `other subset of the hhh_alignment_es prompt dataset`

### Citation (for the original english dataset paper)

```text
@article{DBLP:journals/corr/abs-2112-00861,
  author    = {Amanda Askell and
               Yuntao Bai and
               Anna Chen and
               Dawn Drain and
               Deep Ganguli and
               Tom Henighan and
               Andy Jones and
               Nicholas Joseph and
               Benjamin Mann and
               Nova DasSarma and
               Nelson Elhage and
               Zac Hatfield{-}Dodds and
               Danny Hernandez and
               Jackson Kernion and
               Kamal Ndousse and
               Catherine Olsson and
               Dario Amodei and
               Tom B. Brown and
               Jack Clark and
               Sam McCandlish and
               Chris Olah and
               Jared Kaplan},
  title     = {A General Language Assistant as a Laboratory for Alignment},
  journal   = {CoRR},
  volume    = {abs/2112.00861},
  year      = {2021},
  url       = {https://arxiv.org/abs/2112.00861},
  eprinttype = {arXiv},
  eprint    = {2112.00861},
  timestamp = {Tue, 07 Dec 2021 12:15:54 +0100},
  biburl    = {https://dblp.org/rec/journals/corr/abs-2112-00861.bib},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```

### Checklist

For adding novel benchmarks/datasets to the library:

* [x] Is the task an existing benchmark in the literature?
  * [x] Have you referenced the original paper that introduced the task?
  * [ ] If yes, does the original paper provide a reference implementation? If so, have you checked against the reference implementation and documented how to run such a test?

If other tasks on this dataset are already supported:

* [ ] Is the "Main" variant of this task clearly denoted?
* [ ] Have you provided a short sentence in a README on what each new variant adds / evaluates?
* [ ] Have you noted which, if any, published evaluation setups are matched by this variant?

### Changelog

2025-08-03: Initial version.
