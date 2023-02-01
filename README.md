# 뉴스 디지털화

## 💻 프로젝트 소개

자연어 처리 기술을 적용해 신문 원문 PDF 파일로부터 온라인 뉴스 서비스가 가능하도록 뉴스 디지털화를 구현하는 것이 프로젝트의 목적입니다. 

<br />


## 🎮 개발 기간

22.03.02 ~ 22.03.29

<br />

## 🛠 사용 툴
- Colab Pro
- Visual Studio Code
- Python3.8
  - kobert
  - transformers
  - pytorch
  - gluonnlp
  - mxnet

<br />

  
## 🔎 주요 기능


1. 뉴스 카테고리 분류

```python
testModel(model, '기사 내용')
```

testModel 함수에 기사 내용의 일부를 작성해주면 해당 뉴스의 카테고리와 신뢰도를 얻을 수 있습니다.

2. 띄어쓰기 검사

```python
testModel(config)
```

미리 저장해놓은 test data를 띄어쓰기 해볼 수 있습니다. test data를 바꾸고 싶다면, testModel의 인자인 config에서 `test_data_path`를 수정해주면 됩니다. 



3. 뉴스 단락 연결 여부 검사
