# reversal_curse
I fine-tune Transformers architectures, to test the claim that models trained on A is B, fail to give B is A answers.

The authors of the paper "The Reversal Curse: LLMs trained on 'A is B' fail to learn 'B is A '" claim that LLM has a suprising failure of generalization. I test the claim using a simple experiment, based on the following argument:

“If a model is trained on a sentence of the form “A is B”, it will not automatically generalize to the reverse direction “B is A””, is true then I shouldn’t be able to train a model with A is B examples and get B is A answers.

Paper here: https://arxiv.org/pdf/2309.12288.pdf
