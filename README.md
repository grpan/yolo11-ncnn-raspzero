# yolo11-ncnn

## Benchmark.
| Model  | Infer time|
| ------------- | :-------------: |
| YOLOv5s  | 54 ms |
| YOLO11n  | 48 ms |

## How to build and run
``` shell
mkdir build
cd build 
cmake ..
make 
./yolov11_ncnn ../data/bus.jpg
```

## Show
![show](./data/output.jpg)

## reference

<https://github.com/ultralytics/ultralytics><br>
<https://github.com/Tencent/ncnn><br>
<https://github.com/triple-Mu/ncnn-examples>
<https://qengineering.eu/install-ncnn-on-raspberry-pi-4.html>
