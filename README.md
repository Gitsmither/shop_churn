# Анализ покупательской активности клиентов интернет-магазина с использованием ML

### **Сфера и направление деятельности**

Бизнес, интернет-сервисы, интернет-магазины

### **Цель проекта**

Создать модель для предсказания вероятности снижения покупательской активности клиента (в следующие 3 месяца), а также используя данные модели и данные о прибыльности клиентов выделить сегменты покупателей и разработать для них персонализированые предложения

### **Вводные данные**

  - данные о поведении покупателя на сайте, о коммуникациях с покупателем и его продуктовом поведении
  - данные о выручке, которую получает магазин с покупателя
  - данные о времени (в минутах), которое покупатель провёл на сайте
  - данные о среднемесячной прибыли покупателя за последние 3 месяца

### **Решаемые задачи**

  - Предварительная обработка вводных данных
  - Исследовательский и корреляционный анализ данных
  - Сравнительное исследование признаков клиентов с и без снижения покупательской активности
  - Разработка пайплайнов предобработки данных
  - Подбор гиперпараметров для исследуемых моделей с применением рандомизированного поиска
  - Выбор лучших гиперпарметров на кросс-валидации  
  - Объединение всех шагов в итоговый пайплайн
  - Выбор лучшей модели и оценка ее качества на тестовой выборке метрикой *ROC-AUC* 
  - Анализ важности признаков с использованием SHAP
  - Выбор сегмента покупателей и сравнение клиентов с и без снижения покупательской активности с использованием обученной модели
  - Предоставление заказчику персонализированных предложений для сегмента покупателей 
  - Формулирование выводов и рекомендаций заказчику


### Примеры визуализации данных

**Пример сравнительного исследования признаков**
![Пример сравнительного исследования признаков](https://raw.githubusercontent.com/Gitsmither/shop_churn/main/images/img_1.JPG)

**Пример анализа важности признаков**
![Пример анализа важности признаков](https://raw.githubusercontent.com/Gitsmither/shop_churn/main/images/output.png)
