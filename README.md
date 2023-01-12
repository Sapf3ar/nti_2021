# _NTO 2021_
Team Oasis colab notebooks and stuff for National Tech Olympycs - 2021

## _First stage_
Typical text classification
* models used:
 * https://huggingface.co/DeepPavlov/rubert-base-cased
 * https://huggingface.co/xlm-roberta-base

* Dataset
   * https://russiansuperglue.com/tasks/download/MuSeRC

### _Second stage_

There are a lot of ways to handle this dataset. We tried (partially succesfull): QA, Classification, Span generation with and withous NER

* Dataset
  * https://russiansuperglue.com/tasks/download/RuCoS

* models (transforsmers only, obviously) used:
  * For text classification: 
    https://huggingface.co/DeepPavlov/rubert-base-cased ,via slavic langs vocab provided by from DeepPavlov
  * For correct span generation:
    https://huggingface.co/google/mt5-large
  * For QA:
    https://huggingface.co/bert-base-multilingual-cased
 


