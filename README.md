# Vocabulary evaluation of LLMs


This repository contains the results for the different vocabulary tests run on LLM tools/models presented in the paper: **"The continued usefulness of vocabulary tests for evaluating large language models"** currently published a preprint in arXiv: https://arxiv.org/abs/2310.14703


The name of the files correspond to the vocabulary tests for which results are presented in Tables 3-6 in the paper (note that questions for the TOEFL test are not public).  

In each file, the first column has the question posed to the LLM tool/model, followed by the correct answer. The rest of the columns correspond to the answers of the different LLM tools/models evaluated.  The results and percentages are summarized at the bottom of the file after the last test items.

The models evaluated are:
| Model                 | Link                                                                                                          |
|-------------------------|---------------------------------------------------------------------------------------------------------------|
| Llama 2 7b              | [Link](https://huggingface.co/meta-llama/Llama-2-7b-chat)                                                     |
| Llama 2 13b             | [Link](https://huggingface.co/meta-llama/Llama-2-13b-chat)                                                    |
| Llama 2 70b             | [Link](https://huggingface.co/meta-llama/Llama-2-70b-chat)                                                    |
| Mistral 7b v0.1         | [Link](https://huggingface.co/mistralai/Mistral-7B-v0.1)                                                      |
| GPT 3.5 turbo 0613      | [Link](https://platform.openai.com/docs/models/gpt-3-5-turbo)                                                      |
| GPT 4 0613              | [Link](https://platform.openai.com/docs/models/gpt-4-turbo-and-gpt-4)                                                              |
| Bard                    |                                                                                                               |


To cite our work:

```
@article{martinez2023continued,
  title={The continued usefulness of vocabulary tests for evaluating large language models},
  author={Mart{\'\i}nez, Gonzalo and Conde, Javier and Merino-G{\'o}mez, Elena and Berm{\'u}dez-Margaretto, Beatriz and Hern{\'a}ndez, Jos{\'e} Alberto and Reviriego, Pedro and Brysbaert, Marc},
  journal={arXiv preprint arXiv:2310.14703},
  year={2023}
}
```
