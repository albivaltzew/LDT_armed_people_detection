# Система видеодетекции вооруженных людей
Команда Чемпионы. Лидеры Цифровой Трансформации 2023. Краснодарский край. 
1. Предлагается свести данную задачу к поиску оружия, так как если человек стоит в позе стрелка, то очевидно, что видно оружие.
2. Если человек несет оружие в кармане, то в теории у него меняется походка из-за нервозности и нужно решать задачу Pose Estimation, но это не входит задачу данного хакатона и требует дальнейшего изучения.
3. В связи с этим первым шагом является сбор датасета с различными видами оружия.
   
   - Пистолеты [Roboflow](https://public.roboflow.com/object-detection/pistols)
   - Есть сцены ограблений, но есть и мемы, и просто оружие со стоков [Roboflow](https://universe.roboflow.com/abm/gun-violent-detection)
   - 51к изображений [Paperswithcode](https://paperswithcode.com/dataset/gun-detection-dataset):
   - 9k  изображений, есть в коридоре [Roboflow](https://universe.roboflow.com/gun-detection-1lttj/gun-detection-1fbbu)
   - 3.5к YOLOv5 формат с классами ("пистолет", "смартфон", "нож", "кошелек", "билет", "карта") [GitHub](https://github.com/ari-dasci/OD-WeaponDetection/tree/master/Weapons%20and%20similar%20handled%20objects)
   - (а тут все датасеты на поиск оружия, включая предыдущий) [GitHub](https://github.com/ari-dasci/OD-WeaponDetection)
   - 5к - Китайцы собрали датасет по видео с ютуба. Есть класс "person" и "gun" - есть разделение для YOLOv5 [YouTube-GDD](https://github.com/UCAS-GYX/YouTube-GDD)
   


Полезные ссылки/заметки по CV части:
1. Собираем датасет через Unreal Engine 4 [medium](https://medium.com/mlearning-ai/computer-vision-with-unreal-engine-generate-rich-object-detection-data-64c613e0121f)
2. [unrealCV](http://docs.unrealcv.org/en/master/index.html)
