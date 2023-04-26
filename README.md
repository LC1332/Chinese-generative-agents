# LuotuoRPG: Generative Agents的中文版本

原项目名: Generative Large Language Models for Human-Like Behavior

LuotuoRPG 是由李鲁鲁开发的Generative Agents的中文版本。

This repository includes a working Chinese version of the type of model described in Generative Agents: Interactive Simulacra of Human Behavior.

骆驼RPG是[Luotuo(骆驼)](https://github.com/LC1332/Luotuo-Chinese-LLM)的子项目之一，后者由李鲁鲁，冷子昂，陈启源发起。


## Quickstart

你需要一个openAI的API token来运行这个代码


|  | Colab链接 | 细节 |
| --- | --- | :--- |
| 同福客栈 | <a href="https://colab.research.google.com/github/LC1332/Chinese-generative-agents/blob/main/notebook/Chinese_story_turbo.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> | 将故事替换为同福客栈的版本 |
| 命令行版本 | <a href="https://colab.research.google.com/github/LC1332/Chinese-generative-agents/blob/main/notebook/Chinese_generative_model_turbo.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> | 暂时实现了命令行的版本 |


## Demo Video



https://user-images.githubusercontent.com/5266090/234726234-79342279-746c-4226-8a90-10bc58d8fe79.mov


## 运行效果

人物目标

```
佟湘玉 我的目标是扩大同福客栈的业务，提高知名度，吸引更多客人，赚取更多利润。
李大嘴 我的目标是在同福食堂谋生，打工赚钱，为自己未来的发展打下基础。
白展堂 我的目标是调查七侠镇最近的盗窃案件并保护佟湘玉的安全。
邢捕头 我的目标是调查七侠镇的治安情况，捉拿罪犯，确保居民安全。
姬无命 我的目标是在七侠镇盗窃贵重物品，保持低调，避免被捕。
钱掌柜 我的目标是经营好万利钱庄，避免被欺负和损失，同时避免招惹任何麻烦和纷争，维护好家庭和生意。
钱夫人 我的目标是监管万利当铺的生意，确保钱掌柜的利益不受影响。
日月神教小毛贼 我的目标是找到日月神教小毛贼并将其绳之以法。
```

这里反派比较糟糕，会收到turbo3.5的道德偏好的影响。

七侠镇的一天

```
佟湘玉 七侠镇大街 9 我会与佟湘玉商量如何提升我们的客栈知名度，与白展堂交流我们的安全防范措施，向邢捕头了解情报，向钱掌柜洽谈合作，但要提防被他坑骗，尽量避免接触日月神教小毛贼。同时，我会观察人流，了解我们的竞争对手和客栈声誉。
李大嘴 同福食堂 9 我将继续在同福食堂工作，准备材料，烹饪美食，为顾客提供优质服务，并确保卫生安全。
白展堂 七侠镇大街 9 我会先与邢捕头交流，了解当前盗窃案件的细节，并寻求他的合作。然后，我会与佟湘玉和钱掌柜谈话，了解钱夫人的商业活动是否与盗窃案件有关，同时保护佟湘玉的安全。如果日月神教小毛贼出现在同福客栈，我会立即阻止他们的行动。最后，我会着手调查盗窃案件并采取措施保护七侠镇的安全。
邢捕头 七侠镇大街 9 我会先和佟湘玉聊聊，了解我对七侠镇治安的看法。然后，我会和白展堂交流，询问我对于七侠镇的治安问题是否有了解，同时监视他的行踪。接着，我会在钱掌柜那里收集关于日月神教小毛贼的情报。最后，我会到七侠镇的边界巡逻，以确保七侠镇的居民安全。
姬无命 客栈的屋顶 9 我会继续静待在客栈的屋顶，观察周围情况，注意避开钱掌柜和邢捕头的巡逻。我会尝试与佟湘玉和白展堂交流，获取更多关于贵重物品情报。如果有必要，我会继续躲藏在客栈附近，等待适当的时间进行盗窃行动。
钱掌柜 七侠镇大街 9 我会尽快赶回万利钱庄，确保钱庄的安全和正常运营。在路上我会尽量避免与邢捕头和日月神教小毛贼有任何互动，以免招惹麻烦。如果遇到白展堂，我会礼貌地与他打招呼，并保持距离。与佟湘玉的互动会基于业务沟通为主，避免涉及到个人感情等敏感话题。
钱夫人 客栈的屋顶 9 我会继续观察市场需求，并留意小毛贼的行为。如果有需要，我会联系警察局了解镇上的警情信息。同时，我会确保自己的安全，避免和姬无命接触。
日月神教小毛贼 七侠镇大街 9 我要与钱掌柜和邢捕头互动，了解是否有关于日月神教小毛贼的线索，并且留意白展堂和佟湘玉的动向。如果没有获得有用信息，我会继续在七侠镇大街巡查，寻找其他可以提供线索的人或物。同时，我会小心谨慎，避免惊动日月神教小毛贼。
    - Emoji Representation: 佟湘玉 七侠镇大街 9 ((商量, 佟湘玉), (交流, 白展堂), (了解, 邢捕头), (洽谈, 钱掌柜), (观察, 人流))
    - Emoji Representation: 李大嘴 同福食堂 9 ((工作, 同福食堂), (准备, 材料), (烹饪, 美食), (为, 顾客), (提供, 优质服务), (确保, 卫生安全))
    - Emoji Representation: 白展堂 七侠镇大街 9 (与邢捕头交流, 当前盗窃案件的细节)
(寻求邢捕头的合作, None)
(与佟湘玉和钱掌柜谈话, 了解钱夫人的商业活动是否与盗窃案件有关)
(保护佟湘玉的安全, None)
(阻止日月神教小毛贼的行动, None)
(调查盗窃案件, None)
(采取措施保护七侠镇的安全, None)
```

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
- [ ] add WIP emoji

# How to Use

本项目基于generative agents的一个[简易实现](https://github.com/mkturkcan/generative-agents)修改而来



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
