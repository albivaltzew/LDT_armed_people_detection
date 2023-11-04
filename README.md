# Система видеодетекции вооруженных людей
Команда Чемпионы. Лидеры Цифровой Трансформации 2023. Краснодарский край. 
1. Предлагается свести данную задачу к поиску оружия, так как если человек стоит в позе стрелка, то очевидно, что видно оружие.
2. Если человек несет оружие в кармане, то в теории у него меняется походка из-за нервозности и нужно решать задачу Pose Estimation, но это не входит задачу данного хакатона и требует дальнейшего изучения.
3. В связи с этим первым шагом является сбор датасета с различными видами оружия.
   
   Пистолеты:
   https://public.roboflow.com/object-detection/pistols
   Смешной датасет:
   https://universe.roboflow.com/abm/gun-violent-detection
   51к изображений:
   https://paperswithcode.com/dataset/gun-detection-dataset
   9к изображений, есть в коридоре
   https://universe.roboflow.com/gun-detection-1lttj/gun-detection-1fbbu


Полезные ссылки/заметки по CV части:
1. https://medium.com/mlearning-ai/computer-vision-with-unreal-engine-generate-rich-object-detection-data-64c613e0121f
2. http://docs.unrealcv.org/en/master/index.html
