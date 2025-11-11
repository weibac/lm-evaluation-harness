# Gretel Synthetic Safety Alignment Dataset Benchmark

This benchmark is based on the gretel-safety-alignment-en-v1 dataset, which is a synthetically generated collection of prompt-response-safe_response triplets that can be used for aligning language models. Created using Gretel Navigator's AI Data Designer using small language models like ibm-granite/granite-3.0-8b, ibm-granite/granite-3.0-8b-instruct, Qwen/Qwen2.5-7B, Qwen/Qwen2.5-7B-instruct and mistralai/Mistral-Nemo-Instruct-2407. 


### Citation

```text
@dataset{gretelai_gretel-safety-alignment-en-v1,
    title = {Gretel Synthetic Safety Alignment Dataset},
    year = {2024},
    month = {12},
    publisher = {Gretel},
    url = {https://huggingface.co/datasets/gretelai/gretel-safety-alignment-en-v1}
}
```

### Groups, Tags, and Tasks

#### Groups

* `gretel-safety-alignment-en`: `Contains all tasks. Each task is a collection of prompt-response-safe_response triplets from a specific risk category.`

#### Tasks

* `gretel-safety-alignment-en-discrimination`: `prompt-response-safe_response triplets for the discrimination risk category.`
* `gretel-safety-alignment-en-information-hazards`: `prompt-response-safe_response triplets for the information hazards risk category.`
* `gretel-safety-alignment-en-malicious-use`: `prompt-response-safe_response triplets for the malicious use risk category.`
* `gretel-safety-alignment-en-societal-risks`: `prompt-response-safe_response triplets for the societal risks risk category.`
* `gretel-safety-alignment-en-system-risks`: `prompt-response-safe_response triplets for the systemic risks risk category.`

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
