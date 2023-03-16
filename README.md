## Yolov8 ReID

Train

```python
from ultralytics.yolo.engine.model import YOLO

model = YOLO(model="yolov8n-reid.yaml", task='reid')
model.train(data="market1501.yaml", epochs=100)
```
