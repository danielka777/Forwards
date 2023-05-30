# КЛАССИФИКАЦИЯ КОЛЕСНЫХ ФОРВАРДЕРОВ НА ОСНОВЕ КЛАСТЕРИЗАЦИИ В ПРОСТРАНСТВЕ ГЛАВНЫХ КОМПОНЕНТ

*Для запуска, нажмите кнопку ниже:*
 
 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/danielka777/time-series-in-complex-network/blob/main/Run.ipynb)


Целью работы является разработка классификации колесных форвардеров с учетом расширенного перечня эксплуатационных характеристик.

Материалом для разработки классификации являются сведения, представленные на официальных сайтах производителей Ponsse, Rottne, Komatsu, John Deere, Ecolog, HSM

Объекты в выборке имеют по 14 признаков.

Методы решения: Снижение размерности признакового пространства: метод главных компонент. 
Кластеризация методом k-средних.

Быков Данил – Программирование в Python
Трубников Алексей – Препроцессинг данных, программирование
Хитров Егор – Математическая составляющая
Шепталенко Анастасия – Сбор данных, составление стеков технологий

## Возможности программы
* На выходе вы получаете сетевую структуру в формате csv
* Конвертирование аудиофайлов (mp3, wav) в сетевую структуру
* Конвертирование временных рядов (csv, xls) в сетевую структуру
* Конвертация аудиофайлов с разбивкой на одинаковые временные участки
* В случае использования алгоритмов скользящего окна, выбор размера окна
* Настройка частоты дискретизации аудиофайла

## Реализованные алгоритмы конвертирования
* Алгоритм прямой видимости (nvg)
* Алгоритм горизонтальной видимости (hvg)
* Алгоритм прямой видимости с применением метода скользящего окна (snvg)
* Алгоритм горизонтальной видимости с применением метода скользящего окна (shvg)

*Функции реализации алгоритмов:* 

[![Open In ColabFunc](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/danielka777/time-series-in-complex-network/blob/main/Functions.ipynb)

##
«Программный инструмент подготовлен при частичной финансовой поддержке РФФИ и МОКНСМ в рамках научного проекта №  20-57-44002»
