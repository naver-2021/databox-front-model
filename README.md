## Naver Databox Model Dump for Frontend

### Introduction

- 두 가지 Neural Net 기반 Metric-Alteralbe 차원축소 모듈 포함
  - Housing (California Housing Dataset)
  - Shopping (Naver Databox 쇼핑 데이터)
- `naver-databox-model` 레포지토리에서 생성된 모델을 dump해 저장해놓은 레포지토리
- 이 레포지토리 상에서 웹 서버를 열고, frontend 단에서 이를 전달받아 구동

### Execution

```sh
python3 server.py 8080
```

- 이후 `http://localhost:8080/housing/umap/model.json` 와 `http://localhost:8080/shopping/model.json` 주소로 각각의 모델에 접근 가능 
- 자세한 설명은 `naver-databox-front` 레포지토리의 README 참조