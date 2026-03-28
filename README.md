# Yolov5-object-detection
names: ['Center', 'Donut', 'Scratch', 'Edge-Loc', 'Edge-Ring', 'Loc', 'Near-full', 'Random']
to buid again you need to download all datasheet.
structure like:
This datasheet comes from  WM-118K. I used Roboflow to add labels, filters and split to 70-20-10.
structure
Datasheet/images/
                /train/
                      image.png
                /test
                /val
         /labels/
                /train
                      /image.txt
                /test
                /val
model/yolo/weight/best.pt
Run the model by using best.pt
