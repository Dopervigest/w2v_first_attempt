# Данный мини-проект это попытка создать простейшую модель word2vec

В файле Create_and_train.ipynb находится код осуществляющий создание, тренировку и сохранение модели

Был использован pandas для считывания датасета и создания датафрейма, gensim для токенизации, отчистки датасета от "стоп-слов", в также создания и тренировки модели word2vec, NLTK для стемминга и tqdm для визуализации обработки циклов

Датасет, на котором тренировалась модель весит слишком много для загрузки на GitHub, он был взят с сайта:
http://jmcauley.ucsd.edu/data/amazon/  (Sports and Outdoors, reviews) 

В файле test.ipynb находится загрузка модели и пример реализации её простейших функций

word2vec_test.model - сама модель
