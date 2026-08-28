<img src="header.png" align="center">

[![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome#readme) ⭐ 500,816 | 🐛 105 | 📅 2026-08-21 [![Support Me](https://img.shields.io/badge/%F0%9F%92%97-Support%20Me-blue.svg?style=flat-square)](https://www.patreon.com/arbox)

\[[RubyML](https://github.com/arbox/machine-learning-with-ruby) ⭐ 2,222 | 🐛 6 | 🌐 Ruby | 📅 2024-12-26 |
[RubyDataScience](https://github.com/arbox/data-science-with-ruby) ⭐ 720 | 🐛 1 | 🌐 Ruby | 📅 2023-07-19 |
[RubyInterop](https://github.com/arbox/ruby-interoperability) ⭐ 41 | 🐛 1 | 🌐 Ruby | 📅 2020-11-16]

# Awesome NLP with Ruby with stars

> Useful resources for text processing in Ruby

This curated list comprises [*awesome*](https://github.com/sindresorhus/awesome/blob/master/awesome.md) ⭐ 500,816 | 🐛 105 | 📅 2026-08-21
resources, libraries, information sources about computational processing of texts
in human languages with the [Ruby programming language](ruby).
That field is often referred to as
[NLP](https://en.wikipedia.org/wiki/Natural_language_processing),
[Computational Linguistics](https://en.wikipedia.org/wiki/Computational_linguistics),
[HLT](https://en.wikipedia.org/wiki/Language_technology) (Human Language Technology)
and can be brought in conjunction with
[Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence),
[Machine Learning](https://en.wikipedia.org/wiki/Machine_learning),
[Information Retrieval](https://en.wikipedia.org/wiki/Information_retrieval),
[Text Mining](https://en.wikipedia.org/wiki/Text_mining),
[Knowledge Extraction](https://en.wikipedia.org/wiki/Knowledge_extraction)
and other related disciplines.

This list comes from our day to day work on Language Models and NLP Tools.
Read [why](motivation.md) this list is awesome. Our [FAQ](FAQ.md) describes the
important decisions and useful answers you may be interested in.

:sparkles: Every [contribution](#contributing) is welcome! Add links through pull
requests or create an issue to start a discussion.

Follow us on [Twitter](https://twitter.com/NonWebRuby)
and please spread the word using the `#RubyNLP` hash tag!

<!-- nodoc -->

## Contents

<!-- toc -->

* [:sparkles: Tutorials](#sparkles-tutorials)
* [NLP Pipeline Subtasks](#nlp-pipeline-subtasks)
  * [Pipeline Generation](#pipeline-generation)
  * [Multipurpose Engines](#multipurpose-engines)
    * [On-line APIs](#on-line-apis)
  * [Language Identification](#language-identification)
  * [Segmentation](#segmentation)
  * [Lexical Processing](#lexical-processing)
    * [Stemming](#stemming)
    * [Lemmatization](#lemmatization)
    * [Lexical Statistics: Counting Types and Tokens](#lexical-statistics-counting-types-and-tokens)
    * [Filtering Stop Words](#filtering-stop-words)
  * [Phrasal Level Processing](#phrasal-level-processing)
  * [Syntactic Processing](#syntactic-processing)
    * [Constituency Parsing](#constituency-parsing)
  * [Semantic Analysis](#semantic-analysis)
  * [Pragmatical Analysis](#pragmatical-analysis)
* [High Level Tasks](#high-level-tasks)
  * [Spelling and Error Correction](#spelling-and-error-correction)
  * [Text Alignment](#text-alignment)
  * [Machine Translation](#machine-translation)
  * [Sentiment Analysis](#sentiment-analysis)
  * [Numbers, Dates, and Time Parsing](#numbers-dates-and-time-parsing)
  * [Named Entity Recognition](#named-entity-recognition)
  * [Text-to-Speech-to-Text](#text-to-speech-to-text)
* [Dialog Agents, Assistants, and Chatbots](#dialog-agents-assistants-and-chatbots)
* [Linguistic Resources](#linguistic-resources)
* [Machine Learning Libraries](#machine-learning-libraries)
* [Data Visualization](#data-visualization)
* [Optical Character Recognition](#optical-character-recognition)
* [Text Extraction](#text-extraction)
* [Full Text Search, Information Retrieval, Indexing](#full-text-search-information-retrieval-indexing)
* [Language Aware String Manipulation](#language-aware-string-manipulation)
* [Articles, Posts, Talks, and Presentations](#articles-posts-talks-and-presentations)
* [Projects and Code Examples](#projects-and-code-examples)
* [Books](#books)
* [Community](#community)
* [Needs your Help!](#needs-your-help)
* [Related Resources](#related-resources)
* [License](#license)

<!-- tocstop -->

<!-- doc -->

## :sparkles: Tutorials

Please help us to fill out this section! :smiley:

## NLP Pipeline Subtasks

An NLP Pipeline starts with a plain text.

### Pipeline Generation

* [parallel](https://github.com/grosser/parallel) ⭐ 4,264 | 🐛 43 | 🌐 Ruby | 📅 2026-05-15 -
  Supervisor for parallel execution on multiple CPUs or in many threads.
* [ruby-spark](https://github.com/ondra-m/ruby-spark) ⭐ 226 | 🐛 23 | 🌐 Ruby | 📅 2017-08-31 -
  Spark bindings with an easy to understand DSL.
* [phobos](https://github.com/phobos/phobos) ⚠️ Archived -
  Simplified Ruby Client for [Apache Kafka](https://kafka.apache.org/).
* [pwrake](https://github.com/masa16/pwrake) ⭐ 57 | 🐛 2 | 🌐 Ruby | 📅 2020-01-16 -
  Rake extensions to run local and remote tasks in parallel.
* [composable\_operations](https://github.com/t6d/composable_operations) ⚠️ Archived -
  Definition framework for operation pipelines.

### Multipurpose Engines

* [treat](https://github.com/louismullie/treat) ⭐ 1,367 | 🐛 35 | 🌐 Ruby | 📅 2025-05-16 -
  Natural Language Processing framework for Ruby (like [NLTK](http://www.nltk.org/) for Python).
* [stanford-core-nlp](https://github.com/louismullie/stanford-core-nlp) ⭐ 436 | 🐛 18 | 🌐 Ruby | 📅 2025-05-16 -
  Ruby Bindings for the Stanford [CoreNLP](https://github.com/stanfordnlp/CoreNLP) ⭐ 10,102 | 🐛 182 | 🌐 Java | 📅 2026-08-28 tools.
* [open-nlp](https://github.com/louismullie/open-nlp) ⭐ 91 | 🐛 2 | 🌐 Ruby | 📅 2025-05-16 -
  Ruby Bindings for the [OpenNLP](https://opennlp.apache.org/) Toolkit.
* [ruby-spacy](https://github.com/yohasebe/ruby-spacy) ⭐ 69 | 🐛 3 | 🌐 Ruby | 📅 2026-07-21 —
  Wrapper module for spaCy NLP library via [PyCall](https://github.com/mrkn/pycall.rb) ⭐ 1,116 | 🐛 52 | 🌐 C | 📅 2026-08-21.
* [open\_nlp](https://github.com/hck/open_nlp) ⭐ 11 | 🐛 1 | 🌐 Ruby | 📅 2018-11-28 -
  JRuby Bindings for the [OpenNLP](https://opennlp.apache.org/) Toolkit.
* [nlp\_toolz](https://github.com/LeFnord/nlp_toolz) ⚠️ Archived -
  Wrapper over some [OpenNLP](https://opennlp.apache.org/) classes and
  the original [Berkeley Parser](https://github.com/slavpetrov/berkeleyparser) ⭐ 187 | 🐛 10 | 🌐 Java | 📅 2021-02-08.

#### On-line APIs

* [google-cloud-language](https://github.com/googleapis/google-cloud-ruby/tree/master/google-cloud-language) ⭐ 1,424 | 🐛 64 | 🌐 Ruby | 📅 2026-08-28 -
  Google's Natural Language service API for Ruby.
* [wit-ruby](https://github.com/wit-ai/wit-ruby) ⭐ 280 | 🐛 2 | 🌐 Ruby | 📅 2022-05-09 -
  Ruby client library for the [Wit.ai](https://wit.ai/) Language Understanding Platform.
* [alchemyapi\_ruby](https://github.com/alchemyapi/alchemyapi_ruby) ⚠️ Archived -
  Legacy Ruby SDK for AlchemyAPI/Bluemix.
* [wlapi](https://github.com/arbox/wlapi) ⭐ 19 | 🐛 7 | 🌐 Ruby | 📅 2023-03-03 - Ruby client library for
  [Wortschatz Leipzig](http://wortschatz.uni-leipzig.de/de) web services.
* [monkeylearn-ruby](https://github.com/monkeylearn/monkeylearn-ruby) - Sentiment
  Analysis, Topic Modelling, Language Detection, Named Entity Recognition via
  a Ruby based Web API client.

### Language Identification

Language Identification is one of the first crucial steps in every NLP Pipeline.

* [scylla](https://github.com/hashwin/scylla) ⭐ 37 | 🐛 6 | 🌐 Ruby | 📅 2023-04-12 -
  Language Categorization and Identification.

### Segmentation

Tools for Tokenization, Word and Sentence Boundary Detection and Disambiguation.

* [pragmatic\_segmenter](https://github.com/diasks2/pragmatic_segmenter) ⭐ 594 | 🐛 32 | 🌐 Ruby | 📅 2024-08-11 -
  Word Boundary Disambiguation with many cookies.
* [pragmatic\_tokenizer](https://github.com/diasks2/pragmatic_tokenizer) ⭐ 93 | 🐛 11 | 🌐 Ruby | 📅 2024-08-11 -
  Multilingual tokenizer to split a string into tokens.
* [punkt-segmenter](https://github.com/lfcipriani/punkt-segmenter) ⭐ 91 | 🐛 5 | 🌐 Ruby | 📅 2018-06-10 -
  Pure Ruby implementation of the Punkt Segmenter.
* [tactful\_tokenizer](https://github.com/zencephalon/Tactful_Tokenizer) ⭐ 80 | 🐛 0 | 🌐 Ruby | 📅 2014-04-30 -
  RegExp based tokenizer for different languages.
* [scapel](https://github.com/louismullie/scalpel) ⭐ 52 | 🐛 2 | 🌐 Ruby | 📅 2026-01-29 -
  Sentence Boundary Disambiguation tool.
* [tokenizer](https://github.com/arbox/tokenizer) ⭐ 46 | 🐛 5 | 🌐 Ruby | 📅 2017-04-03 -
  Simple multilingual tokenizer. <sup>\[[tutorial](tutorials/tokenizer.md)]</sup>
* [textoken](https://github.com/manorie/textoken) ⭐ 31 | 🐛 0 | 🌐 Ruby | 📅 2021-09-28 -
  Simple and customizable text tokenization library.
* [nlp-pure](https://github.com/parhamr/nlp-pure) ⚠️ Archived -
  Natural language processing algorithms implemented in pure Ruby with minimal dependencies.

### Lexical Processing

#### Stemming

Stemming is the term used in information retrieval to describe the process for
reducing wordforms to some base representation. Stemming should be distinguished
from [Lemmatization](#lemmatization) since `stems` are not necessarily have
linguistic motivation.

* [ruby-stemmer](https://github.com/aurelian/ruby-stemmer) ⚠️ Archived -
  Ruby-Stemmer exposes the SnowBall API to Ruby.
* [uea-stemmer](https://github.com/ealdent/uea-stemmer) ⭐ 55 | 🐛 0 | 🌐 Ruby | 📅 2026-05-21 -
  Conservative stemmer for search and indexing.

#### Lemmatization

Lemmatization is considered a process of finding a base form of a word. Lemmas
are often collected in dictionaries.

* [lemmatizer](https://github.com/yohasebe/lemmatizer) ⭐ 113 | 🐛 2 | 🌐 Ruby | 📅 2021-10-14 -
  WordNet based Lemmatizer for English texts.

#### Lexical Statistics: Counting Types and Tokens

* [words\_counted](https://github.com/abitdodgy/words_counted) ⭐ 165 | 🐛 7 | 🌐 Ruby | 📅 2021-10-28 -
  Pure Ruby library counting word statistics with different custom options.
* [wc](https://github.com/thesp0nge/wc) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2011-11-15 -
  Facilities to count word occurrences in a text.
* [word\_count](https://github.com/AtelierConvivialite/word_count) ⚠️ Archived -
  Word counter for `String` and `Hash` objects.

#### Filtering Stop Words

* [stopwords-filter](https://github.com/brenes/stopwords-filter) ⭐ 80 | 🐛 6 | 🌐 Ruby | 📅 2023-11-24 - Filter and
  Stop Word Lexicon based on the SnowBall lemmatizer.

### Phrasal Level Processing

* [raingrams](https://github.com/postmodern/raingrams) ⭐ 70 | 🐛 2 | 🌐 Ruby | 📅 2021-02-28 -
  Flexible and general-purpose ngrams library written in pure Ruby.
* [n\_gram](https://github.com/reddavis/N-Gram) ⭐ 37 | 🐛 1 | 🌐 Ruby | 📅 2021-10-02 -
  N-Gram generator.
* [ruby-ngram](https://github.com/tkellen/ruby-ngram) ⭐ 12 | 🐛 1 | 🌐 Ruby | 📅 2013-12-12 -
  Break words and phrases into ngrams.

### Syntactic Processing

#### Constituency Parsing

* [rsyntaxtree](https://github.com/yohasebe/rsyntaxtree) ⭐ 124 | 🐛 2 | 🌐 Ruby | 📅 2026-08-27 -
  Visualization for syntactic trees in Ruby based on [RMagick](https://github.com/rmagick/rmagick) ⭐ 731 | 🐛 4 | 🌐 C++ | 📅 2026-08-25. <sup>\[dep: [ImageMagick](#imagemagick)]</sup>
* [rley](https://github.com/famished-tiger/Rley) ⭐ 37 | 🐛 2 | 🌐 Ruby | 📅 2025-03-18 -
  Pure Ruby implementation of the [Earley](https://en.wikipedia.org/wiki/Earley_parser)
  Parsing Algorithm for Context-Free Constituency Grammars.
* [stanfordparser](https://rubygems.org/gems/stanfordparser) -
  Ruby based wrapper for the Stanford Parser.

### Semantic Analysis

* [tf-idf-similarity](https://github.com/jpmckinney/tf-idf-similarity) ⭐ 783 | 🐛 1 | 🌐 Ruby | 📅 2024-02-26 -
  Calculate the similarity between texts using TF/IDF.
* [amatch](https://github.com/flori/amatch) ⭐ 395 | 🐛 3 | 🌐 C | 📅 2026-06-05 -
  Set of five distance types between strings (including Levenshtein, Sellers, Jaro-Winkler, 'pair distance').
* [damerau-levenshtein](https://github.com/GlobalNamesArchitecture/damerau-levenshtein) ⭐ 152 | 🐛 2 | 🌐 Ruby | 📅 2024-10-03 -
  Calculates edit distance using the Damerau-Levenshtein algorithm.
* [levenshtein-ffi](https://github.com/dbalatero/levenshtein-ffi) ⭐ 151 | 🐛 7 | 🌐 Ruby | 📅 2024-05-28 -
  Fast string edit distance computation, using the Damerau-Levenshtein algorithm.
* [hotwater](https://github.com/colinsurprenant/hotwater) ⭐ 80 | 🐛 1 | 🌐 Ruby | 📅 2013-02-26 -
  Fast Ruby FFI string edit distance algorithms.
* [tf\_idf](https://github.com/reddavis/TF-IDF) ⭐ 35 | 🐛 2 | 🌐 Ruby | 📅 2012-02-09 -
  Term Frequency / Inverse Document Frequency in pure Ruby.

### Pragmatical Analysis

* [SentimentLib](https://github.com/nzaillian/sentiment_lib) ⭐ 14 | 🐛 0 | 🌐 Ruby | 📅 2013-01-24 -
  Simple extensible sentiment analysis gem.

## High Level Tasks

### Spelling and Error Correction

* [gingerice](https://github.com/subosito/gingerice) ⚠️ Archived -
  Spelling and Grammar corrections via the [Ginger](https://www.gingersoftware.com/) API.
* [ffi-hunspell](https://github.com/postmodern/ffi-hunspell) ⭐ 51 | 🐛 7 | 🌐 Ruby | 📅 2023-12-28 -
  FFI based Ruby bindings for [Hunspell](https://hunspell.github.io/).
* [hunspell](https://github.com/segabor/Hunspell) ⭐ 35 | 🐛 2 | 🌐 C | 📅 2025-05-23 -
  Ruby bindings to [Hunspell](https://hunspell.github.io/) via Ruby C API.
* [hunspell-i18n](https://github.com/romanbsd/hunspell) ⭐ 4 | 🐛 0 | 🌐 C | 📅 2012-08-15 -
  Ruby bindings to the standard [Hunspell](https://hunspell.github.io/) Spell Checker.

### Text Alignment

* [alignment](https://github.com/povilasjurcys/alignment) ⭐ 1 | 🐛 0 | 🌐 C | 📅 2014-06-07 -
  Alignment routines for bilingual texts (Gale-Church implementation).

### Machine Translation

* [google-api-client](https://github.com/googleapis/google-api-ruby-client) ⭐ 2,896 | 🐛 41 | 🌐 Ruby | 📅 2026-08-23 -
  Google API Ruby Client.
* [termit](https://github.com/pawurb/termit) ⚠️ Archived -
  Google Translate with speech synthesis in your terminal.
* [microsoft\_translator](https://github.com/ikayzo/microsoft_translator) ⭐ 22 | 🐛 1 | 🌐 Ruby | 📅 2017-05-10 -
  Ruby client for the microsoft translator API.
* [zipf](https://github.com/pks/zipf) ⭐ 4 | 🐛 0 | 🌐 Ruby | 📅 2016-03-06 -
  implementation of BLEU and other base algorithms.

### Sentiment Analysis

* [stimmung](https://github.com/pachacamac/stimmung) ⭐ 19 | 🐛 0 | 🌐 Ruby | 📅 2016-04-24 -
  Semantic Polarity based on the
  [SentiWS](http://wortschatz.uni-leipzig.de/en/download) lexicon.

### Numbers, Dates, and Time Parsing

* [chronic](https://github.com/mojombo/chronic) ⭐ 3,253 | 🐛 148 | 🌐 Ruby | 📅 2023-09-28 -
  Pure Ruby natural language date parser.
* [chronic\_duration](https://github.com/henrypoydar/chronic_duration) ⚠️ Archived -
  Pure Ruby parser for elapsed time.
* [kronic](https://github.com/xaviershay/kronic) ⭐ 149 | 🐛 1 | 🌐 Ruby | 📅 2014-08-10 -
  Methods for parsing and formatting human readable dates.
* [nickel](https://github.com/iainbeeston/nickel) ⭐ 118 | 🐛 21 | 🌐 Ruby | 📅 2017-10-31 -
  Extracts date, time, and message information from naturally worded text.
* [tickle](https://github.com/yb66/tickle) ⭐ 83 | 🐛 10 | 🌐 Ruby | 📅 2020-09-18 -
  Parser for recurring and repeating events.
* [numerizer](https://github.com/jduff/numerizer) ⭐ 38 | 🐛 6 | 🌐 Ruby | 📅 2023-02-05 -
  Ruby parser for English number expressions.
* [chronic\_between](https://github.com/jrobertson/chronic_between) ⭐ 28 | 🐛 0 | 🌐 Ruby | 📅 2021-06-20 -
  Simple Ruby natural language parser for date and time ranges.

### Named Entity Recognition

* [ruby-nlp](https://github.com/tiendung/ruby-nlp) ⭐ 92 | 🐛 0 | 🌐 Ruby | 📅 2014-08-05 -
  Ruby Binding for Stanford Pos-Tagger and Name Entity Recognizer.
* [ruby-ner](https://github.com/mblongii/ruby-ner) ⭐ 19 | 🐛 1 | 🌐 Ruby | 📅 2022-12-16 -
  Named Entity Recognition with Stanford NER and Ruby.

### Text-to-Speech-to-Text

* [pocketsphinx-ruby](https://github.com/watsonbox/pocketsphinx-ruby) ⭐ 257 | 🐛 9 | 🌐 Ruby | 📅 2017-07-25 -
  Pocketsphinx bindings.
* [espeak-ruby](https://github.com/dejan/espeak-ruby) ⭐ 197 | 🐛 4 | 🌐 Ruby | 📅 2026-04-02 -
  Small Ruby API for utilizing 'espeak' and 'lame' to create text-to-speech mp3 files.
* [tts](https://github.com/c2h2/tts) ⭐ 94 | 🐛 7 | 🌐 Ruby | 📅 2022-10-20 -
  Text-to-Speech conversion using the Google translate service.
* [att\_speech](https://github.com/adhearsion/att_speech) ⭐ 20 | 🐛 3 | 🌐 Ruby | 📅 2014-03-21 -
  Ruby wrapper over the AT\&T Speech API for speech to text.

## Dialog Agents, Assistants, and Chatbots

* [lita](https://github.com/litaio/lita) ⚠️ Archived -
  Highly extensible chat operation bot framework written with persistent storage on [Redis](https://redis.io/).
* [chatterbot](https://github.com/muffinista/chatterbot) ⚠️ Archived -
  Straightforward ruby-based Twitter Bot Framework, using OAuth to authenticate.

## Linguistic Resources

* [wordnet](https://github.com/ged/ruby-wordnet/blob/master/README.rdoc) ⭐ 140 | 🐛 0 | 🌐 Ruby | 📅 2023-05-10 -
  Performance tuned bindings for the [Princeton WordNet®](https://wordnet.princeton.edu/).
* [rwordnet](https://github.com/doches/rwordnet) ⭐ 91 | 🐛 5 | 🌐 Ruby | 📅 2019-08-22 -
  Pure Ruby self contained API library for the [Princeton WordNet®](https://wordnet.princeton.edu/).

## Machine Learning Libraries

[Machine Learning](https://en.wikipedia.org/wiki/Machine_learning) Algorithms
in pure Ruby or written in other programming languages with appropriate bindings
for Ruby.

For more up-to-date list please look at the [Awesome ML with Ruby][ml-with-ruby] list.

* [decisiontree](https://github.com/igrigorik/decisiontree) ⭐ 1,490 | 🐛 10 | 🌐 Ruby | 📅 2018-10-31 -
  Decision Tree ID3 Algorithm in pure Ruby <sup>\[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>.
* [classifier-reborn](https://github.com/jekyll/classifier-reborn) ⭐ 558 | 🐛 28 | 🌐 Ruby | 📅 2024-05-27 -
  General classifier module to allow Bayesian and other types of classifications.
* [ruby-fann](https://github.com/tangledpath/ruby-fann) ⭐ 506 | 🐛 1 | 🌐 C | 📅 2024-03-25 -
  Ruby bindings to the [Fast Artificial Neural Network Library (FANN)](http://leenissen.dk/fann/wp/).
* [rb-libsvm](https://github.com/febeling/rb-libsvm) ⭐ 279 | 🐛 2 | 🌐 C++ | 📅 2023-12-07 -
  Support Vector Machines with Ruby.
* [nbayes](https://github.com/oasic/nbayes) ⭐ 155 | 🐛 3 | 🌐 Ruby | 📅 2024-02-12 -
  Full-featured, Ruby implementation of Naive Bayes.
* [lda-ruby](https://github.com/ealdent/lda-ruby) ⭐ 134 | 🐛 0 | 🌐 Ruby | 📅 2026-05-04 -
  Ruby implementation of the [LDA](https://en.wikipedia.org/wiki/Latent_Dirichlet_allocation)
  (Latent Dirichlet Allocation) for automatic Topic Modelling and Document Clustering.
* [liblinear-ruby-swig](https://github.com/tomz/liblinear-ruby-swig) ⭐ 83 | 🐛 5 | 🌐 C++ | 📅 2023-06-27 -
  Ruby interface to LIBLINEAR (much more efficient than LIBSVM for text classification).
* [weka](https://github.com/paulgoetze/weka-jruby) ⭐ 65 | 🐛 0 | 🌐 Ruby | 📅 2026-06-24 -
  JRuby bindings for Weka, different ML algorithms implemented through Weka.
* [naive\_bayes](https://github.com/reddavis/Naive-Bayes) ⭐ 49 | 🐛 6 | 🌐 Ruby | 📅 2012-01-29 -
  Simple Naive Bayes classifier.
* [linnaeus](https://github.com/djcp/linnaeus) ⭐ 37 | 🐛 2 | 🌐 Ruby | 📅 2015-12-26 -
  Redis-backed Bayesian classifier.
* [omnicat-bayes](https://github.com/mustafaturan/omnicat-bayes) ⭐ 31 | 🐛 1 | 🌐 Ruby | 📅 2021-01-13 -
  Naive Bayes text classification implementation as an OmniCat classifier strategy.
* [omnicat](https://github.com/mustafaturan/omnicat) ⭐ 11 | 🐛 0 | 🌐 Ruby | 📅 2021-01-13 -
  Generalized rack framework for text classifications.
* [maxent\_string\_classifier](https://github.com/mccraigmccraig/maxent_string_classifier) ⭐ 9 | 🐛 0 | 🌐 Ruby | 📅 2009-07-06 -
  JRuby maximum entropy classifier for string data, based on the OpenNLP Maxent framework.
* [rtimbl](https://github.com/maspwr/rtimbl) ⭐ 5 | 🐛 0 | 🌐 C++ | 📅 2009-10-23 -
  Memory based learners from the Timbl framework.
* [rblearn](https://github.com/himkt/rblearn) ⭐ 2 | 🐛 0 | 🌐 Ruby | 📅 2016-08-03 - Feature Extraction and Crossvalidation library.

## Data Visualization

Please refer to the [Data Visualization](https://github.com/arbox/data-science-with-ruby#visualization) ⭐ 720 | 🐛 1 | 🌐 Ruby | 📅 2023-07-19
section on the [Data Science with Ruby][ds-with-ruby] list.

## Optical Character Recognition

* [tesseract-ocr](https://github.com/meh/ruby-tesseract-ocr) ⭐ 636 | 🐛 24 | 🌐 Ruby | 📅 2017-07-02 -
  FFI based wrapper over the [Tesseract OCR Engine](https://github.com/tesseract-ocr/tesseract) ⭐ 76,234 | 🐛 490 | 🌐 C++ | 📅 2026-08-25.

## Text Extraction

* [yomu](https://github.com/yomurb/yomu) ⭐ 504 | 🐛 27 | 🌐 Ruby | 📅 2023-03-28 -
  library for extracting text and metadata from files and documents
  using the [Apache Tika](https://tika.apache.org/) content analysis toolkit.

## Full Text Search, Information Retrieval, Indexing

* [elasticsearch-rails](https://github.com/elastic/elasticsearch-rails) ⭐ 3,084 | 🐛 53 | 🌐 Ruby | 📅 2025-10-08 -
  Ruby and Rails integrations for [Elasticsearch](https://www.elastic.co/).
* [sunspot](https://github.com/sunspot/sunspot) ⭐ 2,979 | 🐛 152 | 🌐 JavaScript | 📅 2026-08-18 -
  Rails centric client for [Apache Solr](http://lucene.apache.org/solr/).
* [google-api-client](https://github.com/googleapis/google-api-ruby-client) ⭐ 2,896 | 🐛 41 | 🌐 Ruby | 📅 2026-08-23 -
  Ruby API library for [Google](https://developers.google.com/api-client-library/ruby/) services.
* [elasticsearch](https://github.com/elastic/elasticsearch-ruby/tree/master/elasticsearch) ⭐ 1,977 | 🐛 17 | 🌐 Ruby | 📅 2026-08-24 -
  Ruby client and API for [Elasticsearch](https://www.elastic.co/).
* [thinking-sphinx](https://github.com/pat/thinking-sphinx) ⭐ 1,620 | 🐛 18 | 🌐 Ruby | 📅 2026-01-11 -
  [Active Record](https://guides.rubyonrails.org/active_record_basics.html)
  plugin for using [Sphinx](http://sphinxsearch.com/) in (not only) Rails based projects.
* [rsolr](https://github.com/rsolr/rsolr) ⭐ 422 | 🐛 25 | 🌐 Ruby | 📅 2026-06-26 -
  Ruby and Rails client library for [Apache Solr](http://lucene.apache.org/solr/).

## Language Aware String Manipulation

Libraries for language aware string manipulation, i.e. search, pattern matching,
case conversion, transcoding, regular expressions which need information about
the underlying language.

* [active\_support](https://github.com/rails/rails/tree/master/activesupport/lib/active_support) ⭐ 58,727 | 🐛 1,605 | 🌐 Ruby | 📅 2026-08-28 -
  RoR `ActiveSupport` gem has various string extensions that can handle case.
* [fuzzy\_match](https://github.com/seamusabshere/fuzzy_match) ⭐ 686 | 🐛 18 | 🌐 Ruby | 📅 2021-05-11 -
  Fuzzy string comparison with Distance measures and Regular Expression.
* [verbal\_expressions](https://github.com/ryan-endacott/verbal_expressions) ⭐ 568 | 🐛 11 | 🌐 Ruby | 📅 2023-01-09 -
  Make difficult regular expressions easy.
* [regexp-examples](https://github.com/tom-lord/regexp-examples) ⭐ 519 | 🐛 9 | 🌐 Ruby | 📅 2024-05-20 -
  Generate strings that match a given regular expression.
* [fuzzy-string-match](https://github.com/kiyoka/fuzzy-string-match) ⭐ 287 | 🐛 10 | 🌐 Ruby | 📅 2020-02-29 -
  Fuzzy string matching library for Ruby.
* [re2](https://github.com/mudge/re2) ⭐ 155 | 🐛 3 | 🌐 Ruby | 📅 2026-07-01 -
  hight-speed Regular Expression library for Text Mining and Text Extraction.
* [CommonRegexRuby](https://github.com/talyssonoc/CommonRegexRuby) ⭐ 80 | 🐛 2 | 🌐 Ruby | 📅 2021-11-29 -
  Find a lot of kinds of common information in a string.
* [unicode](https://github.com/blackwinter/unicode) ⭐ 79 | 🐛 1 | 🌐 C | 📅 2024-06-20 -
  Unicode normalization library.
* [fuzzy\_tools](https://github.com/brianhempel/fuzzy_tools) ⭐ 23 | 🐛 4 | 🌐 Ruby | 📅 2025-11-15 -
  Toolset for fuzzy searches in Ruby tuned for accuracy.
* [iuliia](https://github.com/adnikiforov/iuliia-rb) ⭐ 10 | 🐛 1 | 🌐 Ruby | 📅 2021-11-25 —
  transliteration Cyrillic to Latin in many possible ways (defined by the [reference implementation](https://github.com/nalgeon/iuliia) ⚠️ Archived).
* [translit\_kit](https://github.com/AnalyzePlatypus/TranslitKit) ⭐ 7 | 🐛 0 | 🌐 Ruby | 📅 2022-12-15 -
  Transliterate Hebrew & Yiddish text into Latin characters.
* [u](http://disu.se/software/u-1.0/) -
  U extends Ruby’s Unicode support.
* [regex\_sample](https://github.com/mochizukikotaro/regex_sample) -
  sample string generation from a given Regular Expression.

## Articles, Posts, Talks, and Presentations

* 2019
  * *Extracting Text From Images Using Ruby* by [aonemd](https://twitter.com/aonemd) <sup>\[[post](https://aonemd.github.io/blog/extracting-text-from-images-using-ruby) |
    [code](https://gist.github.com/aonemd/7bb3c4760d9e47a9ce8e270198cb40a0)]</sup>
* 2018
  * *Natural Language Processing and Tweet Sentiment Analysis* by [Cassandra Corrales](https://twitter.com/casita305) <sup>\[[post](https://medium.com/@cmcorrales3/natural-language-processing-and-tweet-sentiment-analysis-fa1edbb5ddd5)]</sup>
* 2017
  * *The Google NLP API Meets Ruby* by [Aja Hammerly](https://twitter.com/the_thagomizer) <sup>\[[post](http://www.thagomizer.com/blog/2017/04/13/the-google-nlp-api-meets-ruby.html)]</sup>
  * *Syntax Isn't Everything: NLP For Rubyists* by [Aja Hammerly](https://twitter.com/the_thagomizer) <sup>\[[slides](http://www.thagomizer.com/files/NLP_RailsConf2017.pdf)]</sup>
  * *Scientific Computing on JRuby* by [Prasun Anand](https://twitter.com/prasun_anand) <sup>\[[slides](https://www.slideshare.net/PrasunAnand2/fosdem2017-scientific-computing-on-jruby) |
    [video](https://ftp.fau.de/fosdem/2017/K.4.201/ruby_scientific_computing_on_jruby.mp4) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computing-on-jruby) |
    [slides](https://www.slideshare.net/PrasunAnand2/scientific-computation-on-jruby)]</sup>
  * *Unicode Normalization in Ruby* by [Starr Horne](https://twitter.com/starrhorne) <sup>\[[post](https://blog.honeybadger.io/ruby_unicode_normalization/)]</sup>
* 2016
  * *Quickly Create a Telegram Bot in Ruby* by [Ardian Haxha](https://twitter.com/ArdianHaxha) <sup>\[[tutorial](https://www.sitepoint.com/quickly-create-a-telegram-bot-in-ruby/)]</sup>
  * *Deep Learning: An Introduction for Ruby Developers* by [Geoffrey Litt](https://twitter.com/geoffreylitt) <sup>\[[slides](https://speakerdeck.com/geoffreylitt/deep-learning-an-introduction-for-ruby-developers)]</sup>
  * *How I made a pure-Ruby word2vec program more than 3x faster* by [Kei Sawada](https://twitter.com/remore) <sup>\[[slides](https://speakerdeck.com/remore/how-i-made-a-pure-ruby-word2vec-program-more-than-3x-faster)]</sup>
  * *Dōmo arigatō, Mr. Roboto: Machine Learning with Ruby* by [Eric Weinstein](https://twitter.com/ericqweinstein) <sup>\[[slides](https://speakerdeck.com/ericqweinstein/domo-arigato-mr-roboto-machine-learning-with-ruby) | [video](https://www.youtube.com/watch?v=T1nFQ49TyeA)]</sup>
* 2015
  * *N-gram Analysis for Fun and Profit* by [Jesus Castello](https://github.com/matugm) <sup>\[[tutorial](https://www.rubyguides.com/2015/09/ngram-analysis-ruby/)]</sup>
  * *Machine Learning made simple with Ruby* by [Lorenzo Masini](https://github.com/rugginoso) <sup>\[[tutorial](https://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]</sup>
  * *Using Ruby Machine Learning to Find Paris Hilton Quotes* by [Rick Carlino](https://github.com/RickCarlino) <sup>\[[tutorial](http://web.archive.org/web/20160414072324/http://datamelon.io/blog/2015/using-ruby-machine-learning-id-paris-hilton-quotes.html)]</sup>
  * *Exploring Natural Language Processing in Ruby* by [Kevin Dias](https://github.com/diasks2) <sup>\[[slides](https://www.slideshare.net/diasks2/exploring-natural-language-processing-in-ruby)]</sup>
  * *Machine Learning made simple with Ruby* by [Lorenzo Masini](https://twitter.com/rugginoso) <sup>\[[post](https://www.leanpanda.com/blog/2015/08/24/machine-learning-automatic-classification/)]</sup>
  * *Practical Data Science in Ruby* by Bobby Grayson <sup>\[[slides](http://slides.com/bobbygrayson/p#/)]</sup>
* 2014
  * *Demystifying Data Science: Analyzing Conference Talks with Rails and Ngrams* by
    [Todd Schneider](https://github.com/toddwschneider) <sup>\[[video](https://www.youtube.com/watch?v=2ZDCxwB29Bg) | [code](https://github.com/Genius/abstractogram) ⚠️ Archived]</sup>
  * *Natural Language Parsing with Ruby* by [Glauco Custódio](https://github.com/glaucocustodio) <sup>\[[tutorial](http://glaucocustodio.github.io/2014/11/10/natural-language-parsing-with-ruby/)]</sup>
  * *Natural Language Processing with Ruby* by [Konstantin Tennhard](https://github.com/t6d) <sup>\[[video](https://www.youtube.com/watch?v=5u86qVh8r0M) | [video](https://www.youtube.com/watch?v=oFmy_QBQ5DU) |
    [video](https://www.youtube.com/watch?v=sPkeeWnsMn0) |
    [slides](http://euruko2013.org/speakers/presentations/natural_language_processing_with_ruby_and_opennlp-tennhard.pdf)]</sup>
* 2013
  * *Natural Language Processing with Ruby: n-grams* by [Nathan Kleyn](https://github.com/nathankleyn) <sup>\[[tutorial](https://www.sitepoint.com/natural-language-processing-ruby-n-grams/) |
    [code](https://github.com/nathankleyn/ruby-nlp) ⭐ 33 | 🐛 0 | 🌐 Ruby | 📅 2013-09-14]</sup>
  * *How to parse 'go' - Natural Language Processing in Ruby* by
    [Tom Cartwright](https://twitter.com/tomcartwrightuk) <sup>\[[slides](https://www.slideshare.net/TomCartwright/natual-language-processing-in-ruby) |
    [video](https://skillsmatter.com/skillscasts/4883-how-to-parse-go)]</sup>
  * *Natural Language Processing in Ruby* by [Brandon Black](https://twitter.com/brandonmblack) <sup>\[[slides](https://speakerdeck.com/brandonblack/natural-language-processing-in-ruby) |
    [video](http://confreaks.tv/videos/railsconf2013-natural-language-processing-with-ruby)]</sup>
  * *Seeking Lovecraft, Part 1: An introduction to NLP and the Treat Gem* by
    [Robert Qualls](https://github.com/rlqualls) <sup>\[[tutorial](https://www.sitepoint.com/seeking-lovecraft-part-1-an-introduction-to-nlp-and-the-treat-gem/)]</sup>
* 2012
  * *Machine Learning with Ruby, Part One* by [Vasily Vasinov](https://twitter.com/vasinov) <sup>\[[tutorial](http://www.vasinov.com/blog/machine-learning-with-ruby-part-one/)]</sup>
* 2011
  * *Ruby one-liners* by [Benoit Hamelin](https://twitter.com/benoithamelin) <sup>\[[post](http://benoithamelin.tumblr.com/ruby1line)]</sup>
  * *Clustering in Ruby* by [Colin Drake](https://twitter.com/colinfdrake) <sup>\[[post](https://colindrake.me/post/k-means-clustering-in-ruby/)/)]</sup>
* 2010
  * *bayes\_motel – Bayesian classification for Ruby* by [Mike Perham](https://twitter.com/mperham) <sup>\[[post](http://www.mikeperham.com/2010/04/28/bayes_motel-bayesian-classification-for-ruby/)]</sup>
* 2009
  * *Porting the UEA-Lite Stemmer to Ruby* by [Jason Adams](https://twitter.com/ealdent) <sup>\[[post](https://ealdent.wordpress.com/2009/07/16/porting-the-uea-lite-stemmer-to-ruby/)]</sup>
  * *NLP Resources for Ruby* by [Jason Adams](https://twitter.com/ealdent) <sup>\[[post](https://ealdent.wordpress.com/2009/09/13/nlp-resources-for-ruby/)]</sup>
* 2008
  * *Practical text classification with Ruby* by [Gleicon Moraes](https://twitter.com/gleicon) <sup>\[[post](https://zenmachine.wordpress.com/practical-text-classification-with-ruby/) |
    [code](https://github.com/gleicon/zenmachine) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2009-11-17]</sup>
  * *Support Vector Machines (SVM) in Ruby* by [Ilya Grigorik](https://twitter.com/igrigorik) <sup>\[[post](https://www.igvita.com/2008/01/07/support-vector-machines-svm-in-ruby/)]</sup>
* 2007
  * *Decision Tree Learning in Ruby* by [Ilya Grigorik](https://twitter.com/igrigorik) <sup>\[[post](https://www.igvita.com/2007/04/16/decision-tree-learning-in-ruby/)]</sup>
* 2006
  * *Speak My Language: Natural Language Processing With Ruby* by [Michael Granger](https://deveiate.org/resume.html) <sup>\[[slides](https://deveiate.org/misc/Speak-My-Language.pdf) |
    [write-up](http://blog.nicksieger.com/articles/2006/10/22/rubyconf-natural-language-generation-and-processing-in-ruby/) |
    [write-up](http://juixe.com/papers/RubyConf2006.pdf)]</sup>

## Projects and Code Examples

* [Words Counted](http://rubywordcount.com/) -
  examples of customizable word statistics powered by
  [words\_counted](https://github.com/abitdodgy/words_counted) ⭐ 165 | 🐛 7 | 🌐 Ruby | 📅 2021-10-28.
* [Going the Distance](https://github.com/schneems/going_the_distance) ⭐ 60 | 🐛 1 | 🌐 Ruby | 📅 2016-09-07 -
  Implementations of various distance algorithms with example calculations.
* [Named entity recognition with Stanford NER and Ruby](https://github.com/mblongii/ruby-ner) ⭐ 19 | 🐛 1 | 🌐 Ruby | 📅 2022-12-16 -
  NER Examples in Ruby and Java with some [explanations](https://web.archive.org/web/20120722225402/http://mblongii.com/2012/04/15/named-entity-recognition-with-stanford-ner-and-ruby/).
* [RSyntaxTree](https://yohasebe.com/rsyntaxtree/) -
  Web based demonstration of the syntactic tree visualization.

## Books

* [Miller, Rob](https://twitter.com/robmil/).
  *Text Processing with Ruby: Extract Value from the Data That Surrounds You.*
  Pragmatic Programmers, 2015. <sup>\[[link](https://www.amazon.com/Text-Processing-Ruby-Extract-Surrounds/dp/1680500708)]</sup>
* [Watson, Mark](https://twitter.com/mark_l_watson).
  *Scripting Intelligence: Web 3.0 Information Gathering and Processing.*
  APRESS, 2010. <sup>\[[link](https://www.amazon.de/Scripting-Intelligence-Information-Gathering-Processing/dp/1430223510)]</sup>
* [Watson, Mark](https://twitter.com/mark_l_watson).
  *Practical Semantic Web and Linked Data Applications.* Lulu, 2010. <sup>\[[link](http://www.lulu.com/shop/mark-watson/practical-semantic-web-and-linked-data-applications-java-edition/paperback/product-10915016.html)]</sup>

## Community

* [Reddit](https://www.reddit.com/r/LanguageTechnology/search?q=ruby\&restrict_sr=on)
* [Stack Overflow](https://stackoverflow.com/search?q=%5Bnlp%5D+and+%5Bruby%5D)
* [Twitter](https://twitter.com/search?q=Ruby%20NLP%20%23ruby%20OR%20%23nlproc%20OR%20%23rubynlp%20OR%20%23nlp\&src=typd\&lang=en)

## Needs your Help!

All projects in this section are really important for the community but need
more attention. Please if you have spare time and dedication spend some hours
on the code here.

* [ferret](https://github.com/dbalmain/ferret) ⭐ 280 | 🐛 10 | 🌐 C | 📅 2023-02-01 -
  Information Retrieval in C and Ruby.
* [summarize](https://github.com/ssoper/summarize) ⭐ 203 | 🐛 6 | 🌐 Ruby | 📅 2012-04-23 -
  Ruby native wrapper for [Open Text Summarizer](https://github.com/neopunisher/Open-Text-Summarizer) ⭐ 242 | 🐛 3 | 🌐 Shell | 📅 2018-10-21.

## Related Resources

* [Awesome TensorFlow](https://github.com/jtoy/awesome-tensorflow) ⭐ 17,549 | 🐛 34 | 📅 2026-02-08 -
  Machine Learning with TensorFlow libraries.
* [Awesome Ruby](https://github.com/markets/awesome-ruby#natural-language-processing) ⭐ 14,147 | 🐛 8 | 📅 2026-08-13 -
  Among other awesome items a short list of NLP related projects.
* [Awesome OCR](https://github.com/kba/awesome-ocr) ⭐ 3,119 | 🐛 64 | 📅 2024-07-06 -
  Multitude of OCR (Optical Character Recognition) resources.
* [Speech and Natural Language Processing](https://github.com/edobashira/speech-language-processing) ⭐ 2,225 | 🐛 19 | 📅 2019-04-02 -
  General List of NLP related resources (mostly not for Ruby programmers).
* [Ruby NLP](https://github.com/diasks2/ruby-nlp) ⭐ 1,285 | 🐛 2 | 📅 2023-03-05 -
  State-of-Art collection of Ruby libraries for NLP.
* [iRuby](https://github.com/SciRuby/iruby) ⭐ 924 | 🐛 49 | 🌐 Ruby | 📅 2026-06-30 - IRuby kernel for Jupyter (formelly IPython).
* [Neural Machine Translation Implementations](https://github.com/jonsafari/nmt-list) ⭐ 364 | 🐛 3 | 📅 2022-07-27
* [Scientific Ruby](http://sciruby.com/) -
  Linear Algebra, Visualization and Scientific Computing for Ruby.
* <a name="imagemagic"></a>
  [ImageMagick](https://imagemagick.org/index.php)

## License

[![Creative Commons Zero 1.0](http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/) `Awesome NLP with Ruby` by [Andrei Beliankou](https://github.com/arbox) and
[Contributors](https://github.com/arbox/nlp-with-ruby/graphs/contributors) ⭐ 1,076 | 🐛 7 | 🌐 Ruby | 📅 2023-06-27.

To the extent possible under law, the person who associated CC0 with
`Awesome NLP with Ruby` has waived all copyright and related or neighboring rights
to `Awesome NLP with Ruby`.

You should have received a copy of the CC0 legalcode along with this
work. If not, see <https://creativecommons.org/publicdomain/zero/1.0/>.

<!--- Links --->

[ruby]: https://www.ruby-lang.org/en/

[motivation]: https://github.com/arbox/nlp-with-ruby/blob/master/motivation.md

[faq]: https://github.com/arbox/nlp-with-ruby/blob/master/FAQ.md

[ds-with-ruby]: https://github.com/arbox/data-science-with-ruby

[ml-with-ruby]: https://github.com/arbox/machine-learning-with-ruby

[change-pr]: https://github.com/RichardLitt/knowledge/blob/master/github/amending-a-commit-guide.md

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-28._
