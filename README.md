# hse23_project
Выравнивание белковых последовательностей для гистона 2A

![image](https://github.com/Dianak6/hse23_project/assets/114064027/34c9a677-de52-4cc1-ac40-a00a270140b3)

Выравнивание белковых последовательностей для гистона 2B

![image](https://github.com/Dianak6/hse23_project/assets/114064027/3959fa5e-5fda-4564-a1b8-9720c1ac406f)

Выравнивание белковых последовательностей для гистона 3

![image](https://github.com/Dianak6/hse23_project/assets/114064027/2c836b42-a8ed-47eb-8c3c-2fea79fff690)

Выравнивание белковых последовательностей для гистона 4

![image](https://github.com/Dianak6/hse23_project/assets/114064027/405d74e9-e5da-4737-8b8e-de2fca7e89fc)


С помощью Blastp получаем значения evalue для всех организмов
```
blastp  -query H2A.fasta  -db thermococcus.faa  -out h2a.blast  -outfmt 7
```
Пример выходного файла Blastp
![image](https://github.com/Dianak6/hse23_project/assets/114064027/fb3c2618-7095-4156-9bd3-c4107638bdae)

Таблица со значениями evalue после выравнивания

![image](https://github.com/Dianak6/hse23_project/assets/114064027/da8faff4-43bf-4a79-a0cd-146696d29a9b)

![image](https://github.com/Dianak6/hse23_project/assets/114064027/d84649e7-077c-493f-89c4-240704ef8fa5)

Далее рисую тепловую карту (блокнот с кодом - https://colab.research.google.com/drive/1DBHOT5RKECCw3C7pYM2RQX_cFLlPfzFX?usp=sharing )

![image](https://github.com/Dianak6/hse23_project/assets/114064027/6af29292-f0fa-4565-946b-f042eb29ffe1)

,где 0-H1A 1-H1B 2-H2 3-H3 4-SMYD2
