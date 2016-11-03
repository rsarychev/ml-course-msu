# Семинары по машинному обучению, ВМК МГУ

<img src="http://www.machinelearning.ru/wiki/images/2/28/ML_surfaces.png" width="280">

Конспекты, код и прочие материалы к семинарам по машинному обучению, проводимым на ВМК МГУ.

Почта для заданий: ml.cmc.msu@gmail.com

[Страница курса на machinelearning.ru](http://www.machinelearning.ru/wiki/index.php?title=Машинное_обучение_%28семинары%2C_ВМК_МГУ%29)

[Канал в telegram для объявлений](https://telegram.me/joinchat/A5rlQD_hqqV2n5AOWEVrVA)

[Оценки за курс](https://docs.google.com/spreadsheets/d/1A5BJs_dJcmqY2KVBUCTWlXueTeFWNVT6Tbx5e3dN6_c/edit#gid=2044373835)

На семинары и работу ассистента можно оставить отзыв: [[анонимно без регистрации и смс](https://docs.google.com/forms/d/1j8zMReMtl-BCeAVISxx_v42_y8GAVeolofFuAHQjHBc/viewform)]

Курс лекций на ФКН ВШЭ: [[wiki](http://wiki.cs.hse.ru/Машинное_обучение_1)] [[материалы](https://github.com/esokolov/ml-course-hse)]

## Правила выставления оценок

**Итоговая контрольная работа:**

1. На последней лекции будет проведена контрольная работа, которая затронет все темы, изученные в течение семестра.
2. Контрольная оценивается по двухбалльной шкале (зачет/незачет), незачет влечет за собой недопуск к экзамену.
3. Студент, не получивший допуск, переписывает на экзамене контрольную. В случае успеха он сдает экзамен на первой пересдаче. В случае незачета он снова переписывает контрольную на первой пересдаче, и так далее.

**Семинары:**

1. На семинарах по каждой пройденной теме будут проводиться проверочные работы. Каждая проверочная оценивается по пятибалльной шкале. В зависимости от оценки за проверочную, студент освобождается от части или от всех задач по этой теме на итоговой контрольной работе.
2. На семинарах будут выдаваться практические задания, которые будут оцениваться по десятибалльной шкале.
3. В течение семестра будут проводиться конкурсы по анализу данных. Правила выставления оценок для каждого конкурса указываются в условиях самого конкурса.
4. Оценка за работу в семестре равна сумме оценок за проверочные работы, практические задания и конкурсы.
5. Если оценка за работу в семестре не меньше 100% от максимальной оценки за проверочные и лабораторные работы, то студент освобождается от написания итоговой контрольной и получает допуск к экзамену автоматом.
6. Если оценка за работу в семестре не меньше 80% от максимальной оценки за проверочные и лабораторные работы и конкурсы, то студент получает +1 балл на экзамене (при условии получения положительной оценки).
7. В конце семестра разрешается переписать все проверочные, пропущенные по уважительной причине.

## Занятия

| Дата | Номер | Тема | Материалы | ДЗ |
| :---: | :---: | --- | --- | --- |
| 2 сентября | Семинар 1 | Вводное занятие: <ul><li>Основные термины в машинном обучении</li><li>Этапы решения задачи анализа данных</li></ul> | [Конспект](ML16/lecture-notes/Sem01_intro.pdf) | |
| 16 сентября | Семинар 2 | Метрические методы: <ul><li>Особенности метрических методов: чувствительность к масштабу и шуму, проклятие размерности</li><li>Примеры метрик</li><li>Метрики на категориальных признаках</li><li>Введение в NumPy, SciPy, Pandas, Scikit-Learn</li></ul> | [Конспект](ML16/lecture-notes/Sem02_knn.pdf)<br>[Notebook](ML16/src/Sem02_python_intro.ipynb) | |
| 23 сентября | Семинар 3 | Метрические методы: <ul><li>Locality-sensitive hashing</li><li>Векторизация операций в NumPy</li><li>Практические особенности kNN и LSH</li></ul> | [Конспект](ML16/lecture-notes/Sem03_knn.pdf)<br>[Notebook](ML16/src/Sem03_numpy_knn.ipynb) | [Домашнее задание](ML16/homeworks/Sem03_knn_hw.pdf) |
| 30 сентября | Семинар 4 | Решающие деревья: <ul><li>Жадное построение решающих деревьев</li><li>Критерии информативности</li></ul> | [Конспект](ML16/lecture-notes/Sem04_trees.pdf) | [Домашнее задание](ML16/homeworks/Sem04_trees_hw.pdf) |
| 7 октября | Семинар 5 | Решающие деревья: <ul><li>Стрижка деревьев</li><li>Учет пропущенных значений</li><li>Работа с категориальными признаками</li><li>Случайный лес</li></ul> | [Конспект](ML16/lecture-notes/Sem04_trees.pdf)<br>[Notebook](ML16/src/Sem05_trees.ipynb) | |
| 14 октября | Семинар 6 | Метрики качества: <ul><li>Доля правильных ответов, точность и полнота</li><li>AUC-ROC</ul> | Теория: [конспект](https://github.com/esokolov/ml-course-hse/blob/master/2016-fall/lecture-notes/lecture04-linclass.pdf), раздел 2 <br> <br> Практика: [конспект](https://github.com/esokolov/ml-course-hse/blob/master/2016-fall/seminars/sem05-linclass.pdf), задача 1.1 | |
| 21 октября | Семинар 7 | Метрики качества: <ul><li>AUC-ROC, продолжение</ul> | Теория: [конспект](https://github.com/esokolov/ml-course-hse/blob/master/2016-fall/lecture-notes/lecture04-linclass.pdf), раздел 2 <br> <br> Практика: [конспект](https://github.com/esokolov/ml-course-hse/blob/master/2016-fall/seminars/sem05-linclass.pdf), задачи 1.2, 1.3, 1.4 | [Домашнее задание](ML16/homeworks/Sem07_metrics_hw.pdf) |

## Практические задания

Если задание сдано и было проверено до дедлайна, то разрешается без штрафа внести исправления и прислать новую версию.
Новую версию необходимо прислать не позднее мягкого дедлайна.
Дальнейшие исправления возможны на усмотрение преподавателей.

Чтобы мы точно успели проверить решение, рекомендуем присылать хотя бы за неделю до дедлайна.

Обратите внимание, что по каждому заданию даётся два дедлайна: мягкий и жёсткий.
За сдачу задания после мягкого дедлайна оценка понижается на 0.05\*n\*(n + 1) баллов, где n — количество дней просрочки.
Оценка за задание не может быть отрицательной.

### Задание 1: Pandas, kNN и решающие деревья

[Условие](ML16/labs/lab01_pandas_knn_trees.ipynb)

Дата выдачи: 16.10.2016

Мягкий дедлайн: 30.10.2016, 23:59 MSK

Жёсткий дедлайн: 06.11.2016 23:59 MSK


## Соревнования

По каждому соревнованию в течение недели после его окончания необходимо прислать краткий отчёт о решении
и код, с помощью которого можно воспроизвести решение.

### Соревнование 1: вероятность победы в Dota 2

Дата выдачи: 21.10.2016

Дедлайн для индивидуального участия: 6.11.2016

Старт командного участия: 7.11.2016

Дедлайн для командного участия: 20.11.2016

Соревнование: https://inclass.kaggle.com/c/cmc-msu-machine-learning-fall-2016-2017-competition-1

Ссылка для участия: [link](https://kaggle.com/join/cmc_msu_fall_contest_1_c83bd9mw)

[Описание задачи](ML16/contests/contest01-dota-statement.ipynb)

За первое, второе и третье место в индивидуальной части контеста ставится 10, 9 и 8 баллов соответственно.
За места с четвертого и по самое последнее выставляется от 7 до 1 баллов по равномерной сетке.
Участникам, которые не смогли преодолеть бейзлайн, оценка обнуляется.

По окончании индивидуальной части участники делятся по рейтингу на 3 или 4 корзинки (в зависимости от их количества),
из которых собираются случайные равномерные по силе команды.
В командной части за места с первого по третье ставятся 4, 3 и 2 балла, а дальше по равномерной сетке до 1.
Также в каждой команде будет подсчитан процент улучшения качества относительно лучшего из участников;
исходя из этого рейтинга, будут проставлены дополнительные баллы по такому же принципу, как и в предыдущем предложении.
Следует помнить, что оценка в командной части для участников из нижних корзинок будет сильно зависить от их понимания решения (отчета и выступления).

По окончании контестов участники, занявшие первые 3 места должны выступить с кратким рассказом о своем решении. Если все присланные группой решения будут тривиальными, то преподаватель имеет право снизить максимальную оценку до 10 или 5 баллов.

**Альтернативное соревнование**

[Sberbank Data Science Contest](https://sdsj.ru/contest.html)

Правила выставления оценок аналогичны правилам по индивидуальной части соревнования по Dota.
Никаких ограничений на методы решения не накладывается.
Командное решение не предусмотрено.
Если студент участвовал и в индивидуальном соревновании по Dota, и в данном соревновании,
то ему будет выставлена максимальная из двух оценок, а не сумма.
Возможно решение сначала только контеста Сбербанка, а потом командное учебного по Dota,
но нужно заранее (за пару дней до начала командной части) уведомить об этом преподавателей.
В зависимости от количества участников контеста шкала может быть понижена и/или разрежена.
Также за высокие места среди всех участников в общем зачете или по каждой задаче могут выдаваться серьёзные бонусы.


