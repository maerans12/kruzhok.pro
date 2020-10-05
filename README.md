# kruzhok.pro
Надо установить [yolo](https://github.com/ultralytics/yolov3) действуя инструкции, потом установить Pytorch и Torchvision выполнив команду для установки в cmd: 
```
pip install torch==1.5.0 torchvision==0.6.0 --f https://download.pytorch.org/whl/torch_stable.html
```

затем необходимо поместить изображения для обработки алгоритмом в папку (…\yolov3_master\data\samples\). Результат появится в папке (…\yolov3_master\output\).

Для запуска модели выполнить команду в cmd:
```
python detect.py --weights weights/last.pt --cfg data/yolov3-spp.cfg --names data/objects.names
```
