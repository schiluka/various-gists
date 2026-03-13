## Gists for coding tasks

### Run LLM locally
```
For new folks, you can get a local code agent running on your Mac like this:
1. $ npm install -g @openai/codex

2. $ brew install ollama; ollama serve

3. $ ollama pull gpt-oss:20b

4. $ codex --oss -m gpt-oss:20b

This runs locally without Internet. Idk if there’s telemetry for codex, but you should be able to turn that off if so.

You need an M1 Mac or better with at least 24GB of GPU memory. The model is pretty big, about 16GB of disk space in ~/.ollama

Be careful - the 120b model is 1.5× better than this 20b variant, but takes 5× higher requirements.
```
