# A Comparison of Methods for Evaluating Generative IR
In this repository we include the prompts, codes and generated responses for the paper "A Comparison of Methods for Evaluating Generative IR".

``Prompts`` includes all the prmopts we used for our experiments.

``generated responses`` directory includes all the regular generated responses as well as liar responses we used for our experiments by four different LLMS including:
- gpt-4
- gpt-3.5-turbo
- llama2 7b chat
- llama2 13b chat LLMs.

`data` includes the queries and relevance judgements used for our experiments from Trec DL 2019 and Trec DL 2020. 

`genir experiments` include the results in evaluating LLM generated responses using 5 different evaluation methods described in the paper. 

`Validations` include the resuls of compaing qrels from different level of relevance in TREC dl 2019 and 2020.

The results for experiments conducted in Section 3 and 4 can be found under `Validations` and ``Genir experiments`` respectively.
