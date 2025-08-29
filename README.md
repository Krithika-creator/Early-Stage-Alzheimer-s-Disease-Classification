**Dataset**

The dataset was collected from ADSP-PH: ADNI T1 1.0 – Alzheimer’s Disease Neuroimaging Initiative (ADNI) repository.
It contains preprocessed NIfTI-format MRI images of female subjects aged 55 to 70 years, categorized into four stages of Alzheimer’s disease:

Alzheimer’s Disease (AD)

Mild Cognitive Impairment (MCI)

Late Mild Cognitive Impairment (LMCI)

Early Mild Cognitive Impairment (EMCI)

**Preprocessing and Transformation**

Preprocessing:

Extracted 2D slices from raw NIfTI files.

Resized images to 128 × 128 pixels.

Data Augmentation (Transformations):

Rotation range: 15°

Zoom range: 0.2

Horizontal flip: Enabled

**Model**

The model integrates:

Residual Squeeze-and-Excitation (SE) path for adaptive feature recalibration.

Dilated Convolution path for capturing multi-scale hierarchical features from MRI images.

**Evaluation**

5-fold cross-validation was performed for robust evaluation.
