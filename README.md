<!-- omit in toc -->

# awesome-instruction-tunning-datasets [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A collection of AWESOME datasets for instruction tuning.

There is a trend of improving LLM (large language models) by fine-tuning with instructions. As **data-centric AI** is becoming more and more popular, we need better quality datasets to train our models. This repository is a collection of datasets for instruction tuning.

Note that dataset generated by calling OpenAI API cannot be used to develop models that compete with OpenAI due to OpenAI's [terms of use](https://openai.com/policies/terms-of-use) 2(c)(iii).

An awesome list of foundation models can be found [here](https://github.com/zhengzangw/awesome-huge-models).

## Datasets

- [Alpaca Dataset](https://github.com/tatsu-lab/stanford_alpaca)

  ```yaml
  Size: 52K (English)
  Source: self-instruct from 175 seed instructions by OpenAI API
  Cost: less than US$ 500
  License: CC By NC 4.0; OpenAI terms of use
  ```

- [InstructionWild](https://github.com/XueFuzhao/InstructionWild)

  ```yaml
  Size: 104K (English, Chinese)
  Source: self-instruct from 429 seed instructions collected from the Internet
  Cost: US$ 880
  License: Research only; OpenAI terms of use
  ```

- [Guanaco Dataset](https://huggingface.co/datasets/JosephusCheung/GuanacoDataset)

  Self-instruct dataset

  ```yaml
  Size: 98K (English, Simplified Chinese, Traditional Chinese HK & TW, Janpanese)
  Source: self-instruct from 175 translated seed instructions of Alpaca Dataset
  Cost: US$ 6K
  License: GPL-3.0; OpenAI terms of use
  ```

  Chat dataset

  ```yaml
  Size: 49K
  ```

  Close-QA: give a passage and a question, generate the answer.

  ```yaml
  Size: 99K
  ```

  Close-Question: give a passage, raise proper questions.

  ```yaml
  Size: 107K
  ```

- [BELLE](https://github.com/LianjiaTech/BELLE)

  Self-instruct dataset

  ```yaml
  Size: 1.5M (Chinese)
  Source: self-instruct from 175 translated seed instructions of Alpaca Dataset
  License: Research only; OpenAI terms of use
  ```

  Math dataset

  ```yaml
  Size: 250K (Chinese)
  ```

  Multi-turn chat dataset

  ```yaml
  Size: 800K (Chinese)
  ```

- [Alpaca-CoT Dataset](https://github.com/PhoebusSi/Alpaca-CoT)

  ```yaml
  Size: 75K
  Source: FLAN Chain-of-Thought dataset
  ```

- [OIG-43M Dataset](https://huggingface.co/datasets/laion/OIG) [[preprocess]](https://github.com/togethercomputer/OpenChatKit)

  ```yaml
  Size: 43M
  Source: Collected by Together, LAION, and Ontocord.ai.
  ```

- [GPT4All Dataset](https://github.com/nomic-ai/gpt4all)

  ```yaml
  Size: 806K
  Source: filtered from subset of LAION OIG, StackOverflow Question, BigSciense/p3 dataset. Answered by OpenAI API.
  ```

- [Camel Dataset](https://github.com/lightaime/camel)

  Chat dataset

  ```yaml
  Size: 107K
  Source: role-playing between AIs (Open AI API)
  ```

- <s>[Vicuna Dataset](https://github.com/lm-sys/FastChat)</s>

  ```yaml
  Size: 75K (Unavailable due to privacy concern)
  Source: ShareGPT
  ```

## Derivative Datasets

- [Cabrita Dataset](https://github.com/22-hours/cabrita)

  ```yaml
  Size: 52K (Portuguese)
  Source: translated from Alpaca Data
  Cost: US$ 8
  License: CC By NC 4.0; OpenAI terms of use
  ```

- [Japanese Alpaca Dataset](https://github.com/masa3141/japanese-alpaca-lora)

  ```yaml
  Size: 52K (Japanese)
  Source: translated from Alpaca Data by ChatGPT API.
  Cost: US$ 45
  License: CC By NC 4.0; OpenAI terms of use
  ```

- [Chinese Alpaca Dataset](https://github.com/LC1332/Chinese-alpaca-lora)

  ```yaml
  Size: 52K (Chinese)
  Source: translated from Alpaca Data by ChatGPT API.
  Cost: US$ 30-45
  License: CC By NC 4.0; OpenAI terms of use
  ```

- [Alpaca Chinese Dataset](https://github.com/hikariming/alpaca_chinese_dataset)

  ```yaml
  Size: 52K (Chinese)
  Source: translated from Alpaca Data by ChatGPT API.
  Cost: Volunteer
  License: CC By NC 4.0; OpenAI terms of use
  ```
