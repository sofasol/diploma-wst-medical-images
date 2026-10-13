Выпускная квалификационная работа бакалавра.
Московский авиационный институт (национальный исследовательский университет), 2026.

**Автор:** Солодова София Михайловна, группа М8О-409Б-23
**Научный руководитель:** Битюков Юрий Иванович

## Тема

Сравнительный анализ вейвлет-преобразования рассеяния (WST) и сверточных
нейронных сетей (CNN) для классификации медицинских изображений.

## Цель

Определить, при каком объёме обучающей выборки и каких параметрах WST
качество классификации сопоставимо с качеством CNN.

## Данные

| Набор | Классов | Изображений | Источник |
|---|---|---|---|
| Colorectal Histology MNIST | 8 | 5 000 (28×28, оттенки серого) | Kather J.N. et al., Scientific Reports 6:27988, 2016 |
| Malaria Cell Images Dataset | 2 | 27 558 (цветные) | Rajaraman S. et al., PeerJ 6:e4568, 2018 |

Файлы данных в репозиторий не включены.

## Стек

Python 3, NumPy, SciPy, Kymatio, PyTorch, scikit-learn, Matplotlib, Jupyter.
Вычисления выполняются в Google Colab.

## Литература

1. Mallat S. Group Invariant Scattering // Comm. Pure Appl. Math. 2012. V. 65, № 10. P. 1331–1398.
2. Bruna J., Mallat S. Invariant Scattering Convolution Networks // IEEE TPAMI. 2013. V. 35, № 8. P. 1872–1886.
3. Andreux M. et al. Kymatio: Scattering Transforms in Python // JMLR. 2020. V. 21, № 60.
