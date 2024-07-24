# Evals for multi-turn dialogue

Aim of this repository is to create evals for multi-turn dialogues, using [AISI's Inspect open source framework](https://ukgovernmentbeis.github.io/inspect_ai/).
If you know nothing about Inspect, I wrote a [beginner's guide](https://lovkush.medium.com/evaluating-llms-using-uk-ai-safety-institutes-inspect-framework-96435c9352f3) going through their hello world example.
You can also just read their documentation.

## Repository structure
- `multi_dialogues.ipynb`. Main file for this repository which contains example eval workflow.
- `question.jsonl`. Example dialogue evals copied from [MT Bench](https://github.com/lm-sys/FastChat/blob/main/fastchat/llm_judge/data/mt_bench/question.jsonl).
- `.gitignore`, `LICENSE`, `README.md` - standard files for a github repo.

## Contributions
Issues or pull requests are welcome.
Also happy to hear from people who want to collaborate to flesh out the toy example to make this more reusable and flexible.
