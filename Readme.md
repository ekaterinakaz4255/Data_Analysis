# Аналитика данных на Python
Данный репозиторий содержит ноутбуки с учебными проектами по анализу данных на различных датасетах. 

## 1. Анализ резюме из HeadHunter 
Ноутбук [HeadHunter_analysis.ipynb](HeadHunter_analisys.ipynb)

Проект состоит из 5 частей:
1. Базовый анализ структуры данных
2. Преобразование данных
3. Разведывательный анализ
4. Очистка данных
5. Интеграция данных о средним зарплатам по регионам

Необходимые данные для загрузки можно получить по ссылкам:

[Ссылка](https://disk.yandex.ru/d/BLS9QE8lenCRsw) на датасет с данными по резюме

[Ссылка](https://disk.yandex.ru/d/R_PiV3Ra8MDqWA) на датасет с данными по обменному курсу

[Ссылка](https://disk.yandex.ru/d/NXE3SqPhW7I_3A) на обработанный финальный датасет

[Ссылка](https://disk.yandex.ru/i/xrxHdzF_o9-2Cw ) на датасет "Среднемесячная заработная плата по субъектам Российской Федерации за 2019-2023гг.", источник [ЕМИСС](https://www.fedstat.ru/indicator/57824)

[Датасет](https://disk.yandex.ru/i/jnzQA_yeFJgmvg) с регионами и городами

## 2. Статистический анализ датасета по теннису
Ноутбук [Tennis_matches_analysis.ipynb](Tennis_matches_analysis.ipynb)

Цель - проверить, как изменился мир тенниса за последнее время. 

В данном проекте выполняется небольшая предобработка данных с последующим статистическим анализом нескольких поставленных гипотез. В ходе анализа формируются соответствующие выборки, изучается распределение и характер данных в выборках, подбирается соответствующий статистический тест для проверки той или иной гипотезы. 

Для анализа был использован этот [датасет](https://github.com/JeffSackmann/tennis_atp), применялись только данные из одиночного разряда (файлы в формате ```atp_matches_YYYY.csv```). 

## 3. Статистический анализ пространственной транскриптомики пациентов с плоскоклеточным раком

Ноутбук [bioinformatics_analysis.ipynb](bioinformatics_analysis.ipynb)

Цель - проанализировать датасет и сделать статистически обоснованные выводы.

Необходимо проанализировать [биоинформатический датасет](https://lms.skillfactory.ru/asset-v1:SkillFactory+MFTIBIO+SEP2023+type@asset+block@community_dataset.csv) по пространственной транскриптомике ([дополнительная информация по теме](https://institut-curie.org/popin/spatial-omics)) пациентов с плоскоклеточным раком. В нем клетки (колонка ```cell_type```) объединены в микроокружения (колонка ```cell_interaction```) в зависимости от взаимодействия этих клеток. Основная задача - поиск отличий в организации микроокружения у пожилых и молодых пациентов (колонка ```age_group```).
