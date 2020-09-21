# Тестирование CNN на корпусе Twitter

**Цель: получить базовые результаты модели CNN на корпусе русскоязычных твитов, описывающих состояние здоровья. Каждый твит отмечен в зависимости от того, содержит ли он сообщение о неблагоприятном побочном эффекте, возникшем при приёме лекарственного препарата.**

1\. Данные: task2_ru_training_raw.tsv (train), task2_ru_validation_raw.tsv (validation), task2_ru_test_raw.tsv (test), task2_ru_test_final_raw.tsv (test_final).

2\. Тестирование_CNN_на_корпусе_Twitter.ipynb - ноутбук с моделью CNN для бинарной классификации твитов.

3\. Результаты в виде таблицы:
Train corpus | Test corpus | Precision | Recall | F-measure
--- | --- | --- | --- | ---
train | validation | 0.27559 | 0.78947 | 0.40856
train + validation | test | 0.29630 | 0.67470 | 0.41176
train + validation + test | test_final | 0.36881 | 0.75253 | 0.49502

4\. Ссылка на ноутбук в Google Colaboratory: https://colab.research.google.com/drive/1HggcJqGs1W63uG7O6PYCiFGp7QpwA5c9?usp=sharing
