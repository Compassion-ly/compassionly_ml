# Compassion.ly Machine Learning

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
- **Content-based filtering using Tensorflow and cosine similarity** 

    ![Content Based Filtering](https://github.com/Compassion-ly/compassionly_ml/assets/100945245/daaae2a6-011f-4096-b92e-ef1f917322d6)

- **t5 architecture for similarity search and text summarization**
  
    ![image](https://github.com/Compassion-ly/compassionly_ml/assets/100945245/a02298d9-9a5b-4b30-855f-c76f1afddf54)


## Dataset
For the dataset, access in this link: [dataset_compassionly](https://github.com/Compassion-ly/compassionly_ml/tree/master/dataset)

## Model demo
The demo for our model, you can access in this link: [Model demo](https://majorquickrecommendation.streamlit.app/)

## Deployed Model
For our deployed model, you can access it in this link:
- [Summarization Model](https://drive.google.com/file/d/1xsreSypuxkzYCB4EKzYY5rX2swVdiykl/view?usp=sharing)
- [Quick Recomendation Model](https://drive.google.com/drive/folders/18JrxndMV3qvIPKJa-58zlOPI--uZXi_y?usp=sharing)
- [Numerical Model as an Input](https://drive.google.com/drive/folders/1htdPx9R5R7BTokYok9Xcc1x9Oy18oG6_?usp=sharing)

## Model evaluation 
This is our model accuracy and loss
![image](https://github.com/Compassion-ly/compassionly_ml/assets/100945245/7184a4f5-ed7c-4f5b-8864-0e6d429f9055)


## Summary 


## Reference : 
- R.Manjula (2016). Content Based Filtering Techniques in Recommendation System using user preferences. International Journal of Innovations in Engineering and Technology (IJIET)
- Pradeep, et al (2020). A Machine Learning approach for automation of Resume Recommendation system, Procedia Computer Science
- Parul, et al (2017). Comparing Content Based and Collaborative Filtering in Recommender Systems. International Journal of New Technology and Research (IJNTR).
- Sri Hari Nallamala, et al (2020). A Brief Analysis of Collaborative and Content Based Filtering Algorithms used in Recommender Systems. IOP Conference Series: Materials Science and Engineering.
- Shijie Geng, et al (2022). Recommendation as Language Processing (RLP): A Unified Pretrain, Personalized Prompt & Predict Paradigm (P5).
- Jiacheng Li, et al (2023). Text Is All You Need: Learning Language Representations for Sequential Recommendation. In Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD ’23).
- Radhwan Hussein (2023). Empowering Education: AMCQA Generation with T5 Transformers. ISAR - International Journal of Mathematics and Computing Techniques.


