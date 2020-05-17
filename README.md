# Bladder Segmentation for PET/CT

## Background
Price Jackson from Peter MacCallum Cancer Centre (PMCC) has previously developed a few deep learning models for segmentating different organs from the PET/CT. Further (and similar) work need to be done on the bladder, which involves the challenge that the nearby malignant reginos might interfere with the high uptake in the bladder. This project will be lead by Yu Sun, which is funded by a current fellowship that Price holds.

## Aim
The main objective is to develope a model to identify high-uptake regions in the bladder so that it can be distinguished from malignant regions. Ideally this would exclude nearby activity which is the main challenge in this project.

## Data
Price has contoured a selection of cases (n=40, 20 Ga-68 Octreotate & 20 Ga-68 PSMA) with bladder defined to CT and approximate PET margins. Yu will perform an initial investigation on this dataset. Price will contour more upon request.

## Plans
Starting from the typical U-net structure and fine tune with customised loss functions. Since there is a limited number of cases that neighbouring malignancy influences the bladder activity, data augmentation can be performed to synthesise such cases.

## Contact
Yu: sunyu0410@gmail.com or yu.sun@sydney.edu.au

Price: price.jackson@petermac.org
