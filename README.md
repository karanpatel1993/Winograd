# Winograd’s minimal filtering algorithms
Recently, small convolutional filter sizes have become an important component in convolutional neural networks such as Google’s AlphaGo network or Microsoft’s deep residual networks. While most convolutions are computed with the fast fourier transform (FFT) algorithm, the rising prominence of small 3×3 filter sizes makes the way for a lesser known technique specialized for small filter sizes: Winograd’s minimal filtering algorithms [(Lavin and Gray, 2015)](http://arxiv.org/abs/1509.09308).  

In this project, we implemented the Winograd minimal filtering algorithm on the [SketchCode](https://github.com/ashnkumar/sketch-code) model.

# Results:
| |Normal Convolution|Winograd Convolution|
|:-:|:-:|:-:|
|Parameters |139,723,686  |7,587,814 
|Execution time | 219.33 min (approx)| 196.66 min (approx)
