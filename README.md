# Revisiting-Pooling-in-CNNs

This repository implements RNNPool<sup>[1]</sup> and SoftPool<sup>[2]</sup>. Both of the pooling methods are proposed with the intent of reducing information loss induced by traditional downsampling methods (such as AveragePooling, MaxPooling) as well as to reduce the compute requirements of CNNs on tiny devices. Interested reader is encouraged to check out [this blog post by Microsoft](https://www.microsoft.com/en-us/research/blog/seeing-on-tiny-battery-powered-microcontrollers-with-rnnpool/?OCID=msr_blog_RNNPool_NeurIPS_tw) that shed some light on the limitations of the existing pooling methods. 

**Note** that I am yet to add the implementation of RNNPool. 

For more details on the implementation and usage, please check out the notebooks. 

## Citation
[1] Saha, Oindrila, et al. “RNNPool: Efficient Non-Linear Pooling for RAM Constrained Inference.” ArXiv:2002.11921 [Cs], Oct. 2020. arXiv.org, http://arxiv.org/abs/2002.11921. <br>
[2] Stergiou, Alexandros, et al. “Refining Activation Downsampling with SoftPool.” ArXiv:2101.00440 [Cs], Jan. 2021. arXiv.org, http://arxiv.org/abs/2101.00440.
