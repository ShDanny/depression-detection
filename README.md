# depression-detection
Depression detection from Chinese social media

1. 7002-depression detection-0815 including all codes, such as data processing, models, and feature extraction for user's profile and tweets. While 7002-depression detection-0816, re-training the text CNN model with the database without tokenisation showed little difference from the previous one. 7002-depression detection-0825, addition: I used 7000 rows, the same as my benchmark, to retrain models, text CNN still has the highest performance and is higher than the benchmark
addition: I used 7000 rows, the same as my benchmark, to retrain models, text CNN still has the highest performance and is higher than the benchmark
2. This project has four models: rf, mlp, svm and text CNN.  Those four files 7002-rf, 7002-mlp, 7002-svm, and 7002-text CNN used to test the four models separately using part of the tokenized dataset. 
3. 7002-text CNN -no tokenization dataset: same code but no tokenized dataset with 7002-text CNN file.
4. 7002-merge stopwords: used to merge four stop words file.
5. jieba_expanded_dict: used to expand jieba
6.  dataset link: https://github.com/aidenwang9867/Weibo-User-Depression-Detection-Dataset
![image](https://github.com/ShDanny/depression-detection/assets/125326817/d0f5268d-dc54-44de-b52c-2c1fa195e4f5)

7. 20240619， retrained svm, mlp, rf, and textCnn in colab by GPU. DisitiBert, DistilRoBerta, Bert-Base-Chinese still trained by GPU
