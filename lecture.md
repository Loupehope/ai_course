# Лекция 1

Интеллектуальный анализ данных - совокупность методов обнаружения в данных ранее неизвестных, нетривиальных, практически полезных и доступных для интерпретации знаний.  

Паттерн - знание (закономерность), извлеченное в ходе интеллектуального анализа.  

Задачи Data Mining / Machine Learning:
1. Predictive / Supervised learing (обучение с учителем) - наличие правильных ответов (можно также отнести semi-supervised learning):
    - Задача классификации - разбиваем по конкретным признакам
    - Регрессия
    - Анализ временных рядов
    - Ранжирование
2. Descriptive / Unsupervised learing (обучение без учителя) - отсутствие ответов:
    - Поиск ассоциативных правил - анализ потребительской корзины
    - Кластеризация - разбитие на группы без знания признаков
    - Суммаризация (summarization)
    - Feature selection - отбор признаков необходимых
    - Anomaly detection - обнаружение аномалий

Процесс Data Mining - традиционный:
  1. Selection - выбор данных (data)
  2. Preprocessing - предобработка данных (target data)
  3. Transformation - обработка данных (preprocessed data)
  4. Data mining - поиск патернов / создание модели (patterns / models)
  5. Interpretation evaluation - оценка знаний (knowledge)

Современный pipline работы с данными - CRISP-DM - Cross Industry Standard Process for Data Mining - во главе DATA:
  1. Business understanding (-> 2)
  2. Data understanding (1 <-, -> 3)
  3. Data preparation (-> 4)
  4. Modeling (3 <-, -> 5)
  5. Evalutaion (-> 1, -> 6)
  6. Deployment

# Лекция 2

Данные — зарегистрированная информация; представление фактов, понятий или инструкций в форме, приемлемой для общения, интерпретации или обработки человеком или с помощью автоматических средств.  

Свойства информации / данных, на которые **не** можем повлиять:
- Достпуность
- Актуальность
- Своевременность
- Достоверность
- Полезность

Свойства "вторичные" информации / данных, на которые можем повлиять:
- Полнота
- Интепретируемость
- Согласоавнность (непротиворечивость)
- Корректность
- Избыточность

Preprocessing (предобработка) - изменение информации для улучшения вторичных свойств (процесс приведения данных к форме удобной для дальнейшего анализа).

Свойства выборки данных:
- Объем
- Полнота
- Количество объектов
- Режим доступа
- Семантические характеристики
- Структура данных 
- Источники данных

Неструктурированные данные - аудио, видео, изображения, тексты.   
Структурированые данные - таблицы, матрицы, графы, временные ряды, транзакции.   

Генеральная совокупность - весь возможные данные или объекты.  
Выборка или набор данных - часть генеральной совокупности.   
Целевая переменная - переменная (столбец, признак), модель которой необходимо построить.

Шкалы атрибутов:
1. Номинальная - обычно не цифры (нельзя складывать, умножать, сравнивать, делить и тд)
2. Порядковая - можно сравниватьб упорядочивать, но не складывать, умножать, делить
3. Интервальная - можно вычитать, измерять расстояние, искать среднее, но не складывать, умножать, делить
4. Абсолютная - можно всё


