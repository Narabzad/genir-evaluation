These pickle files include the validation experiments of qrels from different relevance levels using embeddings. 
Please load them in python like this in a dictionary:

```
improt pickle

with open('embeddings/emb_results_2019_gpt-3.5-turbo.pickle', 'rb') as handle:
    embeddding_2019_gpt3_dict = pickle.load(handle)
```
