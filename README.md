# Awesome-Tokenization

A curated collection of Medium articles exploring tokenization in the context of large language models (LLMs).

## Medium Articles on LLM Tokenization

- [All you need to know about Tokenization in LLMs – Tayyib Ul Hassan Gondal (The Deep Hub, Medium)](https://medium.com/thedeephub/all-you-need-to-know-about-tokenization-in-llms-7a801302cf54)  
  A detailed primer covering tokenization definitions, naive schemes (character, word), UTF encoding, BPE, and custom tokenizer implementation. :contentReference[oaicite:1]{index=1}

- [What is LLM Tokenization and Why Is It Important? – Mikhail Berkov (Thinking Sand, Medium)](https://medium.com/thinking-sand/what-is-llm-tokenization-and-why-is-it-important-4eb5fbefb075)  
  A recent explainer emphasizing how understanding tokens helps control model behavior, optimize cost, and avoid context-window limits. :contentReference[oaicite:5]{index=5}

- [Learning Tokenizers: The First Step to NLP – Brandon Gomes (NLP to LLM from Basic Principles, Medium)](https://medium.com/@brandonmgomes06/nlp-to-llm-from-basic-principles-tokenizers-d678c132eea2)  
  A walkthrough of evolving tokenizer implementations, progressing from basic to regex-based versions. :contentReference[oaicite:2]{index=2}

- [My notes about tokenizers – Understanding Tokenizers in LLMs – Valentin Radovich (Medium)](https://medium.com/@valentinradovich/my-notes-about-tokenizers-c433c6f89c0b)  
  Reflections on tokenizers: how they work, vocabulary sizes across GPT-versions, multilingual handling, BPE, and performance side-effects. :contentReference[oaicite:3]{index=3}

- [Unlocking the Secrets of Text: Tokenization in AI – Mohan K (Medium)](https://medium.com/@mohan_kandasamy/unlocking-the-secrets-of-text-tokenization-in-ai-8d6425d8ec43)  
  A conceptual overview likening tokenization to ingredient prep in cooking; covers words, characters, subwords, and their roles in NLP tasks. :contentReference[oaicite:4]{index=4}

- [Tokenization: The Secret Sauce for Dynamic Embeddings – AI-Tasks (Medium)](https://medium.com/@AI_Tasks/tokenization-the-secret-sauce-for-dynamic-embeddings-d45f2055a770) *(Member-only)*  
  Introduces embedding and tokenization basics, walks through BPE, and shows how tokens become embeddings in LLM inputs. :contentReference[oaicite:5]{index=5}

- [LLM Tokenizer for C++ – Brandon Fowler (Medium)](https://medium.com/@brandon_97642/llm-tokenizer-for-c-3fa154534b70)  
  Describes a custom C++ (SentencePiece-style) tokenizer built using libtorch, including repository link. :contentReference[oaicite:6]{index=6}

- [LLMs – TOKENIZATION – scitechtalk tv (Medium)](https://medium.com/@tvscitechtalk/list/llms-tokenization-fa203ff67f83)  
  A short curated list—including “Understanding ‘tokens’ and tokenization in large language models” and other tokenization-related content. :contentReference[oaicite:7]{index=7}

## DEV.to Articles on LLM Tokenization

* [Building a Custom Tokenizer for LLMs to Handle Unique Vocabulary – Hakeem Abbas (DEV.to)](https://dev.to/hakeem/building-a-custom-tokenizer-for-llms-to-handle-unique-vocabulary-1a32)
  Explores the need for custom tokenizers tailored to specialized domains with unique vocabularies and describes methods for improving tokenization fidelity.&#x20;

* [Learn how LLMs convert language into vectors using tokenization and embeddings – Cristian Sifuentes (DEV.to)](https://dev.to/cristiansifuentes/learn-how-llms-convert-language-into-vectors-using-tokenization-and-embeddings-kh2)
  Introduces how LLMs transform language into mathematical representations via tokenization, vectorization, and embeddings, with accessible analogies and Python examples.&#x20;

* [Byte-Pair Tokenization: The Basic Principle Behind Large Language Models – Otavio Monteagudo (DEV.to)](https://dev.to/otamm/byte-pair-tokenization-the-basic-principle-behind-large-language-models-16ld)
  Offers a concise primer on byte-pair encoding (BPE), its vocabulary-building method, and its advantages over word-level tokenizers.&#x20;

## Substack Articles on LLM Tokenization

* [Let’s build Andrej Karpathy’s BPETokenizer in Rust and use it from Python – Alex Razvant (Multimodal AI, Substack)](https://multimodalai.substack.com/p/lets-build-andrej-karpathys-bpetokenizer)
  A hands-on tutorial to implement a BPE tokenizer in Rust with Python bindings—highlighting efficiency gains and practical implementation.&#x20;

* [A practical roadmap on LLM Systems – Alex Razvant (Multimodal AI, Substack)](https://multimodalai.substack.com/p/a-practical-roadmap-on-llm-systems)
  Situates tokenizers as core components of the LLM pipeline, discussing their role in processing and interpreting text within modern model systems.&#x20;

* [What else can LLMs do? – Paul Harrald (Substack)](https://paulharrald.substack.com/p/what-else-can-llms-do)
  Briefly touches on tokenization efficiency challenges, including sequence-length concerns in long inputs like DNA or high-resolution images, and mentions hierarchical tokenization approaches.&#x20;
