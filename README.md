# Brain-Tumor-Research-Paper
The 3 colab files are for creating the different datasets. The following are the datasets created each of which the model will be trained on:

      1) Original Dataset
      
      2) Albumentations Unbalanced Dataset
      
      3) Auto-Augmentations Unbalanced Dataset
      
      4) Albumentations Balanced Dataset (400 images per class)
      
      5) Auto-Augmentations Balanced Dataset (400 images per class)
      
      6) Albumentations Balanced Noisy Dataset (400 images per class)
      

The last dataset contains images which have noise. This is useful in many MRI Scans which are taken by old or faulty equipment and are pixelated or blurry to some extent.

Also, each Dataset is saved in my Google Drive and each has an 'augmentations.txt' text file associated with it which has the exact set of augmentations(which is randomly decided by the model) used on each image with the exact parameter values as well.

This helps to identify very easily what set of augmentations have been applied on every image.
<img width="663" alt="Screenshot 2024-09-02 at 12 50 34 AM" src="https://github.com/user-attachments/assets/4646c8af-adf2-4a8c-b1c5-9b8f8869ef3d">


The model will be trained on all 6 datasets and accuracies of each will be documented.
