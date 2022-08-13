 # AfricaNLP resources
List of all the resources we developed in collaboration with LSV and Masakhane during my doctoral studies and beyond

## Labelled Datasets for AfricaNLP

| Dataset Name | NLP Task | Link to Publication  | Languages covered |
|----------|----------|--------|----------------------------|
| [MasakhaNER](https://github.com/masakhane-io/masakhane-ner) | named entity recognition | [MasakhaNER: Named Entity Recognition for African Languages](https://aclanthology.org/2021.tacl-1.66/)  | amh, hau, ibo, kin, lug, luo, pcm, swa, wol, yor|
| [MAFAND-MT](https://github.com/masakhane-io/lafand-mt) | machine translation | [A Few Thousand Translations Go a Long Way](https://aclanthology.org/2022.naacl-main.223/)| amh, bam, bbj, ewe, fon, hau, ibo, kin, lug, luo, mos, nya, pcm, sna, swa, tsn, twi, wol, xho, yor, zul|
| [ANTC](https://github.com/uds-lsv/afro-maft)      | News-topic classification | [multilingual adaptive fine-tuning (MAFT)](https://arxiv.org/abs/2204.06487) | lin, pcm, mlg, som, zul |
| [MENYO-20K](https://github.com/uds-lsv/menyo-20k_MT) | machine translatio | [MENYO-20k: A Multi-domain English–Yoruba Corpus for Machine Translation](https://arxiv.org/abs/2103.08647v1)| yor|


## Multilingual Pre-trained Language Models
The models below are created using [multilingual adaptive fine-tuning (MAFT)](https://arxiv.org/abs/2204.06487) on XLMR-distilled model, XLM-R, mT5, ByT5 and mBART. We list the model, model size (in millions), and architecture. We cover the following 20 languages: afr, amh, ara, eng, fra, hau, ibo, mlg, nya, orm, pcm, kin, run, sna, som, sot, swa, xho, yor, zul 

| Model | Size (M)  | architecture |
|-------|-------|-----------------|
| [AfroXLMR-mini](https://huggingface.co/Davlan/afro-xlmr-mini) | 117M | Masked LM |
| [AfroXLMR-small](https://huggingface.co/Davlan/afro-xlmr-small) | 140M | Masked LM |
| [AfroXLMR-base](https://huggingface.co/Davlan/afro-xlmr-base) | 270M | Masked LM |
| [AfroXLMR-large](https://huggingface.co/Davlan/afro-xlmr-large) | 550M | Masked LM |
| [AfriMT5](https://huggingface.co/masakhane/afri-mt5-base) | 580M | Seq-to-Seq |
| [AfriByT5](https://huggingface.co/masakhane/afri-byt5-base) | 580M | Seq-to-Seq |
| [AfriMBART](https://huggingface.co/masakhane/afri-mbart50) | 610M | Seq-to-Seq |

## Language Adaptive Fine-tuning (LAFT) Models
The following PLMs are created by language adaptation to a language using monolingual corpus in that language. The monolingual corpus used to create them are described in the [MasakhaNER paper](https://aclanthology.org/2021.tacl-1.66/) and [MAFT paper](https://arxiv.org/abs/2204.06487)
| Language | mBERT  | XLM-R-base | XLM-R-large |
|----------|--------|------------|-------------|
| amh      | [Davlan/bert-base-multilingual-cased-finetuned-amharic](https://huggingface.co/Davlan/bert-base-multilingual-cased-finetuned-amharic)       | [Davlan/xlm-roberta-base-finetuned-amharic](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-amharic)           |             |
| hau      |        | [Davlan/xlm-roberta-base-finetuned-hausa](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-hausa)           |             |
| ibo      | [Davlan/bert-base-multilingual-cased-finetuned-igbo](https://huggingface.co/Davlan/bert-base-multilingual-cased-finetuned-igbo)       | [Davlan/xlm-roberta-base-finetuned-igbo](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-igbo)           |             |
| kin      | [Davlan/bert-base-multilingual-cased-finetuned-kinyarwanda](https://huggingface.co/Davlan/bert-base-multilingual-cased-finetuned-kinyarwanda)        | [Davlan/xlm-roberta-base-finetuned-kinyarwanda](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-kinyarwanda)           |             |
| lin      |        |  [Davlan/xlm-roberta-base-finetuned-lingala](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-lingala)          |             |
| lug      | [Davlan/bert-base-multilingual-cased-finetuned-luganda](https://huggingface.co/Davlan/bert-base-multilingual-cased-finetuned-luganda)       | [Davlan/xlm-roberta-base-finetuned-luganda](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-luganda)           |             |
| luo      | [Davlan/bert-base-multilingual-cased-finetuned-luo](https://huggingface.co/Davlan/bert-base-multilingual-cased-finetuned-luo)       | [Davlan/xlm-roberta-base-finetuned-luo](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-luo)          |             |
| mlg      |        |            |             |
| nya      |        | [Davlan/xlm-roberta-base-finetuned-chichewa](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-chichewa)           |             |
| pcm      | [Davlan/bert-base-multilingual-cased-finetuned-naija](https://huggingface.co/Davlan/bert-base-multilingual-cased-finetuned-naija)        | [Davlan/xlm-roberta-base-finetuned-naija](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-naija)          |             |
| sna      |        | [Davlan/xlm-roberta-base-finetuned-shona](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-shona)           |             |
| som      |        | [Davlan/xlm-roberta-base-finetuned-somali](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-somali)           |             |
| swa      |        | [Davlan/xlm-roberta-base-finetuned-swahili](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-swahili)           |             |
| wol      | [Davlan/bert-base-multilingual-cased-finetuned-wolof](https://huggingface.co/Davlan/bert-base-multilingual-cased-finetuned-wolof)       |            [Davlan/xlm-roberta-base-finetuned-wolof](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-wolof)  |           |
| xho      |        | [Davlan/xlm-roberta-base-finetuned-xhosa](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-xhosa)          |             |
| yor      |        | [Davlan/xlm-roberta-base-finetuned-yoruba](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-yoruba)           |             |
| zul      |        | [Davlan/xlm-roberta-base-finetuned-zulu](https://huggingface.co/Davlan/xlm-roberta-base-finetuned-zulu)           |             |

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
| hau | [Hausa FastText](https://zenodo.org/record/6989326#.YvgMA3UzY5k) |
| ibo | [Igbo FastText](https://zenodo.org/record/6988731#.Yve923UzY5k)  |
| kin | [Kinyarwanda FastText](https://zenodo.org/record/6988740#.Yve93nUzY5k)  |
| lug | [Luganda FastText](https://zenodo.org/record/6988742#.Yve94XUzY5k)  |
| luo | [Luo FastText](https://zenodo.org/record/6988914#.Yve_bHUzY5k)  |
| mos | [Mossi FastText](https://zenodo.org/record/6988918#.Yve_bXUzY5k) |
| nya | [Chichewa FastText](https://zenodo.org/record/6988932#.YvgMJXUzY5k)  |
| pcm | [Nigerian-Pidgin FastText](https://zenodo.org/record/6988939#.YvfDDHUzY5k)  |
| sna | [Setswana FastText](https://zenodo.org/record/6989116#.YvfNc3UzY5k) |
| swa | [Swahili FastText](https://zenodo.org/record/6989122#.YvgMTnUzY5k)  |
| tsn | [Setswana FastText](https://zenodo.org/record/6989116#.YvgMjHUzY5k) |
| twi | [Twi FastText](https://zenodo.org/record/6988532#.YveVmXUzY5k)  |
| wol | [Wolof FastText](https://zenodo.org/record/6989168#.YvgMznUzY5k)  |
| xho | [Xhosa FastText](https://zenodo.org/record/6989303#.YvgM6nUzY5k)  |
| yor | [Yoruba FastText](https://zenodo.org/record/6987250#.YveVi3UzY5k)  |
| zul | [Zulu FastText](https://zenodo.org/record/6989305#.YvgNCXUzY5k) |
