# paddleocr-onnx

PaddleOCR with ONNX

## Installation

```bash
pip install git+https://github.com/0xNOY/paddleocr-onnx.git
```

## Usage

```python
import cv2
from paddleocr_onnx impoer PaddleOcrONNX, get_paddleocr_parameter


param = get_paddleocr_parameter()
model = PaddleOcrONNX(param)

img = cv2.imread("foo.jpg")

bboxes, texts_n_scores, time = model(img)
```
