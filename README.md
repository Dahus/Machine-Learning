# Машинное обучение
```diff
- Код лабараторных был написан на платформе Jupyter Notebook, а проект на Google Colab
```
## Лабораторная работа 1. Введение в анализ данных на PythonЗадание (lab1)

Архив задания содержит:
- lab-1-pandas.ipynb - текст задания (jupyter notebook)
- data.csv - данные
- DataDictionary-ru.txt - смысл столбцов матрицы data.csv
- data_full.csv - полный файл с данными

## Лабораторная работа 2. Основные понятияЗадание (lab2)

Архив задания содержит: 
- lab2-general-concepts.ipynb - текст задания (jupyter notebook)
- data.csv - данные
- DataDictionary.txt - смысл столбцов матрицы data.csv

## Лабораторная работа 3. Ленивое обучениеЗадание (lab3)

Архив задания содержит: 
- lab3-knn.ipynb - текст задания (jupyter notebook) 
- data.csv - данные 
- DataDictionary.txt - смысл столбцов матрицы data.csv
- KNeighborsClassifier.cpp - метод ближайших соседей на C++ для подбора коэффициентов метрики



## Лабораторная работа 4. Восстановление плотностиЗадание (lab4)

Архив задания содержит: 
- lab4-density.ipynb - текст задания (jupyter notebook) 
- data.csv - данные 

## Лабораторная работа 5. Логистическая регрессия. ROC. AUC. One-hot encoding (lab5)

Архив задания содержит: 

- lab5-logistic-regression-ru.ipynb - текст задания (jupyter notebook) 
- Claims_Y1.csv - случаи обращения пациентов за медицинской помощью за прошедший год
- Members.csv - другие известные данные о пациентах
- DaysInHospital_Y2.csv - данные о госпитализации пациентов за следующий год (DaysInHospital=1 - был госпитализирован)
- Lookup PrimaryConditionGroup.csv - расшифровка значений в столбце PrimaryConditionGroup файла Claims_Y1.csv
- Lookup ProcedureGroup.csv - расшифровка значений в столбце ProcedureGroup файла Claims_Y1.csv

[Ссылка на архив.](http://staff.mmcs.sfedu.ru/~sguda/MachineLearning/lab5.7z)

- lab5-logistic-regression-en.ipynb - task text (jupyter notebook)
- Claims_Y1.csv cases of treatment of patients for medical care during the past year
- Members.csv - other known patient data
- DaysInHospital_Y2.csv - data on hospitalization of patients for the next year (DaysInHospital=1 - was hospitalized)
- Lookup PrimaryConditionGroup.csv - decrypts the values in the PrimaryConditionGroup column in the Claims_Y1.csv file
- Lookup ProcedureGroup.csv - decrypts the values in the ProcedureGroup column of the Claims_Y1.csv file

## Лабораторная работа 6. SVM. Natural language processingЗадание (lab6)

К лабораторной работе прикреплен файл 
- lab6-svm.ipynb - текст задания (jupyter notebook) 

## Лабораторная работа 7. Логические алгоритмы. БустингЗадание (lab7)

Архив задания содержит: 

- lab7-boosting.ipynb - текст задания (jupyter notebook) 
- data.csv - данные 
- DataDictionary.txt - смысл столбцов матрицы data.csv

## Проект (project)

Благодаря множеству опубликованных в интернете датасетов и кода решения задач машинного обучения мы можем перенять опыт профессионалов. Чтобы работа над заданием была интереснее, стандартный целевой признак опубликованного датасета будет изменен преподавателем. Также в этом задании предполагается конкурс, победители которого получат бонусные баллы.

Для начала нужно выбрать датасет, например на сайте Kaggle, в репозитории UCI или на агрегаторе тренировок. Затем нужно подойти к преподавателю и, посоветовавшись, решить, как изменить цель предсказания и какой критерий качества выбрать. 

Вместе с выбранной задачей, каждый получит второй датасет, который уже кто-то выбрал раньше - для соревнования. В итоге на каждого студента должно приходится два датасета (задачи), и на каждый датасет - два студента, которые на нем соревнуются. Отчетность: код и результат работы программы (сдавать нужно лично преподавателю). Достигнутые результаты будут держаться преподавателями в секрете (но студенты могут их друг другу рассказывать по желанию).

5 бонусных баллов получат те, кто окажется победителем в обоих своих задачах.

По умолчанию для оценки качества используйте функцию cross_val_score (или cross_val_predict и вашу метрику качества), и подавайте туда cv=KFold(n_splits=10, shuffle=True, random_state=0).  cross_val_score возвращает массив R2-score, нам нужно среднее значение.

In English:

Thanks to the many datasets and code for solving machine learning problems published on the Internet, we can learn from the experience of professionals. To make the work on the task more interesting, the standard target attribute of the published dataset will be changed by the teacher. Also, this task assumes a competition, the winners of which will receive bonus points.

First, you need to select a dataset, for example, on the Kaggle website, in the UCI repository or on the training aggregator. Then you need to ask the teacher and decide how to change the target variable and what quality criterion to choose. 

Together with the selected task, everyone will receive a second dataset, which someone has already chosen earlier - to make a competition between them. As a result, there should be two datasets (tasks) for each student, and for each dataset there are two students who compete on it. Reporting: the code and the result of the program (you need to take it personally to the teacher). The achieved results will be kept secret by the teachers (but students can tell them to each other at will).

5 bonus points will be awarded to those who are the winners in both of their tasks.

By default for quality measure use function cross_val_score (or cross_val_predict and your measure) with argument cv=KFold(n_splits=10, shuffle=True, random_state=0).  cross_val_score returns array of R2-score, you need in mean value.
