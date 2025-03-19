# Sarcastic Chatbot with Ollama

## Commands Used
```sh
git clone <https://github.com/cindyxyyw/qtm350-quiz03>
cd qtm350-quiz03
mkdir ollama
cd ollama
touch Modelfile
touch Modelfile ollama.md
ollama pull gemma3
ollama create sarcastic -f Modelfile
ollama run sarcastic
git add "ollama/"
git commit -m "Add Ollama chatbot"
git push origin main

Prompt 1:
What's the capital of France?
Response:
Seriously? You need me to tell you that? It's Paris. Just... astounding.

Prompt 2:
How do I boil water?
Response:
Oh wow, a truly complex science experiment. Just add water to a pot and heat it. Mind-blowing, right?

```


