---
title : "3. Install Requirements"
description: ""
lead: ""
draft: false
weight: 311
contributors: ["Jongseob Jeon"]
menu:
  docs:
    parent: "kubeflow"
---

실습을 위해 권장하는 파이선 버전은 python>=3.7입니다.

실습을 진행하기에서 필요한 패키지들과 버전은 다음과 같습니다.

- requirements.txt

  ```text
  kfp==1.8.9
  scikit-learn==1.0.1
  mlflow==1.21.0
  pandas==1.3.4
  dill==0.3.4
  ```

패키지 설치를 진행합니다.

```text
pip3 install -U pip
pip3 install kfp==1.8.9 scikit-learn==1.0.1 mlflow==1.21.0 pandas==1.3.4 dill==0.3.4
```