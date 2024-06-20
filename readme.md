# Compassion.ly Machine learning

Focusing on the machine learning aspects of our project Compassion.ly, which is an app that will help people find their major and university.

## Tasks

-   **Data Collection**:
    
    -   Collect data from the LTMPT website and gather as much information about majors as possible.
    -   Find details about each major, including the courses they offer and the career prospects for specific majors.
-   **Data Labeling**:
    
    -   Label the dataset and add weights to the data for each major according to specific topics:
        -   Matematika
        -   Sains
        -   Fisika
        -   Sosiologi
        -   Biologi
        -   Kimia
        -   Teknologi
        -   Bisnis dan Ekonomi
        -   Seni
        -   Sastra dan Linguistik
        -   Pendidikan
        -   Hukum
        -   Lingkungan
        -   Kesehatan
        -   Geografi
        -   Komunikasi
        -   Sejarah dan Filsafat
-   **Modeling**:
    
    -   Build three models:
        -   **Recommendation Model**: Use content-based filtering with TensorFlow and Scikit-learn cosine similarity. access in this link [content-based-filtering-model](https://github.com/Compassion-ly/compassionly_ml/blob/master/notebook_modeling/model_content_based_filtering.ipynb)
        -   **Similarity Search**: Fine-tune the T5 architecture to find similar texts for the majors. The input for this model is text, allowing the model to predict the best matches and answers. [t5 similarity search](https://github.com/Compassion-ly/compassionly_ml/blob/master/notebook_modeling/t5_similarity_search.ipynb)
        -   **Text Summarization**: Fine-tune the T5 architecture for text summarization. [text_summarization](https://github.com/Compassion-ly/compassionly_ml/blob/master/notebook_modeling/text_summarization.ipynb)

## Model architecture

- Content based filtering using Tensorflow and cosine similarity :  (
(Please tambahin gambar cbf sama archtiecturenya)

- t5 architecture for similarity search and text summarization
(Please tambahin  archtiecturenya)

## Dataset : 
For the dataset, access in this link : [dataset_compassionly](https://github.com/Compassion-ly/compassionly_ml/tree/master/dataset)

## Model demo,
The demo for our model, you can access in this link : [Model demo](https://majorquickrecommendation.streamlit.app/)

## Model evaluation 
This is the 

((Lanjutin tambahin detail evaluasi -> untuk accuracy, F1 score dll )

## Summary 


## Reference : 
- siapa 
