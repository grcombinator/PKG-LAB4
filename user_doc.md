# Пользовательская документация

## 1. Введение

Программа RasterAlgorithmsApp предназначена для визуализации работы основных растровых алгоритмов отрисовки линий и окружностей. Приложение позволяет пользователям выбирать различные алгоритмы, вводить координаты для построения графических объектов и оценивать визуализацию в реальном времени.

## 2. Системные требования

- **Python** версии 3.6 или выше.
- Установленная библиотека **tkinter** (обычно идет в комплекте с Python).
  
## 3. Запуск

Сохраните код программы в файл, например, raster_algorithms_app.py, и выполните команду:

```bash

python raster_algorithms_app.py
```

## 4. Использование приложения

### 4.1 Выбор алгоритма

На панели управления выберите один из доступных алгоритмов:

- Пошаговый алгоритм
- Алгоритм ЦДА (DDA)
- Алгоритм Брезенхема (отрезок)
- Алгоритм Брезенхема (окружность)
  
### 4.2 Ввод координат

Заполните соответствующие поля для:

- Отрезков: начальная точка (x₀, y₀) и конечная точка (x₁, y₁).
- Окружностей: центр (xс, yс) и радиус (r).

### 4.3 Отрисовка

- Введите необходимые координаты.
- Выберите желаемый алгоритм из выпадающего списка.
- Нажмите "Отрисовать". Результат отобразится на холсте.
  
### 4.4 Масштабирование

Используйте ползунок для изменения масштаба отображаемого изображения.

### 4.5 Очистка холста

Нажмите "Очистить", чтобы удалить все нарисованные объекты и сбросить холст.

## 5. Пример использования

Пример отрисовки отрезка

- Начальная точка: (2, 3)
- Конечная точка: (10, 7)
- Выберите алгоритм Брезенхома и нажмите "Отрисовать".

Пример отрисовки окружности

- Центр: (0, 0)
- Радиус: 5
- 
Выберите алгоритм Брезенхома (окружность) и нажмите "Отрисовать".

## 6. Обратная связь

Для вопросов и багов: пишите мне на почту

# Приложения

## Приложение 1. Список реализованных алгоритмов

1. Пошаговый алгоритм
2. Алгоритм ЦДА (DDA)
3. Алгоритм Брезенхома (отрезок)
4. Алгоритм Брезенхома (окружность)

## Лицензия
Данное приложение распространяется на условиях лицензии MIT. Подробнее смотрите файл LICENSE в репозитории.

## Дополнительные материалы
Репозиторий проекта: этот репозиторий

## Обновления документации

Документация обновляется при внесении изменений в приложение. Рекомендуется регулярно проверять актуальность документации в репозитории проекта.