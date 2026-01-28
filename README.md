This is a tiny CLIP-style Vision-Language Model(VLM).

It has two separate encoders - one for images and one for text.

Both encoders map their inputs into a common embedding space of dimension 64 (or any other dimension we choose).

The goal is to make matching image-text pairs lie close together in the space

These embeddings are then compared using Contrastive Loss, ensuring that the matching image-text pairs are closer in the common embedding space.
