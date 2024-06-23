# 🌺 Анализ Поведения Пользователей YouTube через Кластеризацию Видео

### Описание проекта: Анализ сегментации клиентов на основе данных с YouTube API
В этом проекте я провел анализ сегментации клиентов, используя данные, полученные с YouTube API. Основная цель заключалась в том, чтобы понять различные группы видео контента на YouTube и выявить ключевые характеристики каждой из этих групп.

### Этапы проекта:
+ **Сбор данных**: Я использовал YouTube API для получения информации о видео по ключевым словам. В процессе сбора данных извлекались такие параметры, как идентификатор видео, название, канал, дата публикации, описание и URL миниатюр.
+ **Подготовка данных**: Полученные данные были очищены и преобразованы в табличный формат с использованием библиотеки pandas. Это позволило легко управлять данными и проводить дальнейший анализ.
+ **Сегментация данных**: Для сегментации видео контента я использовал метод K-средних (K-means). Данные были стандартизированы и классифицированы на несколько кластеров на основе таких параметров, как количество просмотров, лайков и комментариев.
+ **Визуализация и интерпретация**: Результаты кластеризации были визуализированы, что позволило выявить и интерпретировать ключевые особенности каждой группы видео. Это помогло лучше понять поведение пользователей и популярность различных типов контента.

### Анализ сегментации клиентов
Для данного проекта я использовал данные с YouTube API, чтобы провести сегментацию пользователей. Проект включал в себя следующие этапы:
+ Сбор данных с YouTube API
+ Подготовка данных
+ Сегментация данных
+ Интерпретация результатов

## Используемые библиотеки
`os` `pandas` `seaborn` `matplotlib.pyplot` `googleapiclient.discovery` `sklearn.cluster.KMeans` `sklearn.preprocessing.StandardScaler` `sklearn.decomposition.PCA`
