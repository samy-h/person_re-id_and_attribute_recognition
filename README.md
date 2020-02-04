# Attribute detection and person re-identification

Based on the paper [Improving Person Re-identification by Attribute and Identity Learning.
](https://arxiv.org/pdf/1703.07220.pdf)

### Dataset: Market-1501

Contains:
- 19,732 images for 751 identities -> training set
- 13,328 images for 750 identities -> test set
- 27 attributes for each image

### Objective

Using tensorﬂow.keras implement the algorithm of re-identiﬁcation described in the article _Lin et al. - Improving Person Re-identiﬁcation by Attribute and Identity Learning - 2019_.

1. Using a pre-trained resnet50 on imagenet, implement the algorithm of classiﬁcation by Attribute.

2. Implement a first algorithm of re-identiﬁcation by combining the classiﬁcation of attributes with an additional fully-connected layer for the identiﬁcation.

3. Increase the dataset data during training according to the protocol described on page 7 of the article ("Randomly cropping and horizontal ﬂipping are applied on the input images during training.").

4. Implement a system to compare 2 feature vectors (Euclidean distance is a good starting point). 

5. **Bonus**: Implement the attribute reweighting module "Attributes Re-Weighting".
