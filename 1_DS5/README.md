# Прикладная статистика

## Материалы
- **обновленные pdf и ноутбуки [тут](https://drive.google.com/drive/folders/16j9iEUCET_xU7ZCGCpk2g9j3MAHODxPO?usp=sharing)** -  папка будет постоянно обновляться!
- книжки [тут](https://drive.google.com/open?id=16POMhfOKoJ2yOn0FvBvgK79FrhwV3fXL&authuser=allen.ilya%40gmail.com&usp=drive_fs)
- домашние задания нужно присылать в класс-рум, куда нужно присоединиться по [инвайт-ссылке](https://classroom.google.com/c/NDA4MzM3Nzk3MjQ2?cjc=wpyqr64) (инвайт-код wpyqr64)
- курс во многом основан на предыдущей [итерации](http://iosipoi.com/teaching/applied-statistics-3/)

---

## План занятий
### (1) Теория оценивания, ч.1
- Темы
	- Recap теории вероятностей
	- Несмещенность и состоятельность
	- Метод моментов
	- Метод максимального правдоподобия

<details>
	<summary> Ссылки с занятия</summary>

- Про начальный и центральный момент можно посмотреть:
	- В русской ([here](https://ru.wikipedia.org/wiki/%D0%9C%D0%BE%D0%BC%D0%B5%D0%BD%D1%82%D1%8B_%D1%81%D0%BB%D1%83%D1%87%D0%B0%D0%B9%D0%BD%D0%BE%D0%B9_%D0%B2%D0%B5%D0%BB%D0%B8%D1%87%D0%B8%D0%BD%D1%8B)) вики есть четкий пример, когда какой момент нужен и что показывает
	- В английской ([here](https://en.wikipedia.org/wiki/Moment_(mathematics))) есть похожая таблица
	- В статье про центральный ([here](https://en.wikipedia.org/wiki/Central_moment)) есть пара трюков для подсчетов (если вдруг интересно)


	
	

	
- Про эти 2 момента, думаю, все всё знают
	- 1 - Мат. ожидание / [Expectation](https://en.wikipedia.org/wiki/Expected_value) - 1ый начальный
	- 2 - Дисперсия / [variance](https://en.wikipedia.org/wiki/Variance) - 2ой центральный
- Про эти 2 можно почитать и посмотреть картинки
	- 3 - Асимметрия / скошенность влево-вправо / [Skewness](https://en.wikipedia.org/wiki/Skewness) - считается через 3ий начальный
	
	
	- 4 - Эксцесс / островершинность / [Kurtosis](https://en.wikipedia.org/wiki/Kurtosis) - считается через 4ый начальный

- Интерактивные картинки с занятия
	- [Тут](https://seeing-theory.brown.edu/basic-probability/index.html#section2) демонстрация ЗБЧ
	- [Тут](https://seeing-theory.brown.edu/probability-distributions/index.html#section2) визуализация функций плотности и распределения
	- Вообще рекомендую [все](https://seeing-theory.brown.edu/index.html#secondPage) главы на сайты полистать, там много интересных визуализаций из тер.вера и статистики
</details>
	

---

### (2) Теория оценивания, ч.2
- Темы
	- Метод прямоугольников и Метод Монте-Карло
	- Целочиленное интегрирование
	- Оценка среднего и дисперсии

- Про преобразование Бокса-Кокса можно почитать [тут](http://www.machinelearning.ru/wiki/index.php?title=%D0%9C%D0%B5%D1%82%D0%BE%D0%B4_%D0%91%D0%BE%D0%BA%D1%81%D0%B0-%D0%9A%D0%BE%D0%BA%D1%81%D0%B0), есть реализация в [sklern](https://scikit-learn.org/stable/modules/preprocessing.html#mapping-to-a-gaussian-distribution) ([тут](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.power_transform.html) документация)


---

### (3) Доверительные интервалы
- Темы
	- Доверительные интервалы
	- Распределения, связанные с нормальным
	- Доверительные интервалы в нормальной модели
	- Бутстрэп (параметрический и непараметрический)

- Разные мелочи
	- [Правило 3 сигм](https://miro.medium.com/max/1400/1*IZ2II2HYKeoMrdLU5jW6Dw.png) и сравнение с [boxplot](https://i.stack.imgur.com/lZ61D.png) для нормального распределения
	- Статистические [таблицы](https://github.com/bdemeshev/pr201/raw/master/stat_tables/e2_pro_tables.pdf) и ещё [цветные](http://www.stat.purdue.edu/~jtroisi/STAT350Spring2015/tables/)
	- [Визуализация](https://seeing-theory.brown.edu/frequentist-inference/index.html#section2) дов. интервала

### (4) Доверительные интервалы, ч.2
- Темы
	- Доверительный интервалы и бутстрэп
	- Распределения, связанные с нормальными
	- Тестирование гипотез о параметрах нормального распределения

--- 

### (5) Параметрические гипотезы

### (6) Непараметрические гипотезы


### (7) Линейная регрессия
#### Часть 1: EDA-related
- Корреляции Пирсона и Спирмена
- Многомерное нормальное
- Пропуски / выбросы / бокс-кокс / масштабирование / One Hot Encoding

#### Часть 2: Статистический взгляд на линейную регрессию
- Метод максимального правдоподобия и связь с MSE, MAE, logloss
- Линейная регрессия и метод максимального правдоподобия / постановка задачи для парной регрессии, тест отношения правдоподобия
- Когда важна интерпретация / примеры
- Линейная регрессия: статистический подход / предпосылки и теорема Гаусса-Маркова


### (8) Линейная регрессия + Временные ряды
#### Часть 1
- Линейная регрессия: проверка гипотез
- Обзор проблем, возникающих при оценке регрессии
- Разложение на смещение и разброс

