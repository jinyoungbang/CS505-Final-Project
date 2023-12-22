# Predicting Music Genre using Lyrics with Deep Learning

Collaborators: Jin Young Bang, Taesung Yoon, Christopher Gough

## Abstract

This research explores the use of neural networks in predicting music genres from song lyrics to enhance recommendation systems. Leveraging the MetroLyrics Dataset, our study emphasizes preprocessing for focused lyric-based analysis. Addressing genre distribution imbalance through categorical cross-entropy, our baseline models, including LSTM, GRU, and HAN, reveal bidirectional variants consistently outperforming non-bidirectional counterparts. The HAN-GRU model stands out, achieving a 59.98% accuracy. Hyperparameter tuning yields modest improvements, underscoring the baseline model's efficacy. Despite resource constraints, this study provides valuable insights into the synergy of lyrics, music genres, and machine learning. Future iterations, with enhanced computational resources, hold promise for further advancements in the dynamic realm of digital music consumption and recommendation systems.

## Project Navigation
```
|-- data
|   |-- lyrics.csv.zip                      (original dataset)
|   |-- lyrics_cleaned.csv.zip              (preprocessed dataset)
|-- models                           
|   |-- han-lr-0.0001.ipynb
|   |-- han-lr-0.0001.pdf
|   |-- han-lr-0.01.ipynb
|   |-- han-lr-0.01.pdf
|   |-- han-lr-0.01.ipynb
|   |-- han-lr-0.01.pdf
|   |-- tuning-han-gru-1.ipynb
|   |-- tuning-han-gru-1.pdf
|   |-- tuning-han-gru-2.ipynb
|   |-- tuning-han-gru-2.pdf
|   |-- tuning-han-gru-3.ipynb
|   |-- tuning-han-gru-3.pdf
|   |-- gru-bidirectional.ipynb
|   |-- gru-bidirectional.pdf
|-- main.ipynb       
|-- main.pdf  
|-- README.md
```