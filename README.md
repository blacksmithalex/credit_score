# Анализ данных банковского сектора и решение задачи кредитного скоринга 

## Вступление:

Задача кредитного скоринга возникает в банках и других кредитных организациях при принятии решений о выдаче кредитов. Задача заключается в том, чтобы на основе дополнительной информации о заявителе обоснованно принять решение - стоит ли выдавать кредит или нет.

## Цель: 
Проанализировать данные и построить модель кредитного скоринга

## Задачи:

1. Провести предобработку данных
2. Провести первичный анализ данных и их визуализацию
3. Построить классификационную модель, определяющую кредитный статус новых пользователей
4. Проанализировать результаты, дать обоснованную оценку, определить дальнейший формат работы с результатами

## Актуальность: 

Данная тема имеет большую актуальность в наше время. Потребность в автоматизации процедуры выдачи кредитов впервые возникла в период бума кредитных карт 60-70-х годов в США и других развитых странах. Объектами в данном случае являются физические или юридические лица, претендующие на получение кредита. 
Сейчас данный подход все больше интегрируется в финансовые организации: спрос на аналитиков и специалистов в области анализа данных растет с каждым годом. Результаты данной работы могут иметь ценность как для отдельных организаций из этой области, так и для изучения задачи кредитного скоринга в целом.

## Выводы:

1. Была произведена предобработка данных с использованием Python: преобразованы данные из одних типов в другой, убраны выбросы и нерелевантные значения.
2. Был первичный анализ данных и их визуализация
3. Построена классификационная модель, которая предсказывает кредитный статус новых клиентов
4. Результаты были проанализированы, был определен дальнейший формат работы.

## Итог:

Подведем итог проделанной работы. Нам удалось, используя функциональные возможности языка Python проанализировать порядка 100.000 данных пользователей. В результате чего мы смогли выявить базовые закономерности и визуализировать результаты. Стоит отметить, что большая работа была проделана по предобработке данных, приведению их к виду, необходимому для построения моделей машинного обучения. Результатом работы является модель, которая прогнозирует статус клиента с точки зрения кредитного скоринга с точностью порядка 84%, что является достаточно высоким результатом. 

<b> Как можно продолжить модификацию данной работы? </b> В данной модели мы использовали достаточно много параметров и применяли несколько моделей разом, что делает результат плохо интерпретируемым. С точки зрения банковского сектора важным является понятная интерпретация результатов и стабильность модели, так как до получения результативности зачастую проходит от нескольких месяцев до нескольких лет. Поэтому первая цель - сократить количество параметров до целевых и остроить модель на них. Вторым шагом будет являться, безусловно, улучшение точности модели за счет добавления дополнительных данных о пользователях.

<b> Где данный результат может быть применен? </b> На текущий момент все крупные игроки банковского сектора используют модели машинного обучения для прогнозирования ключевых показателей разных продуктов. Данная модель может быть полезна в качестве как теоретического, так и практического дополнения текущих моделей, которые используют на практике. Также этот результат может иметь обучающую функцию для тех, кто хочет начать развиваться в теме машинного обучения и интересуется именно финансовым сектором. В завершении хочу отметить, что большая часть работы над данными носит исследовательскую функцию, что впоследствии помогает использовать результаты не только в той сфере, где эти исследования были проведены.

<i> 
data.csv - данные, описание столбцов внутри файла

Для работы над проектом использовался Jupyter Notebook (Python). Для реализации считывания, визуализации, предобработки и построения моделей использовались следующие библиотеки: 

1. pyplot, seaborn, pandas, numpy (считывание и визуализация)
2. imblearn, sklearn (для предобработки и обучения модели)
3. xgboost, joblib (для построения модели)
</i>


