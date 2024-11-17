Please download [summary.xlsx](summary.xlsx) to view the most recent results. [This page](https://docs.google.com/spreadsheets/d/e/2PACX-1vSCu8F7Hwck-AGJ5kWxi2G3xhO5MJoc_igybvsxjCt-2fEEYyf2BIcR0rTXW0eUzg/pubhtml) shows the results which may not be the latest. 
 ```
[2024-11-17 06:57:15,451 submission_checker.py:3109 INFO] Results=46, NoResults=0, Power Results=0
[2024-11-17 06:57:15,451 submission_checker.py:3116 INFO] ---
[2024-11-17 06:57:15,451 submission_checker.py:3117 INFO] Closed Results=19, Closed Power Results=0

[2024-11-17 06:57:15,451 submission_checker.py:3122 INFO] Open Results=27, Open Power Results=0

[2024-11-17 06:57:15,451 submission_checker.py:3127 INFO] Network Results=0, Network Power Results=0

[2024-11-17 06:57:15,451 submission_checker.py:3132 INFO] ---
[2024-11-17 06:57:15,451 submission_checker.py:3134 INFO] Systems=4, Power Systems=0
[2024-11-17 06:57:15,451 submission_checker.py:3138 INFO] Closed Systems=3, Closed Power Systems=0
[2024-11-17 06:57:15,451 submission_checker.py:3143 INFO] Open Systems=2, Open Power Systems=0
[2024-11-17 06:57:15,451 submission_checker.py:3148 INFO] Network Systems=0, Network Power Systems=0
[2024-11-17 06:57:15,451 submission_checker.py:3153 INFO] ---
[2024-11-17 06:57:15,451 submission_checker.py:3158 INFO] SUMMARY: submission looks OK
INFO:root:       ! call "postprocess" from /home/runner/CM/repos/mlcommons@cm4mlops/script/run-mlperf-inference-submission-checker/customize.py

```

|    | Organization   | Availability   | Division   | SystemType      | SystemName    | Platform                                                       | Model        | MlperfModel   | Scenario     |       Result | Accuracy              |   number_of_nodes | host_processor_model_name            |   host_processors_per_node |   host_processor_core_count | accelerator_model_name   |   accelerators_per_node | Location                                                                                                          | framework   | operating_system                                | notes                             |   compliance |   errors | version   |   inferred | has_power   | Units        | weight_data_types   |
|---:|:---------------|:---------------|:-----------|:----------------|:--------------|:---------------------------------------------------------------|:-------------|:--------------|:-------------|-------------:|:----------------------|------------------:|:-------------------------------------|---------------------------:|----------------------------:|:-------------------------|------------------------:|:------------------------------------------------------------------------------------------------------------------|:------------|:------------------------------------------------|:----------------------------------|-------------:|---------:|:----------|-----------:|:------------|:-------------|:--------------------|
|  0 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9    | bert-99.9     | Offline      |  1675.34     | F1: 90.8832407068292  |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/offline           | TensorRT    | Ubuntu 20.04 (linux-6.8.0-48-generic-glibc2.31) | Automated by MLCommons CM v3.4.1. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | fp16                |
|  1 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Server       |  3841.12     | F1: 90.25897829249658 |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/server              | TensorRT    | Ubuntu 20.04 (linux-6.8.0-48-generic-glibc2.31) | Automated by MLCommons CM v3.4.1. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
|  2 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Offline      |  4132.06     | F1: 90.15673510616978 |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/offline             | TensorRT    | Ubuntu 20.04 (linux-6.8.0-48-generic-glibc2.31) | Automated by MLCommons CM v3.4.1. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
|  3 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | SingleStream |     1.0117   | F1: 90.26682135974633 |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/singlestream        | TensorRT    | Ubuntu 20.04 (linux-6.8.0-48-generic-glibc2.31) | Automated by MLCommons CM v3.4.1. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
|  4 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | Server       | 35357.7      | acc: 76.078           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/server             | TensorRT    | Ubuntu 20.04 (linux-6.8.0-48-generic-glibc2.31) | Automated by MLCommons CM v3.4.1. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
|  5 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | Offline      | 43780.7      | acc: 76.078           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/offline            | TensorRT    | Ubuntu 20.04 (linux-6.8.0-48-generic-glibc2.31) | Automated by MLCommons CM v3.4.1. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
|  6 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | SingleStream |     0.277192 | acc: 76.064           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/singlestream       | TensorRT    | Ubuntu 20.04 (linux-6.8.0-48-generic-glibc2.31) | Automated by MLCommons CM v3.4.1. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
|  7 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | MultiStream  |     0.467317 | acc: 76.064           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/multistream        | TensorRT    | Ubuntu 20.04 (linux-6.8.0-48-generic-glibc2.31) | Automated by MLCommons CM v3.4.1. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
|  8 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet    | retinanet     | Server       |   637.174    | mAP: 37.324           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/server            | TensorRT    | Ubuntu 20.04 (linux-6.8.0-48-generic-glibc2.31) | Automated by MLCommons CM v3.4.1. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
|  9 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet    | retinanet     | Offline      |   863.79     | mAP: 37.315           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/offline           | TensorRT    | Ubuntu 20.04 (linux-6.8.0-48-generic-glibc2.31) | Automated by MLCommons CM v3.4.1. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 10 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet    | retinanet     | SingleStream |     1.75875  | mAP: 37.358           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/singlestream      | TensorRT    | Ubuntu 20.04 (linux-6.8.0-48-generic-glibc2.31) | Automated by MLCommons CM v3.4.1. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 11 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet    | retinanet     | MultiStream  |    10.9208   | mAP: 37.353           |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/multistream       | TensorRT    | Ubuntu 20.04 (linux-6.8.0-48-generic-glibc2.31) | Automated by MLCommons CM v3.4.1. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 12 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | Offline      |     4.17015  | DICE: 0.86236         |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/offline        | TensorRT    | Ubuntu 20.04 (linux-6.8.0-48-generic-glibc2.31) | Automated by MLCommons CM v3.4.1. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 13 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | SingleStream |   433.198    | DICE: 0.86236         |                 1 | 13th Gen Intel(R) Core(TM) i9-13900K |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/singlestream   | TensorRT    | Ubuntu 20.04 (linux-6.8.0-48-generic-glibc2.31) | Automated by MLCommons CM v3.4.1. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 14 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9    | bert-99.9     | Offline      |  3342.88     | F1: 90.8832407068292  |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/offline           | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | fp16                |
| 15 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Server       |  6061.5      | F1: 90.25897829249658 |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/server              | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 16 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Offline      |  8174.99     | F1: 90.15673510616978 |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/offline             | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 17 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | SingleStream |     1.05149  | F1: 90.26682135974633 |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/singlestream        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 18 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | Server       | 73743.9      | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/server             | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 19 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | Offline      | 87685.9      | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/offline            | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 20 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | SingleStream |     0.31936  | acc: 76.064           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/singlestream       | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 21 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | MultiStream  |     1.04553  | acc: 76.064           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/multistream        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 22 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet    | retinanet     | Server       |  1213.53     | mAP: 37.335           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/server            | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 23 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet    | retinanet     | SingleStream |     2.36173  | mAP: 37.345           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/singlestream      | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 24 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet    | retinanet     | MultiStream  |     6.42005  | mAP: 37.376           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/multistream       | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 25 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | Offline      |     8.25245  | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/offline        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 26 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | SingleStream |   432.029    | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/singlestream   | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 27 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia-gpu-TensorRT-default_config                   | 3d-unet-99.9 | 3d-unet-99.9  | Offline      |     8.29596  | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/3d-unet-99.9/offline                        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 28 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia-gpu-TensorRT-default_config                   | 3d-unet-99.9 | 3d-unet-99.9  | SingleStream |   431.158    | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/3d-unet-99.9/singlestream                   | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 29 | MLCommons      | available      | closed     | datacenter,edge | gh_ubuntu_x86 | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config               | resnet50     | resnet        | Server       | 73015.2      | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/server                         | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 30 | MLCommons      | available      | closed     | datacenter,edge | gh_ubuntu_x86 | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config               | resnet50     | resnet        | Offline      | 87471.2      | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/offline                        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 31 | MLCommons      | available      | closed     | datacenter,edge | gh_ubuntu_x86 | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config               | resnet50     | resnet        | SingleStream |     0.342055 | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/singlestream                   | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 32 | MLCommons      | available      | closed     | datacenter,edge | gh_ubuntu_x86 | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config               | resnet50     | resnet        | MultiStream  |     0.951987 | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/multistream                    | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 33 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9    | bert-99.9     | Server       |     0.888629 | F1: 90.89074704580993 |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/server          | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 34 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9    | bert-99.9     | Offline      |  3314.54     | F1: 90.8832407068292  |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/offline         | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 35 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Server       |  6061.5      | F1: 90.25897829249658 |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/server            | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 36 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Offline      |  8219.33     | F1: 90.15673510616978 |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/offline           | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 37 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | SingleStream |     1.03994  | F1: 90.26682135974633 |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/singlestream      | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 38 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99   | 3d-unet-99    | Offline      |     8.27882  | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99/offline        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 39 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99   | 3d-unet-99    | SingleStream |   431.284    | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99/singlestream   | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 40 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | Server       | 73743.9      | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/server           | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 41 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | Offline      | 87803.5      | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/offline          | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 42 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | SingleStream |     0.323576 | acc: 76.064           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/singlestream     | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 43 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | MultiStream  |     1.01767  | acc: 76.064           |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/multistream      | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 44 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | Offline      |     8.27882  | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/offline      | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 45 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | SingleStream |   431.284    | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X            |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/singlestream | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |