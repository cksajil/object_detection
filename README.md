# Object_detection
Object Detection Using Pretrained Models

# Usage

```bash
wget https://storage.googleapis.com/download.tensorflow.org/models/tflite/coco_ssd_mobilenet_v1_1.0_quant_2018_06_29.zip
unzip coco_ssd_mobilenet_v1_1.0_quant_2018_06_29.zip -d Sample_TFLite_model
```

```python
python3 runme.py --modeldir=Sample_TFLite_model
```