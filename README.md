# Knowledgebase

* [Word2Vec and FastText Word Embedding with Gensim](https://towardsdatascience.com/word-embedding-with-word2vec-and-fasttext-a209c1d3e12c)
* [Gensim Tut](https://radimrehurek.com/gensim/models/word2vec.html)
* [uMap - Visualization of high-dimension-vectors](https://github.com/lmcinnes/umap)
* fast approximate nearest neighbor search
  * [Hnswlib](https://github.com/nmslib/hnswlib)
  * [SPTAG](https://github.com/microsoft/SPTAG)


# Interesting approaches worth to investigate further

* [Word Embeddings for Entity annotated texts](https://dbs.ifi.uni-heidelberg.de/files/Team/aspitz/publications/Almasian_et_al_2019_Word_Embeddings_for_Entity-annotated_Texts.pdf)
* [Vector Embedding of Wikipedia Concepts and Entities](https://arxiv.org/abs/1702.03470)
* Probing for Semantic Classes: Diagnosing the Meaning Content of Word Embeddings ([blog post](https://www.microsoft.com/en-us/research/blog/analyzing-ambiguity-and-word-embeddings-by-probing-semantic-classes/), [paper](https://www.microsoft.com/en-us/research/publication/probing-for-semantic-classes-diagnosing-the-meaning-content-of-word-embeddings/))

# Survey Paper

* [A Survey of Word Embeddings Evaluation Methods](http://arxiv.org/abs/1801.09536)

# Tools

## Entity Linking
* OpenTapioca ([Demo](https://opentapioca.org/), [Source Code](https://github.com/wetneb/opentapioca), [Paper](https://arxiv.org/abs/1904.09131))
* [Wikilinks NEL](https://github.com/wikilinks/nel)
* [DBpedia spotlight](https://www.dbpedia-spotlight.org/demo/)
* [ambiverse-nlu](https://github.com/ambiverse-nlu/ambiverse-nlu)

# Benchmarking Paper

* [Evaluation methods for unsupervised word embeddings](https://www.aclweb.org/anthology/D15-1036)
* [WordRep: A Benchmark for Research on Learning Word Representations](https://arxiv.org/pdf/1407.1640.pdf)
* [Word Embeddings Evaluation and Combination](http://www.lrec-conf.org/proceedings/lrec2016/pdf/392_Paper.pdf)
* [Automatic generation of tunable analogy benchmarks for word representations
](https://www.ideals.illinois.edu/handle/2142/92859)

# BigGraph Facebook 
Trained Embeddings on Knowledge-Graph from WikiData as Knowledgebase
> PyTorch-BigGraph (PBG) is a distributed system for learning graph embeddings for large graphs, particularly big web interaction graphs with up to billions of entities and trillions of edges.
> PBG was introduced in the PyTorch-BigGraph: A Large-scale Graph Embedding Framework paper, presented at the SysML conference in 2019.
* [PyTorch-BigGraph: A Large-Scale Graph Embedding System](https://www.sysml.cc/doc/2019/71.pdf)
* [Source Code](https://github.com/facebookresearch/PyTorch-BigGraph)
* [Training Data Source](https://dl.fbaipublicfiles.com/starspace/fb15k.tgz)
* [Pre-Trained Embedding (36GiB, gzip-compressed)](https://dl.fbaipublicfiles.com/torchbiggraph/wikidata_translation_v1.tsv.gz)

