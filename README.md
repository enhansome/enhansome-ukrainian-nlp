# awesome-ukrainian-nlp with stars

Curated list of Ukrainian natural language processing (NLP) resources (corpora, pretrained models, libriaries, etc.)

## News

* 2025-11 -- [UNLP 2026 — The Fifth UNLP Conference](https://unlp.org.ua/call-for-papers/) first call for papers
* 2024/12 -- [UNLP 2025 Shared Task on Detecting Social Media Manipulation](https://unlp.org.ua/shared-task/) has been announced.
* 2024/01 -- [UNLP 2024 Shared Task on Fine-Tuning LLMs for Ukrainian](https://github.com/unlp-workshop/unlp-2024-shared-task) ⭐ 17 | 🐛 1 | 📅 2024-04-15 has been announced.

## 1. Datasets / Corpora

### Monolingual

* [mC4](https://github.com/allenai/allennlp/discussions/5056) ⚠️ Archived — filtered CommonCrawl again, 196GB of Ukrainian text.
* [Brown-UK](https://github.com/brown-uk/corpus) ⭐ 119 | 🐛 4 | 🌐 Groovy | 📅 2026-08-16 — carefully curated corpus of modern Ukrainian language with dismabiguated tokens, 1 million words
* [Ukrainian Twitter corpus](https://github.com/saganoren/ukr-twi-corpus) ⭐ 16 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2019-07-04 - Ukrainian Twitter corpus for toxic text detection.
* [Ukrainian forums](https://github.com/khrystyna-skopyk/ukr_spell_check/blob/master/data/scraped.txt) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2017-06-30 — 250k sentences scraped from forums.
* [Kobza](https://huggingface.co/datasets/Goader/kobza) — around 1.3TB of uncompressed text, 60 billion tokens across 97 million documents, deduplicated compilation of CulturaX, Fineweb 2, HPLT 2.0, Ukrainian News and UberText 2.0.
* [Malyuk](https://huggingface.co/datasets/lang-uk/malyuk) — 113GB of text, compilation of UberText 2.0, OSCAR, Ukrainian News.
* [UberText 2.0](https://lang.org.ua/en/ubertext/) — over 5 GB of news, Wikipedia, social, fiction, and legal texts
* [Wikipedia](https://dumps.wikimedia.org/ukwiki/latest/)
* [OSCAR](https://oscar-corpus.com/) — shuffled sentences extracted from [Common Crawl](https://commoncrawl.org/) and classified with a language detection model. Ukrainian portion of it is 28GB deduplicated.
* [CC-100](http://data.statmt.org/cc-100/) — documents extracted from [Common Crawl](https://commoncrawl.org/), automatically classified and filtered. Ukrainian part is 200M sentences or 10GB of deduplicated text.
* [Ukrainain news headlines](https://huggingface.co/datasets/Yehor/news-headlines-ubercorpus) — 3.98M news headlines.
* [STQ-UA](https://huggingface.co/datasets/danylo-boiko/stq-ua) — 100k Ukrainian search queries.

### Parallel

* [Tatoeba MT Challenge data sets](https://github.com/Helsinki-NLP/Tatoeba-Challenge/) ⭐ 855 | 🐛 12 | 🌐 Makefile | 📅 2024-08-20
* [Back-translated monolingual Wiki data](https://github.com/Helsinki-NLP/Tatoeba-Challenge/blob/master/data/Backtranslations.md) ⭐ 855 | 🐛 12 | 🌐 Makefile | 📅 2024-08-20
* [OPUS](https://opus.nlpl.eu/)
* [Polish-Ukrainian Parallel Corpus](https://clarin-pl.eu/dspace/handle/11321/535)
* [Wiki Edits](https://huggingface.co/datasets/osyvokon/wiki-edits-uk) — 5M sentence edits extracted from the Ukrainian Wikipedia revision history.

See [Helsinki-NLP/UkrainianLT](https://github.com/Helsinki-NLP/UkrainianLT) ⭐ 41 | 🐛 1 | 📅 2022-04-27 for more data and machine translation resources links.

### Labeled

* [UA-GEC](https://github.com/grammarly/ua-gec) ⭐ 273 | 🐛 4 | 🌐 Macaulay2 | 📅 2024-02-11 — grammatical error correction (GEC) and fluency corpus.
* [NER-uk](https://github.com/lang-uk/ner-uk) ⭐ 94 | 🐛 7 | 🌐 Common Lisp | 📅 2026-07-30 — Brown-UK labeled for named entities.
* [ua-news](https://github.com/fido-ai/ua-datasets/tree/main/ua_datasets/src/text_classification) ⭐ 57 | 🐛 0 | 🌐 Python | 📅 2025-10-26 — 150k news article in 5 categories.
* [UA-SQuAD](https://github.com/fido-ai/ua-datasets/tree/main/ua_datasets/src/question_answering) ⭐ 57 | 🐛 0 | 🌐 Python | 📅 2025-10-26 — Ukrainian version of Stanford Question Answering Dataset.
* [Universal Dependencies](https://github.com/UniversalDependencies/UD_Ukrainian-IU/tree/master) ⭐ 30 | 🐛 2 | 📅 2026-05-06 — dependency trees corpus.
* [Ukrainian Winograd schema challenge (WSC) Dataset](https://github.com/pkuchmiichuk/ua-coref#ukrainian-wsc-dataset) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2023-12-22 — manually translated.
* [Ukrainian OntoNotes Dataset](https://github.com/pkuchmiichuk/ua-coref#ukrainian-ontonotes-dataset) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2023-12-22 — scripts to build large silver dataset for coreference resolution.
* [ZNO](https://huggingface.co/datasets/osyvokon/zno) — \~4000 text-only questions and answers from Ukrainian External independent testing (ЗНО/ZNO).
* [MMZNO](https://huggingface.co/datasets/lang-uk/MMZNO) — \~4000 multi-modal (text and images) ZNO questions
* [OmniGEC](https://huggingface.co/collections/lang-uk/omnigec-68095391ebef195ed6c0a5f3) — synthetic GEC datasets, along with models.
* [Yakaboo Book Reviews](https://1drv.ms/f/s!AgoiFOsRix8LcYNBl26rru8wGGo?e=geqLkp) — book reviews, ratings and descriptions.

### Dictionaries

* [ВЕСУМ](https://github.com/brown-uk/dict_uk) ⭐ 630 | 🐛 36 | 🌐 Groovy | 📅 2026-08-24 — POS tag dictionary. Can generate a list of all word forms valid for spelling.
* [Tonal dictionary](https://github.com/lang-uk/tone-dict-uk) ⭐ 47 | 🐛 1 | 🌐 Common Lisp | 📅 2016-09-26
* [obscene-ukr](https://github.com/saganoren/obscene-ukr) ⭐ 24 | 🐛 0 | 📅 2025-05-15 — profanity dictionary
* [Word stress dictionary](https://github.com/lang-uk/ukrainian-word-stress-dictionary) ⭐ 23 | 🐛 3 | 📅 2024-09-29 — word stress for 2.7M word forms. See [ukrainian-word-stress](https://github.com/lang-uk/ukrainian-word-stress) ⭐ 62 | 🐛 0 | 🌐 Python | 📅 2026-07-20
* [Heteronyms](https://github.com/lang-uk/ukrainian-heteronyms-dictionary) ⭐ 5 | 🐛 0 | 📅 2022-07-12 — words that share the same spelling but have different meaning/pronunciation.
* [Abbreviations](https://github.com/lang-uk/ukrainian-abbreviations-dictionary) ⭐ 4 | 🐛 0 | 📅 2022-01-18 — map abbreviation to expansion
* [Multilingualsentiment, includes Ukrainian](https://sites.google.com/site/datascienceslab/projects/multilingualsentiment) - a list of positive/negative words

### Prompts

* [Aya](https://huggingface.co/datasets/CohereForAI/aya_dataset) — crowd-sourced prompts and reference outputs. Ukrainian part is \~500 prompts.

## 2. Tools

* [pymorphy2](https://github.com/kmike/pymorphy2) ⭐ 1,175 | 🐛 86 | 🌐 Python | 📅 2024-06-26 + [pymorphy2-dicts-uk](https://pypi.org/project/pymorphy2-dicts-uk/) — POS tagger and lemmatizer
* [NLP-Cube](https://github.com/adobe/NLP-Cube) ⭐ 562 | 🐛 4 | 🌐 HTML | 📅 2024-11-03 - Python package for tokenization, sentence splitting, multi-word-tokenization, lemmatization, part-of-speech tagging and dependency parsing.
* [nlp-uk](https://github.com/brown-uk/nlp_uk) ⭐ 79 | 🐛 2 | 🌐 Groovy | 📅 2026-05-27 — Tools for cleaning and normalizing texts, tokenization, lemmatization, POS, disambiguation
* [tree\_stem](https://github.com/amakukha/stemmers_ukrainian) ⭐ 29 | 🐛 1 | 🌐 Python | 📅 2022-11-22 — stemmer
* [LanguageTool](https://languagetool.org/uk/) — grammar, style and spell checker
* [Stanza](https://stanfordnlp.github.io/stanza/) — Python package for tokenization, multi-word-tokenization, lemmatization, POS, dependency parsing, NER

## 3. Pretrained models

### Language models

*Autoregressive:*

* [XGLM](https://github.com/pytorch/fairseq/blob/main/examples/xglm/README.md) ⚠️ Archived — multilingual autoregressive LM, the 4.5B checkpoint includes Ukrainian.

* [UAlpaca](https://github.com/robinhad/kruk) ⭐ 96 | 🐛 5 | 🌐 Jupyter Notebook | 📅 2024-07-12 — Llama fine-tuned for instruction following on the machine-translated Alpaca dataset.

* [uk4b](https://github.com/proger/uk4b) ⭐ 20 | 🐛 2 | 🌐 Python | 📅 2023-08-06 and [haloop inference toolkit](https://github.com/proger/haloop/tree/main#pretrained-models) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2025-07-15 - GPT-2 small, medium and large-style models trained on UberText 2.0 wikipedia, news and books.

* [Lapa](https://huggingface.co/collections/lapa-llm/lapa-v012-release) — Gemma-3-12B-based Ukrainian LLM, along with training datasets

* [MamayLM v0.1](https://huggingface.co/collections/INSAIT-Institute/mamaylm-gemma-2-68080b895a949a52b474d5de) - Ukrainian-focused Gemma 2 based 9B model, pre-trained and fine-tuned on large Ukrainian/English corpora (blog in [Ukrainian](https://huggingface.co/blog/INSAIT-Institute/mamaylm-ukr) and [English](https://huggingface.co/blog/INSAIT-Institute/mamaylm))

* [MamayLM v1.0](https://huggingface.co/collections/INSAIT-Institute/mamaylm-v10-gemma-3-68d3fd732b78eaba4886db9d) - Ukrainian-focused Gemma 3 based 4B and 12B multimodal models, pre-trained and fine-tuned on large Ukrainian/English corpora ([blog](https://blog.mamaylm.insait.ai/))

* [aya-101](https://huggingface.co/CohereForAI/aya-101) — massively multilingual LM, 13B parameters

* [pythia-uk](https://huggingface.co/theodotus/pythia-uk) — mT5 finetuned on wiki and oasst1 for chats in Ukrainian.

* [Tereveni-AI/GPT-2](https://huggingface.co/Tereveni-AI/gpt2-124M-uk-fiction)

*Masked:*

* [xlm-roberta-base-uk](https://huggingface.co/ukr-models/xlm-roberta-base-uk) — truncated version of XLM-RoBERTa with only Ukrainian and English embeddings left.
* [youscan/ukr-roberta-base](https://huggingface.co/youscan/ukr-roberta-base)
* [Goader/modern-liberta-large](https://huggingface.co/Goader/modern-liberta-large) — ModernBERT Large with Ukrainian tokenizer and 8192 context window, continually pretrained on 160B tokens.

*Mixed*:

* [Electra](https://huggingface.co/lang-uk)

### Machine translation

* [M2M-100](https://github.com/pytorch/fairseq/tree/master/examples/m2m_100) ⚠️ Archived — Ukrainian to/from 100 languages.
* [Helsinki-NLP / OPUS-MT models](https://github.com/Helsinki-NLP/UkrainianLT) ⭐ 41 | 🐛 1 | 📅 2022-04-27 — Ukrainian to/from 25 langaguages.
  * [OPUS-MT models evaluated on flores101](https://github.com/Helsinki-NLP/UkrainianLT/blob/main/opus-mt-ukr-flores-devtest.md) ⭐ 41 | 🐛 1 | 📅 2022-04-27
  * [OPUS-MT models at HuggingFace](https://huggingface.co/models?language=uk\&pipeline_tag=translation\&sort=modified)
* [Uk-En folktale corpus](https://github.com/Ukrainian-To-English-Corpora/Folktale_corpus) ⭐ 0 | 🐛 0 | 📅 2022-09-15 — small sentence-aligned corpus of fairy tales.

See [Helsinki-NLP/ UkrainianLT](https://github.com/Helsinki-NLP/UkrainianLT) ⭐ 41 | 🐛 1 | 📅 2022-04-27 for more.

### Sequence-to-sequence models

* [mBART50](https://github.com/pytorch/fairseq/tree/master/examples/multilingual#mbart50-models) ⚠️ Archived
* [mT5](https://github.com/google-research/multilingual-t5) ⚠️ Archived

### Named-entity recognition (NER)

* [MITIE NER Model](https://lang.org.ua/en/models/#anchor1)
* [ukr-models/uk-ner](https://huggingface.co/ukr-models/uk-ner)
* [lang-uk/flair-uk-ner](https://huggingface.co/lang-uk/flair-uk-ner)
* [dchaplinsky/uk\_ner\_web\_trf\_large](https://huggingface.co/dchaplinsky/uk_ner_web_trf_large)

### Part-of-speech tagging (POS)

* [lang-uk/flair-uk-pos](https://huggingface.co/lang-uk/flair-uk-pos)

### Word embeddings

* [BPEmb: Subword Embeddings, includes Ukrainian](https://nlp.h-its.org/bpemb/) - easy to use with [Flair](https://github.com/flairNLP/flair/blob/master/resources/docs/embeddings/BYTE_PAIR_EMBEDDINGS.md) ⭐ 14,383 | 🐛 31 | 🌐 Python | 📅 2025-10-27
* [Flair](https://github.com/flairNLP/flair/blob/master/resources/docs/embeddings/FLAIR_EMBEDDINGS.md) ⭐ 14,383 | 🐛 31 | 🌐 Python | 📅 2025-10-27 — [Ukrainian](https://huggingface.co/lang-uk/flair-uk-forward) added in 2022.
* fastText
  * [Older official fastText trained on Wiki](https://github.com/facebookresearch/fastText/blob/master/docs/pretrained-vectors.md) ⚠️ Archived — 294 languages, including Ukrainian.
  * [fastText\_multilingual](https://github.com/babylonhealth/fastText_multilingual) ⭐ 1,201 | 🐛 11 | 🌐 Jupyter Notebook | 📅 2023-03-10 — 78 languages, aligned to the same vector space.
  * [Official fastText trained on CommonCrawl and Wiki](https://fasttext.cc/docs/en/crawl-vectors.html) — 157 languages, including Ukrainian.
  * [fasttext\_uk (2023)](https://huggingface.co/dchaplinsky/fasttext_uk) and [cbow](https://huggingface.co/dchaplinsky/fasttext_uk_cbow) — trained on UberText 2.0
* [Word2Vec](https://lang.org.ua/en/models/#anchor4)
* [GloVe](https://lang.org.ua/en/models/#anchor4)
* [LexVec](https://lang.org.ua/en/models/#anchor4)

### Other

* [ukrainian-word-stress](https://github.com/lang-uk/ukrainian-word-stress) ⭐ 62 | 🐛 0 | 🌐 Python | 📅 2026-07-20 — adds word stress.
* [uk-punctcase](https://huggingface.co/ukr-models/uk-punctcase) — punctuation and case restoration model based on XLM-RoBERTa-Uk.
* [punctuation\_uk\_bert](https://huggingface.co/dchaplinsky/punctuation_uk_bert) — another punctuation and case restoration model based on bert-base-multilingual-cased.

## 4. Paid

* [LORELEI Ukrainian Representative Language Pack](https://catalog.ldc.upenn.edu/LDC2020T24) - Ukrainian monolingual text, Ukrainian-English parallel text, partially annotated for named entities

## 5. Other resources and links

* [egorsmkv / speech-recognition-uk](https://github.com/egorsmkv/speech-recognition-uk) ⭐ 440 | 🐛 11 | 🌐 Python | 📅 2025-09-12 — speech recognition and text-to-speech models and datasets
* [Helsinki-NLP/ UkrainianLT](https://github.com/Helsinki-NLP/UkrainianLT) ⭐ 41 | 🐛 1 | 📅 2022-04-27 — another collection of links to Ukrainian language tools.

## 6. Workshops and conferences

* [UNLP 2024 Shared Task](https://github.com/unlp-workshop/unlp-2024-shared-task) ⭐ 17 | 🐛 1 | 📅 2024-04-15 — shared task (competition) on fine-tuning large language models (LLMs) for Ukrainian
* [Ukrainian Natural Language Processing Workshop](https://unlp.org.ua/)
* UNLP 2023 Shared Task — shared task (competition) in grammatical error correction for Ukrainian
  * [Training data and evaluation scripts](https://github.com/osyvokon/unlp-2023-shared-task) ⭐ 9 | 🐛 0 | 🌐 Macaulay2 | 📅 2023-03-14
  * [Public leaderboard](https://codalab.lisn.upsaclay.fr/competitions/10740)
* [UNLP 2025 Shared Task on Detecting Social Media Manipulation](https://unlp.org.ua/shared-task/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-02._
