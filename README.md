# Normalizingflow_point_MAE
### Target: Literature review and finding ideas

[PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation](https://arxiv.org/abs/1612.00593)
 
Notes and ideas
The basic architecture of our network is surprisingly simple as in the initial stages each point is processed identically and independently.
Why Independently?
Key to our approach is the use of a single symmetric function, max pooling.

[Masked Autoencoders for Point Cloud Self-supervised Learning](https://arxiv.org/abs/2203.06604)

The basic idea of this paper is using the self-supervised learning to learns the latent information.

It is usually done by designing a pretext task to pre-train the model, then fine-tune on down- stream tasks. 
