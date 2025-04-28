## Project Overview
This project focuses on building a multimodal deep learning model that classifies scanned document images by combining visual features (images) and textual features (OCR-extracted text).
We utilize ResNet18 for image feature extraction and TF-IDF for text feature extraction, followed by feature fusion for final classification.

### Model Architecture
1.Image Processing:
Pretrained ResNet50 used to extract visual embeddings.

2.Text Processing:
TF-IDF Vectorizer used to extract fixed-size text embeddings.

3.Fusion:
Image embeddings and text embeddings are concatenated.

Passed through fully connected layers for classification.

### Future Improvements
-Replace TF-IDF with Transformer-based text embeddings (e.g., BERT).
-Fine-tune ResNet instead of freezing it.
-Explore attention-based fusion for even better multimodal integration.
