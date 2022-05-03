To convert ONNX model to IR format use the command below.
# FP32:
```bash
mo --input_model D:\Users\amira\openvino_env\Lib\site-packages\openvino\model_zoo\models\group_project\enet_b2_8\enet_b2_8.onnx -o D:\Users\amira\openvino_env\Lib\site-packages\openvino\model_zoo\models\group_project\enet_b2_8 --data_type FP32
```
# FP16:
mo --input_model D:\Users\amira\openvino_env\Lib\site-packages\openvino\model_zoo\models\group_project\enet_b2_8\enet_b2_8.onnx -o D:\Users\amira\openvino_env\Lib\site-packages\openvino\model_zoo\models\group_project\enet_b2_8 --data_type FP16
