# Deep-Fake-Recognition

The goal of this study is to identify deep fake images using a variety of facial images. Our first approach uses a transformer-based architecture for deep fake recognition. The Vision Transformer, sometimes referred to as ViT, is a methodology for categorizing images that applies a Transformer-like design to certain portions of the image. After an image has been partitioned into fixed-size patch-es, each of which has been linearly embedded and position embeddings added, the resultant sequence of vectors is provided to a traditional Transformer encod-er. To do classification, the traditional approach of including an additional, learnable "classification token" in the sequence is used.

Our second approach is a variation of our initial pipeline, where an Efficient net B07 architecture is used as a classifier instead of the vision transformer for a comparative study.

