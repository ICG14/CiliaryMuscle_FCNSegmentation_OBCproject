# CiliaryMuscle_FCN_Segmentation

The FCN can be found here: https://unizares-my.sharepoint.com/:u:/g/personal/iulen_unizar_es/ES4bNxVrp2xMlMgXkyZaTfMBv_r2MsX1vnwagNfmjcgjvg?e=cUqQaH
Another FCN with a different training dataset (Sometimes can outperform the other one): https://unizares-my.sharepoint.com/:u:/g/personal/iulen_unizar_es/EQBMM8enrGFAqDUIQXW1sI4BBrQQd5Ng5NdGvOMg4ACYWQ?e=Aho6kD

You can find the model weights for transfer learning here: https://unizares-my.sharepoint.com/:u:/g/personal/iulen_unizar_es/EfjA68CKAvREqnXQtYHuifkBfER0-veFU6svmdoLJSZNUQ?e=dlA6SO

# Model.summary: Unet with EfficientNetb2 as backbone


An example of the FCN implementation can be found in the files uploaded to the project:
"Example_Use_FCN-CM_OBC_ICabeza-Gil.ipynb"
The FCN architecture for the CM segmentation can also be found in the script above.

The dataset of the subject #3 can be found in this zip: https://unizares-my.sharepoint.com/:u:/g/personal/iulen_unizar_es/EX_RO3T0DMROoHF9ExIxQ4gBbYIOv5x-zeDnOHapz8CmEQ?e=pRJMRI
S_3.npz corresponds to the whole recording (160 frames/images).
S_3_test.npz contains the original and groundtruth images (17).
S_3_annotation contains the groundtruth images. They are in different format as in S_3_test.npz for their easy processing.

Sometimes the links are down. Please write to me to upload them again. Thank you.
