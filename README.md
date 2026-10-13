## Выпускная квалификационная работа бакалавра.

## Московский авиационный институт (национальный исследовательский университет), 2026.

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
| Colorectal Histology MNIST (версия с Kaggle) | 8 | 5 000 (по 625 в каждом классе, 28×28, оттенки серого) | [Kaggle: kmader/colorectal-histology-mnist](https://www.kaggle.com/datasets/kmader/colorectal-histology-mnist) |
| Malaria Cell Images Dataset (NLM-Falciparum-Thin-Cell-Images) | 2 | 27 558 (по 13 779 в каждом классе, цветные, разного размера) | [NIH / NLM: Malaria Datasets](https://lhncbc.nlm.nih.gov/LHC-research/LHC-projects/image-processing/malaria-datasheet.html) |

**Гистология.** Набор представляет собой уменьшенную копию набора Kather,
размещённую на Kaggle. Оригинальные изображения опубликованы авторами под лицензией
CC BY 4.0 (DOI: 10.5281/zenodo.53169).

> Kather J.N., Weis C.-A., Bianconi F., et al. Multi-class texture analysis in
> colorectal cancer histology // Scientific Reports. 2016. V. 6. Article 27988.

**Малярия.** Набор предоставлен Национальной медицинской библиотекой США.

> Source: U.S. National Library of Medicine (NLM/NIH).
>
> Rajaraman S., Antani S.K., Poostchi M., et al. Pre-trained convolutional neural
> networks as feature extractors towaretection in thin
> blood smear images // PeerJ. 2018. V. 6. e4568.

Файлы данных в репозиторий не включены. Скачайте их по ссылкам из таблицы и
положите в папку `DataSet/`

## Стек

Python 3, NumPy, SciPy, Kymatio, PyTorch, scikit-learn, Matplotlib, Jupyter.
Вычисления выполняются в Google Colab.

## Литература

1. Mallat S. Group Invariant Scattering // Comm. Pure Appl. Math. 2012. V. 65, № 10. P. 1331–1398.
2. Bruna J., Mallat S. Invariant Scattering Convolution Networks // IEEE TPAMI. 2013. V. 35, № 8. P. 1872–1886.
3. Andreux M. et al. Kymatio: Scattering Transforms in Python // JMLR. 2020. V. 21, № 60.
