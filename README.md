# VFE
Variational Feature Encoder for Image Classifiers

Transfer Learning (TL) plays a vital role in im-
age classification systems based on Deep Convolutional Neural
Networks (DCNNs). Systems employing such technique may be
susceptible to distortions on images, motivating the development
of robust DCNNs capable of facing these problems. Unfortu-
nately, changes in the architecture of DCNNs are sometimes
specific to a kind of distortion and result in models that need
to be retrained from scratch. This work proposes the use of
autoencoders as intermediaries between pre-trained DCNNs and
classifiers, delegating the denoising task to this architecture
trained to encode feature maps. The classifiers are then trained
to map the inputs from the autoencoder latent spaces to their
respective classes. Models employing this approach achieved 3%
to 4% increase in accuracy and 50% to 70% reduction in loss on
the CIFAR10 and CIFAR100 datasets. The results also showed an
up to 80% reduction in loss and up to 15% increase in accuracy
for images with unseen distortions compared to the classical TL
approach. This work improves classification results and increases
robustness to distortions in a straightforward manner.
