# KCAGNet
This is our Tensorflow implementation for the paper:

title: Traditional Chinese herb recommendation using an attentive graph network integrating knowledge graphs and co-occurrence relationships

Author: Dr. Xiang Wang, Dr. Makhmut Yerlan

## Dataset

* `fianl_kg.txt`
  * Used to construct the knowledge graph.
  * Each line contains a triple in the format `headId relationId tailId`, representing the head entity ID, relation ID, and tail entity ID, respectively.

* `symPair4.txt`
  * Used to construct the symptom–symptom homogeneous graph.
  * Each line contains a pair of symptom IDs in the format `symptomId symptomId`, representing an edge between two symptom nodes.

* `herbPair40.txt`
  * Used to construct the herb–herb homogeneous graph.
  * Each line contains a pair of herb IDs in the format `herbId herbId`, representing an edge between two herb nodes.
