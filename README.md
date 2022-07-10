# MLops
# mlops 란? 
- 2021 년 부터 AI업계에서 많이 나온단어 MLOps , ML + Ops(operation)
- 머신러닝을 실제로 운영할때 생기는 일을 다루는 분야 연구가 아닌 서비스에 적용하는 과정에서 필요한 분야
- MLOPS = modelops + dataops + devops
- modelops : 모델 개발 관리(모델관리
- dataops : 데이터 관리(데이터 엔지니어링, 데이터관리)
- devops : 소프트웨어 개발과 관련 운영(배포,클라우드)


- 일반적인 ML pipeline
## ![image](https://user-images.githubusercontent.com/54635552/178142170-1a5fd7bf-3141-4151-93f9-235c6570175c.png)

- MLOPS 구조
## ![image](https://user-images.githubusercontent.com/54635552/178142205-e5cbc174-e82e-43a4-912f-644639cf3cdd.png)

- MLOPS 필요성
## ![image](https://user-images.githubusercontent.com/54635552/178142242-746d725a-70e9-424c-a69f-f749adb66d53.png)

- Research와 Production 관점의 ML
## ![image](https://user-images.githubusercontent.com/54635552/178142321-0284eb53-57b2-40a2-9317-c493d3e76f88.png)

## 예상되는 문제점
## ![image](https://user-images.githubusercontent.com/54635552/178141311-80735b90-ca1d-4648-8092-621a4c00e0de.png)

## MLops 필요한 이유
## ![image](https://user-images.githubusercontent.com/54635552/178141345-27fccabd-9787-4be0-8c8f-b7b0afbcf47d.png)

## MLOPS 분야
## ![image](https://user-images.githubusercontent.com/54635552/178142817-7109583f-3f09-4dc1-b5b5-dc71df6ef111.png)

## Data-centric OPS
## ![image](https://user-images.githubusercontent.com/54635552/178146719-68b7213a-63fe-48df-9443-c315392549fa.png)
- 실제 개발자들 사이에서 진행된 투표에서 모델 정확도 개선에서
- 코드개선(모델 변경, 파라미터 변경) vs 데이터 개선
- 데이터개선의 선택비율이 80%로 높았다
- AI Improve 는 즉 Improve the quality of the data 와 동일시된다
- 모델 개발과정중에 데이터 요구사항이 자꾸 변경될 경우, 계속 데이터의 변경에 비효율성이 발생함
- 가설을 세우고, 해당 가설을 데이터분석을 통해 하는 점에서 효율성이 필요함
- Active learning 방식을 통해 해결하고자함
- 데이터의 Consistency 문제가 중요함 -> 규모가 큰 빅데이터 관점에선 영향력이적지만 -> 실제 Task에서 비교적 작은 데이터셋에선 해당문제가 중요하게 열겨짐

## 출처
- https://www.youtube.com/watch?v=xZKtofBe18I&ab_channel=%EC%B9%B4%EC%9D%BC%EC%8A%A4%EC%BF%A8
- https://www.youtube.com/watch?v=I-sa8bOcOUk&list=PLIuC6QlQQF0Pf-aM0tioYTjrnLzaJaGez&index=1&ab_channel=MLOpsKR
- https://www.youtube.com/watch?v=eQzjJ5fTlKU&list=PLIuC6QlQQF0Pf-aM0tioYTjrnLzaJaGez&index=3&ab_channel=MLOpsKR
