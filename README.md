# Generative Large Language Models for Human-Like Behavior
# LuotuoRPG: Generative Agents的中文版本

LuotuoRPG 是由李鲁鲁开发的Generative Agents的中文版本。

This repository includes a working Chinese version of the type of model described in Generative Agents: Interactive Simulacra of Human Behavior.

## Quickstart

因为免费的模型还没有支持中文，我把接口替换成了openAI的。

你需要一个openAI的API token来运行这个代码

colab链接

## TODO

- [x] Translate prompt and runing in Chinese
- [ ] Add a colab link on page
- [ ] Add a Chinese-culture story
- [ ] Add a 3.5 turbo version (if it's possible)
- [ ] A Gradio Interface


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