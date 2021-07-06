# Trainer-Tutorial

이미지 분류기 학습을 위한 Tutorial Repository 입니다.
Pytorch 프레임워크 기반으로 작성된 VGGNet 모델을 활용하여, 이미지 분류기를 학습합니다.

## 초기 구성

저장소의 Repository 에는 다음과 같이 `*` 표시된 경로/파일들이 빠져있습니다.
( 학습용 데이터 미 세팅시 모델이 동작하지 않습니다 )

### Skeleton

```
└── /Trainer-Tutorial
    │
    ├── /bin
    │   └── run_trainer.sh
    │
    ├── /datasets
*   │   ├── /train (train_dataset)      # 학습용 데이터
*   │   └── /evaluation (eval_dataset)  # 평가용 데이터
    │
    ├── .gitignore
    ├── basic_trainer.py  # Tutorial 1 의 학습기 코드
    ├── dataset.py
    ├── vgg_model.py    
    ├── trainer.py
    ├── LICENSE - Pytorch
    └── README.md
```

- /datasets - 이하에 학용 train 및 evaluation 경로 작성 및 학습 데이터 세팅
- /output 폴더 & class_index.json 파일은 Trainer 동작시 필요에 따라 자동 생성

## Dependency

```
개발 환경 :
python 3.6 이상
pytorch 1.2.0 이상 
torchvision 0.4.0 이상

을 권장합니다
```

## Run Trainer

```
python trainer.py
```

## LICENSE

```
Pytorch License (from pytorch)
```

## Reference

- [Pytorch](https://github.com/pytorch/pytorch)
- [Pytorch torchvision](https://github.com/pytorch/vision)
- [Pytorch Tutorial](https://github.com/yunjey/pytorch-tutorial)
- [딥러닝 모델 Trainer 개발을 위한 Tutorial-1 (with Pytorch)](https://blog.nerdfactory.ai/2020/10/08/Tutorial-1-for-Deep-Learning-Model-Trainer-Development.html)
- [딥러닝 모델 Trainer 개발을 위한 Tutorial-2 (with Pytorch)](https://blog.nerdfactory.ai/2020/11/04/Tutorial-2-for-Deep-Learning-Model-Trainer-Development.html)