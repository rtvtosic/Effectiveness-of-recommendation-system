# Эффективность рекомендательной системы
This project analyzed the results of an A/B test conducted to evaluate a new product recommendation algorithm. This task allowed me to use in practice the apparatus of mathematical statistics to analyze the result of A/B-test. Moreover, I checked the SRM metric and also used more advanced visualization compared to my previous project

# Гипотеза и дизайн A/B-теста
Гипотеза: Если внедрить новую систему рекомендаций, то **доля пользователей, у которых за период была хотя бы одна покупка с рекомендованным товаром** будет выше на 15% среди пользователей с новой системой, чем у пользователей со старой системой рекомендаций. 

Дизайн A/B-теста: 
- **Группа A** (контрольная): пользователи со старой системой рекомендаций
- **Группа B** (экспериментальная): пользователи с новой системой рекомендаций
- **Метрика**: Доля пользователей, у которых за период была хотя бы одна покупка с рекомендованным товаром
- **Формат результатов**: значение итоговой метрики в группе A и B, проверка на статзначимость.
- **Период**: 01.10.2023 по 14.10.2023 (2 недели)
