Project for the course of AI for Automotive

Made by:
- Federico Cocchi
- Paula Klinke


In past years the development of artificial intelligence models with a Transformerlike
architecture took a big step forward in sequence modeling tasks. Only recently the
scientific community starts to investigate the use of Transformer architectures also on
multi-modal domains, like Image captioning. In this context, our work is located.
Our models were applied specifically to the automotive domain. To do so a dataset
called ’cc automotive’ was created, with about 155K triplets of data correlated with this
domain.
The architecture used is a CLIP model to encode the relation of image regions. Taking
those image regions a Memory - Transformer structure composed of an encoder and
decoder to generate the final captions, related to the input image is used.
The Image captioning model can describe in natural language the concepts in the
images, taking into account also the correlation among the objects and the semantic
information.
Finally one can say that models trained on automotive related data perform better in
the specific domain than models trained on a general dataset.

![AI4A.jpg]()
