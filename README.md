# English-NER-system

Tutorials of how to create English Named Entity Recognition (NER) systems by finetuning the model [distilbert-base-cased](https://huggingface.co/distilbert-base-cased) using the English subset of [MultiNERD NER dataset](https://huggingface.co/datasets/Babelscape/multinerd?row=0).

[System A](https://github.com/LauraYahui/English-NER-system/blob/main/System_A.ipynb) recognizes all entity types included in the original dataset.
[System B](https://github.com/LauraYahui/English-NER-system/blob/main/System_B.ipynb) recognizes 5 entity types: PERSON(PER), ORGANIZATION(ORG), LOCATION(LOC), DISEASES(DIS), ANIMAL(ANIM). Other entity types are converted to the "O" type.

## Run on Google Colab

1. Open [Google Colab](https://colab.research.google.com/).
2. Press "Open Colab".
3. Open a notebook from GitHub with the URL of [System A](https://github.com/LauraYahui/English-NER-system/blob/main/System_A.ipynb) or [System B](https://github.com/LauraYahui/English-NER-system/blob/main/System_B.ipynb).
4. Change the runtime type to T4 GPU.
5. Run all the cells.

## Dependencies

Please install the necessary libraries inside the Notebook. Refer to requirements.txt for the library versions.
