# test_task
Не до конца понял пункт про "Вычисление площади фигуры без знания типа фигуры в compile-time", прочитал на вики про Compile Time, но все равно не уверен, что конкретно имеется ввиду.


После окончания стажировки готов выйти на фуллтайм. По утрам и днем я обычно нахожусь в лаборатории, но готов работать по вечерам. Также в некоторые дни я дома с утра, так что проблем не возникнет.


Можно скачать и импортировать библиотеку, помещая FindArea.py в директорию со своим файлом, либо скачав с PypI. В таком случае нужно поступать так:
pip install AreaFinding==0.1,
from FindArea.FindArea import FindArea,
a = FindArea(),
print(a.triangle(6, 8, 10)) #как пример
