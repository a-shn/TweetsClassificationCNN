# Тестирование CNN на корпусе Twitter

Данные: task2_ru_training_raw.tsv (train), task2_ru_validation_raw.tsv (validation), task2_ru_test_raw.tsv (test), task2_ru_test_final_raw.tsv (test_final)

Train corpus | Test corpus | Precision | Recall | F-measure
--- | --- | --- | --- | ---
train | validation | 0.64705 | 0.24812 | 0.35869
train + validation | test | 0.51063 | 0.28915 | 0.36923
train + validation + test | test_final | 0.74698 | 0.31313 | 0.44128