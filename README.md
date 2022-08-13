# AfricaNLP resources
List of all the resources we developed in collaboration with LSV and Masakhane during my doctoral studies and beyond

## Labelled Datasets for AfricaNLP

| Dataset Name | NLP Task | Link to Publication  | Languages covered |
|----------|----------|--------|----------------------------|
| MasakhaNER | | | |
| MAFAND-MT | | | |
| ANTC      | | | |


## Multilingual Pre-trained Language Models
The models below are created using [multilingual adaptive fine-tuning (MAFT)](https://arxiv.org/abs/2204.06487)
| Model | Size  | Languages covered |
|-------|-------|-----------------|
| AfroXLMR-mini | |
| AfroXLMR-small | |
| AfroXLMR-base | |
| AfroXLMR-large | |
| AfriMT5 | |
| AfriByT5 | |
| AfriMBART | |

## Language Adaptive Fine-tuning (LAFT) Models
| Language | mBERT  | XLM-R-base | XLM-R-large |
|----------|--------|------------|-------------|
| amh      |        |            |             |

## FastText Embeddings for African languages
We provide better quality word embeddings than the [pre-trained FastText embeddings](https://fasttext.cc/docs/en/crawl-vectors.html) trained on Common crawl and Wikipedia. While we did not evaluate the quality on all the languages, our evaluation on Yoruba and Twi shows that they give better performance on word similarity tasks. The FastText embeddings are trained on curated data from JW300, Bible, VOA, BBC, and other news websites. Details of the data sources are in my PhD dissertation. 

We trained the FastText embeddings using [Gensim 3.8.1](https://pypi.org/project/gensim/3.8.1/). All embedding models can be downloaded from Zenodo. Please, find the links below. 

| Language | Link to Model  |
|----------|-----------------|
| amh | [Amharic FastText](https://zenodo.org/record/6988528#.YvePxXUzY5k)  |
| bam | [Bambara FastText](https://zenodo.org/record/6987246#.YveVNnUzY5k) |
| bbj | [Ghomala FastText](https://zenodo.org/record/6988547#.YveVlHUzY5k)  |
| ewe | [Ewe FastText](https://zenodo.org/record/6988555#.YveVknUzY5k)  |
| fon | [Fon FastText](https://zenodo.org/record/6988727#.YveVonUzY5k) |
| hau |   |
| ibo | [Igbo FastText](https://zenodo.org/record/6988731#.Yve923UzY5k)  |
| kin | [Kinyarwanda FastText](https://zenodo.org/record/6988740#.Yve93nUzY5k)  |
| lug | [Luganda FastText](https://zenodo.org/record/6988742#.Yve94XUzY5k)  |
| luo |   |
| mos |   |
| nya |   |
| pcm |   |
| sna |   |
| swa |   |
| tsn |   |
| twi | [Twi FastText](https://zenodo.org/record/6988532#.YveVmXUzY5k)  |
| wol |   |
| xho |   |
| yor | [Yoruba FastText](https://zenodo.org/record/6987250#.YveVi3UzY5k)  |
| zul |   |
