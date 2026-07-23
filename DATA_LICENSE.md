# Data License

This file documents the license status for the released Annoy-DataSync datasets by reusing the license information from the datasets' direct data source and the model used for synthesis. No new license is introduced here.

## Annoy-PythonEdu-Rs and Annoy-PythonEdu-Rs-Raw

`Annoy-PythonEdu-Rs` and `Annoy-PythonEdu-Rs-Raw` are derived from the Python-Edu subset of [HuggingFaceTB/smollm-corpus](https://huggingface.co/datasets/HuggingFaceTB/smollm-corpus). The `HuggingFaceTB/smollm-corpus` dataset card declares:

```yaml
license: odc-by
```

Accordingly, the released Annoy PythonEdu datasets use the same direct upstream data-source license: [Open Data Commons Attribution License (ODC-BY 1.0)](https://opendatacommons.org/licenses/by/1-0/).

## Synthesis model

The natural-language transformations/reasoning traces were synthesized with [DeepSeek-V2.5](https://huggingface.co/deepseek-ai/DeepSeek-V2.5), whose model card links to the [DeepSeek License Agreement](https://github.com/deepseek-ai/DeepSeek-V2/blob/main/LICENSE-MODEL). Section 6 of that license states that DeepSeek claims no rights in model outputs, subject to the license terms and lawful use.

Therefore, we do not apply a newly invented license to the synthesized outputs. The dataset release follows the direct data-source license above, while use of the synthesis model itself is governed by the DeepSeek License Agreement.

## Underlying source-code content

The Python-Edu subset traces back to [The Stack v2](https://huggingface.co/datasets/bigcode/the-stack-v2-train-full-ids), where source files come from repositories with different original licenses. Any use of raw or processed source-code-derived content must also comply with the applicable original repository licenses, including attribution and notice requirements where relevant. Please refer to upstream provenance metadata and The Stack v2 documentation for license details for individual source files.

## Summary

- Annoy-PythonEdu-Rs / Annoy-PythonEdu-Rs-Raw dataset release: ODC-BY 1.0, reused from the direct upstream data source `HuggingFaceTB/smollm-corpus`.
- Model used for synthesis: DeepSeek-V2.5 under the DeepSeek License Agreement; DeepSeek's license says it claims no rights in outputs.
- Underlying source-code-derived content: also subject to original source repository licenses surfaced through The Stack v2 provenance metadata.

## Upstream references

- HuggingFaceTB/smollm-corpus: https://huggingface.co/datasets/HuggingFaceTB/smollm-corpus
- DeepSeek-V2.5: https://huggingface.co/deepseek-ai/DeepSeek-V2.5
- DeepSeek License Agreement: https://github.com/deepseek-ai/DeepSeek-V2/blob/main/LICENSE-MODEL
- The Stack v2 train full IDs: https://huggingface.co/datasets/bigcode/the-stack-v2-train-full-ids
- ODC-BY 1.0: https://opendatacommons.org/licenses/by/1-0/
