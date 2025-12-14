# ArtClassifier

This project implements a deep learning–based **art classification system** capable of categorizing artworks into five main types and, when applicable, further predicting painting styles.

It performs **two-stage classification**:

1. **Art Type Classification**
   - Drawings
   - Engraving
   - Iconography
   - Painting
   - Sculpture

2. **Painting Style Classification** (only if the artwork is classified as a painting)
   - Japanese Art
   - Neoclassicism
   - Primitivism

The models are built using **Keras (TensorFlow backend)** and leverage **Convolutional Neural Networks (CNNs)**, including a **VGG16-based architecture** for style classification.

The data set used is from kaggle [Art Type](https://www.kaggle.com/datasets/thedownhill/art-images-drawings-painting-sculpture-engraving) and [Art Style](https://www.kaggle.com/datasets/sivarazadi/wikiart-art-movementsstyles/data)<br />
In the following pictures you can see a summary of the work:
![5](https://github.com/user-attachments/assets/98563693-a1e5-43f8-b05d-25df7cc77809)
![6](https://github.com/user-attachments/assets/9de84cd7-95f5-43a9-8c5b-0c3bd1a56bc0)
![7](https://github.com/user-attachments/assets/91e8fd66-aff8-4957-a3cd-8752b5c9cb03)
![8](https://github.com/user-attachments/assets/b11079b8-2eed-4c83-90e2-cfdadb05be56)
![9](https://github.com/user-attachments/assets/fe30847c-1a5c-437d-8f25-961b371c0a34)
![10](https://github.com/user-attachments/assets/21bae4d7-cb67-4258-9068-8896293faa26)
![11](https://github.com/user-attachments/assets/3aa77b2d-9a39-4bfb-b765-7ef25136be05)
![12](https://github.com/user-attachments/assets/932bd2be-d7a1-44af-a0b4-4f1060e82148)
![13](https://github.com/user-attachments/assets/4baf06ba-3613-447c-863d-dbdcb3848473)
![14](https://github.com/user-attachments/assets/7c534fb0-8b36-439b-9b0b-c80498500b07)
