# Reservoir_lag_gradient
This contains code and data for generating ERD reservoir activations for investigating narrative lag gradients
This allows the generation of the reservoir activations that are used for measuring the lag gradient.
A few notes:
1. to run easyesn and have access to the internal reservoir states, there is a change to make:  see this message
https://github.com/kalekiu/easyesn/issues/12

2.  to train the reservoir, please use the files in_small.npy and out_small.npy available here 
    Narrative-Integration-Reservoir/in_small.npy, out_small.npy
3. to get the embeddings for wikipedia2vec
https://huggingface.co/jinmang2/dooly-hub/blob/0fcf5b24ba3748253300579ecaac0de546aec668/word_embedding/en/wikipedia2vec.en/enwiki_20180420_100d.pkl
