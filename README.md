**Студент:** Матвеев Данил Евгеньевич  
**Группа:** М8О-407Б-21

## Задачи

### 1. Задача классификации

- **Датасет:** Iris
- **Обоснование:** Этот небольшой и сбалансированный датасет идеально подходит для задачи классификации. Он содержит информацию о видах ирисов на основе четырех признаков (длина и ширина лепестков и чашелистиков).

### 2. Задача регрессии

- **Датасет:** California Housing
- **Обоснование:** Данный датасет содержит реальные данные о ценах на жилье в Калифорнии, что делает его подходящим для задачи регрессии, направленной на прогнозирование стоимости недвижимости в зависимости от различных характеристик.


Метрика оценки качества регрессии: **R^2**;  
Метрика оценки качества классификации: **accuracy**;

*Метрики качества на тестовом наборе данных*
<table>
    <tr>
        <th rowspan="1">Алгоритм</th>
        <th>Задача</th>
        <th>Бейзлайн</th>
        <th>Улучшенный бейзлайн</th>
        <th>Самостоятельная имплементация алгоритма</th>
    </tr>
    <tr>
        <td rowspan="2">KNN</td>
        <td>классификация</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>0.67</td>
        <td>0.68</td>
        <td>0.67</td>
    </tr>
    <tr>
        <td rowspan="2">Линейные модели</td>
        <td>классификация</td>
        <td>0.95</td>
        <td>0.95</td>
        <td>0.95</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>0.98</td>
        <td>0.9834</td>
        <td>0.9841</td>
    </tr>
    <tr>
        <td rowspan="2">Решающее дерево</td>
        <td>классификация</td>
        <td>1</td>
        <td>1</td>
        <td>0.3</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>0.6221</td>
        <td>0.6818446481456171</td>
        <td> 0.8514569470233706</td>
    </tr>
    <tr>
        <td rowspan="2">Случайный лес</td>
        <td>классификация</td>
        <td>1</td>
        <td>1</td>
        <td>1</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>0.8045</td>
        <td>0.9740</td>
        <td>0.9740</td>
    </tr>
    <tr>
        <td rowspan="2">Градиентный бустинг</td>
        <td>классификация</td>
        <td>0.9591</td>
        <td>0.9591</td>
        <td>0.9649</td>
    </tr>
    <tr>
        <td>регрессия</td>
        <td>0.7803</td>
        <td>0.8342</td>
        <td>0.7803</td>
    </tr>
</table>

Лучшие результаты в классификации показали алгоритмы KNN, Решающее дерево и Случайный лес, где точность равнялась 1. Это означает, что данные алгоритмы идеально решают задачу классификации.
Для регрессии алгоритм Самостоятельной имплементации с Решающим деревом и Случайным лесом показал наибольшее улучшение, что подчеркивает важность оптимизации моделей для задачи регрессии.
Градиентный бустинг и Линейные модели также показали хорошие результаты, но в целом, задачи классификации и регрессии они решают менее эффективно, чем другие алгоритмы в данной таблице.
