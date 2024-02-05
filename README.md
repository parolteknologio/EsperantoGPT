# EsperantoGPT
This is a project to create a custom Esperanto GPT for ChatGPT and similar systems that has knowledge about Esperanto culture, is better at teaching Esperanto and can access specific resources such as the PIV.

ChatGPT:
* Test it here: https://chat.openai.com/g/g-D4jB3Ml4b-esperanto-helpanto
* More on curstom GPTs: https://openai.com/blog/introducing-gpts

Huggingface Chat Assistant (still very experimental)
* Test it here: https://hf.co/chat/assistant/65c145c565be046e86ee130f
* Only supports [one system prompt](https://github.com/parolteknologio/EsperantoGPT/blob/main/HuggingChatSystemPrompt.md) and no knowledge files right now. 

Plan:
* create a structure to organize the files ✅
* create first versions of the most important files ✅
* refine the information over time 🚧
* become multilingual?

Feel free to join the disscussion and to improve the files! Ni ĉiam ĝojas pri helpantoj!

# Instructions
The [Instructions](https://github.com/parolteknologio/EsperantoGPT/blob/main/Instructions.md) field defines the general behaviour of the Assistant.

* Todo: experiemtn with more knowledge here


# Knowledge

External files:
* The PDF of the [PMEG](https://bertilow.com/pmeg/elshutebla/pmeg_15.2.pdf)  (CC BY-SA 4.0)
* The xdxf file export of the [REVO dictionary](https://github.com/revuloj/revo-fonto/releases) (GPL2) curently removed again see [#1](https://github.com/parolteknologio/EsperantoGPT/issues/1)
* [Esperanto Etymological Dictionary](https://github.com/parolteknologio/EsperantoGPT/blob/main/knowledge/Esperanto%20Etymological%20Dictionary.txt) by András Rajki (CC0)

Manually created files (todo):
* [Culture](https://github.com/parolteknologio/EsperantoGPT/blob/main/knowledge/Culture.md)
* [History](https://github.com/parolteknologio/EsperantoGPT/blob/main/knowledge/History.md)
* [Language](https://github.com/parolteknologio/EsperantoGPT/blob/main/knowledge/Language.md)
* [Learning](https://github.com/parolteknologio/EsperantoGPT/blob/main/knowledge/Learning.md)
* [Sources](https://github.com/parolteknologio/EsperantoGPT/blob/main/knowledge/Sources.md)
* [Technology](https://github.com/parolteknologio/EsperantoGPT/blob/main/knowledge/Technology.md)

# Actions:
* OpenAI documentation: https://platform.openai.com/docs/actions/what-is-an-action
* For more details and more experimental actions see [actions/README.md](https://github.com/parolteknologio/EsperantoGPT/blob/main/actions/README.md)

Right now the GPT supports these actions:
* Search in the PIV: https://github.com/parolteknologio/EsperantoGPT/blob/main/actions/piv-ai.json

I am always looking for ideas for aditional actions!

# Notoj
Eblaj fontoj:
* Duolingo Esperanto mega post: https://gist.github.com/c4software/d7d9693b693c7f3f07d49e1a4cfd5272#file-esperanto-megapost-md
* Esperantaj kodprojektoj: https://github.com/Esperanto/projektoj
