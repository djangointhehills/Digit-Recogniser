This notebook is purely for my own learning.

Aims:

Implement a CNN using the Kaggle 'Digit Recogniser' competition dataset.
Use TPU.
Explore data augmentation.
Outcomes so far:

Successful implentation of CNN using TPU.

Unable to augment data in model as suggested by the TensorFlow documentation. I want to have the benefits of saving the augmentations as these seem to me to be an integral part of the model.

I have however managed to successfully augment the data (not in this notebook) without the use of the TPU, which coincidentally had the best results.

One consideration is that the model test/train accuracy is optimal at around 4 epochs. This suggests that the TPU might be overkill and the model might be better using the CPU and having data augmentation.

Future Endeavours:

Get data augmentation and TPU working optimally.
Save best model in training.


