---
layout: post
title:      "Why to Use Group Normalization "
date:       2019-05-22 16:49:55 +0000
permalink:  why_to_use_group_normalization
---

Batch normalization is a ground breaking development in the training and testing of data in deep learning. Batch normalization enables networks to train, but runs into problems with normalization. When using batch normalization errors in normalization increase dramatically when the batch size becomes smaller. This is caused by inaccurate batch statistics estimates. This normalization error limits the usage for training larger models using batch normalization. This paper will discuss alternatives to this, mainly group normalization. Group normalization works by dividing the channels into groups and runs within each group, making the computation independent of batch sizes. This means the accuracy is more stable for a wider range of batch sizes; outperforming other normalization variants. 

Batch normalization is an established, effective tool within deep learning. It works by normalizing its features using the mean and variance. At the time the foundation of batch normalization is a state of the art computer vision algorithm, though it has many drawbacks. The biggest issue faced when using batch normalization is it requires a large batch size in order for it to run accurately. When using a BN using a small batch sizes leads to inaccurate estimations of the statistics, which there by greatly increases the model error. This means the system will be compromised between the model’s design and batch size. 

This is where group normalization comes up as a simple alternative. Group normalization works as a layer that divides channels into groups and normalizes their features within each group. By doing this, the batch dimension does not affect the outcome. For example, a batch size of 2 samples has a lower error when using group normalizations versus batch normalization. When using a large sample batch size both group normalization and batch normalization have comparable errors, though GN shows improved results. By comparing group normalization with batch can further shows how GN performs better. For example, when using 32 images, batch normalization works reasonably well as does group normalization. 

When dealing with small batch sizes batch normalization benefits from randomness under some situations, but the error will increase when the batch size gets smaller and the uncertainty becomes larger. Meaning the batch normalization error will greatly increase with smaller batches as we discussed earlier. This is why group normalization is the better choice. Group normalization acts more stable and is not effected by the batch size. When looking at graphs, you can visually see how GN has similar curves across a wide range of batch sizes. This benefits the normalization process, which is essential for controlling the distribution of features. 

This is all important to your business because it will help it run more efficiently and perform better. By using group normalization over batch normalization you are removing the possibility of having a constraint for the batch size. By not being impacted by batch size, you are able to normalize the data regardless of size. You will also have the ability to train high capacity models, which will avoid bottle necking that typically cause the process to run slower. Overall group normalization works as well as batch normalization with large batches, and outperforms when working with small batches. This means by switching to the group normalization process for training data, you will be able to use one system. This will streamline the process and save you time, which will also save you money.
	



