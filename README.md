# JobFit Analyzer

This project aims to create a PDF data extractor that matches data (such as skills and education) extracted from CVs to job descriptions.
The CVs used to test this project were taken from [this Kaggle dataset](https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset), and the job descriptions were taken from [this Hugging Face dataset](https://huggingface.co/datasets/jacob-hugging-face/job-descriptions).

## Steps to proceed:
> A ZIP file containing all the resumes from the aforementioned dataset needs to be downloaded and subsequently uploaded on Google Drive
[Link to ZIP file](https://drive.google.com/file/d/1oAW3x5qwUt3E9gBNvR-ac-RyYJgXDrXz/view?usp=sharing)
(NOTE: Kaggle provides the option to download its datasets as ZIP files. However, the ZIP file for this dataset contains all resumes in separate folders based on the job profile applied for. The above link does not contain these segregations)
> The JobFit_Analyzer.ipynb file in this repo needs to be downloaded and run on Google Colab, where it was written originally.
> After completing the above steps, mount your Google Drive on Colab.
> The ZIP file uploaded to Drive in the first step must now be located in Colab's runtime storage. Its file path must be copied and pasted in the required variable.
