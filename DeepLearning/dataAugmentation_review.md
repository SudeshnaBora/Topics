# A review of medical image data augmentation techniques fordeep learning applications

Phillip Chlap,Hang Min,Nym Vandenberg,Jason Dowling,Lois Holloway and Ann ette Haworth
---

**Requirement:** Dearth of well annotated medical data for training deep learning algorithms.

**what this paper does:** Review of data augmentation for radiological tasks like medical image classification, segmentation on CT and MRI.

---

**What is data augmentation?**

Modification on the images of training set to generate further representative samples to decrease generalization error.
It can be considered a form of regularization technique.

**What does data augmentation achieve?**

1. Avoid learning features too specific to the training set.
2. Counter imbalance.

---

**Basic Augmentation Technique**

Basic augmentation techniques include those which apply a transformation to an image which maps the
points of the image to a different position, or manipulates the image intensity values, to produce an augmented image.

**Geometric augmentation** is one form of basic augmentation. It includes scaling, translating, rotatin, reflecting, shearing and skew. 
In **cropping** patches are randomly selected from existing image. This technique is used during class imbalance. 
In **occlusion** patches are randomly removed from an image.
**Gamma correction**,**linear contrast** and **histogram equalization** are used to adjust contrast of image. 
**Noise injection** techniques include gaussian noise, uniform noise, salt and pepper noise. 
**Convolution** based on a kernel is done to sharpen, blur or smooth images. 





