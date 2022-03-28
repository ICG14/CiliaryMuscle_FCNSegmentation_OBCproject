# CiliaryMuscle_FCN_Segmentation

The FCN can be found here: https://drive.google.com/file/d/15l3pWy99m8SjALXy8QmH1hvgPsirVLwR/view?usp=sharing
Another FCN with a different training dataset (Sometimes can outperform the other one): https://drive.google.com/file/d/15l_Kix7iLysqgOvRJzMzcNUa76QiRQ3m/view?usp=sharing

You can find the model weights for transfer learning here: https://drive.google.com/file/d/15lDwqYdHAr7UGOWaS2L-auoDsUBB0oEc/view?usp=sharing

# Model.summary: Unet with EfficientNetb2 as backbone


An example of the FCN implementation can be found here: https://colab.research.google.com/drive/11A65-3U4HaX6rJbhECsa3-94Qz2NqCvR?usp=sharing
The FCN architecture for the CM segmentation can also be found in the link above.

The dataset of the subject #3 can be found in this zip: https://drive.google.com/file/d/161MPrqWyZsYFaXzEuseLPfcV8sxB-rb0/view?usp=sharing
S_3.npz corresponds to the whole recording (160 frames/images).
S_3_test.npz contains the original and groundtruth images (17).
S_3_annotation contains the groundtruth images. They are in different format as in S_3_test.npz for their easy processing.
