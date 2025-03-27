Back-Translation for Data Augmentation
This project performs back-translation using the Helsinki-NLP MarianMT model to enhance text datasets. It translates English text to French and back to English for augmentation.

Features
✅ GPU-accelerated translation using MarianMT
✅ Batch processing for efficiency
✅ Supports ISEAR dataset (Emotion Classification)

Usage
Upload the ISEAR dataset (ISEAR.xlsx) to Kaggle.

Run the script to generate back-translated text.

The output CSV (ISEAR_back_translated.csv) is saved in /kaggle/working/.

Requirements
torch
transformers
pandas
tqdm

Acknowledgment
Built using Helsinki-NLP MarianMT for translation. 🚀
