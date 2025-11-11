# Gretel Synthetic Safety Alignment Dataset Benchmark in Spanish

This benchmark is based on the gretel-safety-alignment-es-v1 dataset, which is a synthetically generated and machine-translated collection of prompt-response-safe_response triplets that can be used for aligning language models. Created using Gretel Navigator's AI Data Designer using small language models like ibm-granite/granite-3.0-8b, ibm-granite/granite-3.0-8b-instruct, Qwen/Qwen2.5-7B, Qwen/Qwen2.5-7B-instruct and mistralai/Mistral-Nemo-Instruct-2407. Then translated to Spanish using gpt-4o-mini-2024-07-18 and mistralai/mistral-small-3.2-24b-instruct.


### Citation

```text
@dataset{latam-gpt_gretel-safety-alignment-es-v1,
    title = {Gretel Synthetic Safety Alignment Dataset in Spanish},
    year = {2025},
    month = {8},
    author = {latam-gpt},
    url = {https://huggingface.co/datasets/latam-gpt/gretel-safety-alignment-es-v1},
}
```

### Groups, Tags, and Tasks

#### Groups

* `gretel-safety-alignment-es`: `Contains all tasks. Each task is a collection of prompt-response-safe_response triplets from a specific risk category.`

#### Tasks

* `gretel-safety-alignment-es-discrimination`: `prompt-response-safe_response triplets for the discrimination risk category.`
* `gretel-safety-alignment-es-information-hazards`: `prompt-response-safe_response triplets for the information hazards risk category.`
* `gretel-safety-alignment-es-malicious-use`: `prompt-response-safe_response triplets for the malicious use risk category.`
* `gretel-safety-alignment-es-societal-risks`: `prompt-response-safe_response triplets for the societal risks risk category.`
* `gretel-safety-alignment-es-system-risks`: `prompt-response-safe_response triplets for the systemic risks risk category.`

### Checklist

For adding novel benchmarks/datasets to the library:

* [ ] Is the task an existing benchmark in the literature?
  * [ ] Have you referenced the original paper that introduced the task?
  * [ ] If yes, does the original paper provide a reference implementation? If so, have you checked against the reference implementation and documented how to run such a test?

If other tasks on this dataset are already supported:

* [ ] Is the "Main" variant of this task clearly denoted?
* [ ] Have you provided a short sentence in a README on what each new variant adds / evaluates?
* [ ] Have you noted which, if any, published evaluation setups are matched by this variant?

### Changelog
