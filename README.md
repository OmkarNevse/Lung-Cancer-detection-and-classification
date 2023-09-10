# Lung Cancer Detection and Classification

Lung cancer is the second most common cancer in both men and women and
affects millions yearly. Nearly 1 out of 4 cancer deaths are from lung cancer,
more than colon, breast, and prostate cancers combined. Globally there were an estimated 2.1
million lung cancer cases and 1.8 million deaths in 2018. Early cancer detection can
allow for early treatment which significantly increases the chances of survival. Lung cancer
screening is performed with a CT scan that collects hundreds of images to build a full 3D
composite of the lung. Next, small growths called pulmonary nodules need to be detected.
These nodules show up as small, circular structures on the CT scans.

In some cases, the nodules are not obvious and may take a trained eye and a
considerable amount of time to detect. Building a machine learning algorithm that can
automatically detect the nodules can save considerable time and money, thus opening the
accessibility of prescreening, ultimately saving lives. Additionally, most pulmonary nodules
are not cancerous as they can be due to non-cancerous growths, scar tissue, or infections.

The task is to determine the features of a nodule that are associated with malignancy.
Current state-of-the-art methods yield a 25% false positive rate in CT lung cancer screenings.
A convolutional neural network may be used to determine the features associated with
cancerous or non-cancerous pulmonary nodules and may reduce the false positive rate of CT
lung cancer screenings.

This model detects if a patient's CT scan contains nodules and classifies them into 4 different classes: Normal, Adenocarcinoma, Squamous Cell Carcinoma, and Large cell Carcinoma.

Currently, we can achieve an overall 90.2% accuracy with the model.






Datasets Used: 
1. https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images
2. https://paperswithcode.com/dataset/lidc-idri


