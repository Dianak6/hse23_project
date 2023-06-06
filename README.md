# hse23_project
Гистоновая метка: **H3K36me**

Белок: **SMYD2**

![image](https://github.com/Dianak6/hse23_project/assets/114064027/46359197-9114-4b80-be8d-b5450ebb144b)

Функция белка: Histone modification write

Необходим для нормального развития организма и регуляции ряда патофизиологических процессов. Является важнейшим регулятором сердечно-сосудистых заболеваний и рака.

Ссылки на статьи:
https://clinicalepigeneticsjournal.biomedcentral.com/articles/10.1186/s13148-019-0711-4
https://www.nature.com/articles/nature05287

Экспрессируется в основном в сердце.

![image](https://github.com/Dianak6/hse23_project/assets/114064027/1e8a400f-adec-4a43-85b5-07d5c0a8c40d)

Домены: SET super family 

![image](https://github.com/Dianak6/hse23_project/assets/114064027/7a8a9913-ef57-4a9e-a435-2e60aedc669e)

Выравнивание было выполнено в программе MEGAX

Выравнивание белковых последовательностей для гистона 2A

![image](https://github.com/Dianak6/hse23_project/assets/114064027/34c9a677-de52-4cc1-ac40-a00a270140b3)

Большая часть последовательностей очень похожи между собой, поэтому можно считать, что они кодируют один и тот же ген. Но некоторые последовательности другие

Выравнивание белковых последовательностей для гистона 2B

![image](https://github.com/Dianak6/hse23_project/assets/114064027/3959fa5e-5fda-4564-a1b8-9720c1ac406f)

Также как и у предыдущего гистона, большая часть представленных последовательностей очень похожи между собой, поэтому можно считать, что они кодируют один и тот же ген. Остальные же различаются. Возможно, это связано с тем, что они похожи между собой по пространственному строению и выполняют одинаковые функции, но последовательности различаются.

Выравнивание белковых последовательностей для гистона 3

![image](https://github.com/Dianak6/hse23_project/assets/114064027/2c836b42-a8ed-47eb-8c3c-2fea79fff690)

Все последовательности одинаковые, поэтому можно считать, что они кодируют один и тот же ген.

Выравнивание белковых последовательностей для гистона 4

![image](https://github.com/Dianak6/hse23_project/assets/114064027/405d74e9-e5da-4737-8b8e-de2fca7e89fc)

Все последовательности одинаковые, поэтому можно считать, что они кодируют один и тот же ген.

Выбрала по одной аминокислоте каждого гистона (файлы формата fasta приложены в папке data)

С помощью Blastp получаем значения evalue для всех организмов
```
blastp  -query H2A.fasta  -db thermococcus.faa  -out h2a.blast  -outfmt 7
```
Пример выходного файла Blastp
![image](https://github.com/Dianak6/hse23_project/assets/114064027/327be637-4023-4b1b-99dc-c43580670d5d)

Таблица со значениями evalue после выравнивания

![image](https://github.com/Dianak6/hse23_project/assets/114064027/74526776-7bc3-428d-8a3a-1d32243d382a)

![image](https://github.com/Dianak6/hse23_project/assets/114064027/518a0695-7f65-4b45-a9a7-7ccbd5bd4150)

Далее рисую тепловую карту (блокнот с кодом - https://colab.research.google.com/drive/1DBHOT5RKECCw3C7pYM2RQX_cFLlPfzFX?usp=sharing )

![image](https://github.com/Dianak6/hse23_project/assets/114064027/5b42efee-269f-48f5-8454-e5ebf1b4107c)

,где 0-H1A 1-H1B 2-H2 3-H3 4-SMYD2

На тепловой карте видно, что даннаый белок SMYD2 проявляется на уровне yeast и ciliate. Высокий коэффициент схожести с human, mouse, zebrafish. 
