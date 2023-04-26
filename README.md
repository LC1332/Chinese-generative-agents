# LuotuoRPG: Generative Agents的中文版本

原项目名: Generative Large Language Models for Human-Like Behavior

LuotuoRPG 是由李鲁鲁开发的Generative Agents的中文版本。

This repository includes a working Chinese version of the type of model described in Generative Agents: Interactive Simulacra of Human Behavior.

骆驼RPG是[Luotuo(骆驼)](https://github.com/LC1332/Luotuo-Chinese-LLM)的子项目之一，后者由李鲁鲁，冷子昂，陈启源发起。


## Quickstart

你需要一个openAI的API token来运行这个代码


|  | Colab链接 | 细节 |
| --- | --- | :--- |
| 命令行版本 | <a href="https://colab.research.google.com/github/LC1332/Chinese-generative-agents/blob/main/notebook/Chinese_generative_model_turbo.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> | 暂时实现了命令行的版本 |






## TODO

- [x] Translate prompt and runing in Chinese
- [x] Add a colab link on page
- [ ] demo video
- [ ] Add a Chinese-culture story
- [ ] demo video2
- [x] Add a 3.5 turbo version (if it's possible)
- [ ] A Gradio Interface
- [ ] (opt) Message Queue parall request
- [ ] build En and Ch page individiually

# How to Use

* The most stable model is available at https://github.com/mkturkcan/generative-agents/tree/main/notebook/Release.
* WIP models with the latest features will be available in https://github.com/mkturkcan/generative-agents/tree/main/notebook/WIP.
* A WIP library is available under https://github.com/mkturkcan/generative-agents/tree/main/game_simulation.

## Model

The current model is a simulation of the town of Phandalin from an introductory D&D 5e adventure. This setting is chosen as it is much more free form than the simple scenario described in the original paper.

## Limitations

The model, as described in the paper, requires access to a very high quality instruction model such as GPT-3. However, the model also requires many high-context queries to work, making it expensive to run. As such, in this work we use low-parameter, locally runnable models instead. 

We expect that with the advent of the next generation of instruction-tuned models, the model in this repo will perform better.

## Future Steps

* Summarize agent decisions as emojis. (WIP)
* Create a family of questions to compress agent contexts better.
* Check if the agent contexts are compressed well with an another layer of prompts.