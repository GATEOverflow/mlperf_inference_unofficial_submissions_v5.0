Please download [summary.xlsx](summary.xlsx) to view the most recent results. [This page](https://docs.google.com/spreadsheets/d/e/2PACX-1vSCu8F7Hwck-AGJ5kWxi2G3xhO5MJoc_igybvsxjCt-2fEEYyf2BIcR0rTXW0eUzg/pubhtml) shows the results which may not be the latest. 
 ```
[2024-12-10 14:05:05,767 submission_checker.py:3204 INFO] Results=48, NoResults=0, Power Results=0
[2024-12-10 14:05:05,767 submission_checker.py:3211 INFO] ---
[2024-12-10 14:05:05,767 submission_checker.py:3212 INFO] Closed Results=19, Closed Power Results=0

[2024-12-10 14:05:05,767 submission_checker.py:3217 INFO] Open Results=29, Open Power Results=0

[2024-12-10 14:05:05,767 submission_checker.py:3222 INFO] Network Results=0, Network Power Results=0

[2024-12-10 14:05:05,767 submission_checker.py:3227 INFO] ---
[2024-12-10 14:05:05,767 submission_checker.py:3229 INFO] Systems=4, Power Systems=0
[2024-12-10 14:05:05,767 submission_checker.py:3233 INFO] Closed Systems=3, Closed Power Systems=0
[2024-12-10 14:05:05,767 submission_checker.py:3238 INFO] Open Systems=2, Open Power Systems=0
[2024-12-10 14:05:05,767 submission_checker.py:3243 INFO] Network Systems=0, Network Power Systems=0
[2024-12-10 14:05:05,767 submission_checker.py:3248 INFO] ---
[2024-12-10 14:05:05,767 submission_checker.py:3253 INFO] SUMMARY: submission looks OK
INFO:root:       ! call "postprocess" from /home/runner/CM/repos/mlcommons@mlperf-automations/script/run-mlperf-inference-submission-checker/customize.py

```

|    | Organization   | Availability   | Division   | SystemType      | SystemName    | Platform                                                       | Model        | MlperfModel   | Scenario     |       Result | Accuracy              |   number_of_nodes | host_processor_model_name           |   host_processors_per_node |   host_processor_core_count | accelerator_model_name   |   accelerators_per_node | Location                                                                                                          | framework   | operating_system                                | notes                             |   compliance |   errors | version   |   inferred | has_power   | Units        | weight_data_types   |
|---:|:---------------|:---------------|:-----------|:----------------|:--------------|:---------------------------------------------------------------|:-------------|:--------------|:-------------|-------------:|:----------------------|------------------:|:------------------------------------|---------------------------:|----------------------------:|:-------------------------|------------------------:|:------------------------------------------------------------------------------------------------------------------|:------------|:------------------------------------------------|:----------------------------------|-------------:|---------:|:----------|-----------:|:------------|:-------------|:--------------------|
|  0 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9    | bert-99.9     | Server       |  1414.97     | F1: 90.89127264236201 |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/server            | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Queries/s    | fp16                |
|  1 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9    | bert-99.9     | Offline      |  1674.57     | F1: 90.89170281131781 |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/offline           | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Samples/s    | fp16                |
|  2 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Server       |  3841.1      | F1: 90.25897829249658 |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/server              | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
|  3 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Offline      |  4135.1      | F1: 90.15673510616978 |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/offline             | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
|  4 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | SingleStream |     1.00372  | F1: 90.26682135974633 |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/singlestream        | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
|  5 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | Server       | 35357.8      | acc: 76.078           |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/server             | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
|  6 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | Offline      | 44332.9      | acc: 76.078           |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/offline            | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
|  7 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | SingleStream |     0.286566 | acc: 76.064           |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/singlestream       | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
|  8 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | MultiStream  |     0.469376 | acc: 76.064           |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/multistream        | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
|  9 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet    | retinanet     | Server       |   637.175    | mAP: 37.349           |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/server            | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 10 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet    | retinanet     | Offline      |   869.281    | mAP: 37.341           |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/offline           | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 11 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet    | retinanet     | SingleStream |     1.69932  | mAP: 37.327           |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/singlestream      | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 12 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet    | retinanet     | MultiStream  |    11.5542   | mAP: 37.347           |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/multistream       | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 13 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | Offline      |     4.16918  | DICE: 0.86236         |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/offline        | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 14 | MLCommons      | available      | open       | datacenter,edge | RTX4090x1     | RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | SingleStream |   432.185    | DICE: 0.86236         |                 1 | AMD Ryzen 9 7950X 16-Core Processor |                          1 |                          16 | NVIDIA GeForce RTX 4090  |                       1 | open/MLCommons/results/RTX4090x1-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/singlestream   | TensorRT    | Ubuntu 20.04 (linux-6.8.0-49-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 15 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9    | bert-99.9     | Offline      |  3247.32     | F1: 90.8832407068292  |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/offline           | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Samples/s    | fp16                |
| 16 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Server       |  6061.51     | F1: 90.25897829249658 |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/server              | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 17 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Offline      |  8237.37     | F1: 90.15673510616978 |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/offline             | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 18 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | SingleStream |     1.06323  | F1: 90.26682135974633 |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/singlestream        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 19 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | Server       | 73744        | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/server             | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 20 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | Offline      | 87916        | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/offline            | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 21 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | SingleStream |     0.598655 | acc: 76.064           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/singlestream       | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 22 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | MultiStream  |     1.03774  | acc: 76.064           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/multistream        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 23 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet    | retinanet     | Server       |  1414.99     | mAP: 37.326           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/server            | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 24 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet    | retinanet     | Offline      |  1730.51     | mAP: 37.321           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/offline           | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 25 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet    | retinanet     | SingleStream |     2.33544  | mAP: 37.336           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/singlestream      | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 26 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | retinanet    | retinanet     | MultiStream  |     6.22742  | mAP: 37.311           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/retinanet/multistream       | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 27 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | Offline      |     8.16675  | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/offline        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 28 | MLCommons      | available      | open       | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | SingleStream |   431.038    | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | open/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/singlestream   | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 29 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia-gpu-TensorRT-default_config                   | 3d-unet-99.9 | 3d-unet-99.9  | Offline      |     8.29596  | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/3d-unet-99.9/offline                        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 30 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia-gpu-TensorRT-default_config                   | 3d-unet-99.9 | 3d-unet-99.9  | SingleStream |   431.158    | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia-gpu-TensorRT-default_config/3d-unet-99.9/singlestream                   | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 31 | MLCommons      | available      | closed     | datacenter,edge | gh_ubuntu_x86 | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config               | resnet50     | resnet        | Server       | 73015.2      | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/server                         | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 32 | MLCommons      | available      | closed     | datacenter,edge | gh_ubuntu_x86 | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config               | resnet50     | resnet        | Offline      | 87471.2      | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/offline                        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 33 | MLCommons      | available      | closed     | datacenter,edge | gh_ubuntu_x86 | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config               | resnet50     | resnet        | SingleStream |     0.342055 | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/singlestream                   | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 34 | MLCommons      | available      | closed     | datacenter,edge | gh_ubuntu_x86 | gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config               | resnet50     | resnet        | MultiStream  |     0.951987 | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/gh_ubuntu_x86-nvidia-gpu-TensorRT-default_config/resnet50/multistream                    | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | Automated by MLCommons CM v3.2.6. |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 35 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9    | bert-99.9     | Server       |     0.888629 | F1: 90.89074704580993 |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/server          | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 36 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99.9    | bert-99.9     | Offline      |  3314.54     | F1: 90.8832407068292  |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99.9/offline         | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 37 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Server       |  6061.5      | F1: 90.25897829249658 |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/server            | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 38 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | Offline      |  8219.33     | F1: 90.15673510616978 |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/offline           | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 39 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | bert-99      | bert-99       | SingleStream |     1.03994  | F1: 90.26682135974633 |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/bert-99/singlestream      | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 40 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99   | 3d-unet-99    | Offline      |     8.27882  | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99/offline        | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 41 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99   | 3d-unet-99    | SingleStream |   431.284    | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99/singlestream   | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 42 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | Server       | 73743.9      | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/server           | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Queries/s    | int8                |
| 43 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | Offline      | 87803.5      | acc: 76.078           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/offline          | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 44 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | SingleStream |     0.323576 | acc: 76.064           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/singlestream     | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 45 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | resnet50     | resnet        | MultiStream  |     1.01767  | acc: 76.064           |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/resnet50/multistream      | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |
| 46 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | Offline      |     8.27882  | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/offline      | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Samples/s    | int8                |
| 47 | MLCommons      | available      | closed     | datacenter,edge | RTX4090x2     | RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config | 3d-unet-99.9 | 3d-unet-99.9  | SingleStream |   431.284    | DICE: 0.86236         |                 1 | Intel(R) Xeon(R) w7-2495X           |                          1 |                          24 | NVIDIA GeForce RTX 4090  |                       2 | closed/MLCommons/results/RTX4090x2-nvidia_original-gpu-tensorrt-vdefault-default_config/3d-unet-99.9/singlestream | TensorRT    | Ubuntu 20.04 (linux-6.2.0-39-generic-glibc2.31) | nan                               |            1 |        0 | v4.1      |          0 | False       | Latency (ms) | int8                |