<p align="center">
  <img src="images/Mobase_LLM_Service.png" alt="Mobase LLM Service" width="1536" height="1024">
</p>

---

# 📋 목차

- ### [🚀 1. 계정 생성 및 사용법](#-계정-생성-및-사용법)
- ### [🎯 2. 주요 기능](#-주요-기능)
- ### [⚙️ 3. 구성 모델](#️-구성-모델)

---

<br>

## 🚀 1. 계정 생성 및 사용법

<details>
<summary><b>📝 단계별 가이드 보기</b></summary>

<br>

### 1단계: 지정된 IP로 접속

<img src="images/image.png" alt="접속 화면" width="600">

<br>

### 2단계: 계정이 없을 경우 가입 클릭

<img src="images/image 1.png" alt="가입 버튼" width="600">

<br>

### 3단계: 계정 생성

<img src="images/image 2.png" alt="계정 생성" width="600">

<br>

### 4단계: 로그인

<img src="images/image 3.png" alt="로그인" width="600">

</details>





<details>
<summary><b>⚙️ 설정 및 파일 업로드 가이드 보기</b></summary>

<br>

### 1. 사용할 LLM 모델 설정

서비스에서 제공하는 다양한 LLM 모델 중 원하는 모델을 선택하세요.

<img src="images/0b7906c6-7143-44f6-91b3-03a3a389a4f0.png" alt="모델 설정" width="600">

<br>

### 2. 파일 업로드 지원

> 💡 **추후 추가 예정 기능**
> - 📸 캡처 첨부
> - 🌐 웹페이지 첨부
> - 📄 노트 첨부

<img src="images/image 4.png" alt="파일 업로드" width="600">

</details>

<br>

## 🎯 2. 주요 기능

### 1. 일반 질의응답

<details>
<summary><b>자세히 보기</b></summary>

<br>

다양한 주제에 대해 자연스러운 대화를 통해 정보를 얻을 수 있습니다.

<img src="images/image 5.png" alt="일반 질의응답" width="700">

</details>

### 2. 코드 생성

<details>
<summary><b>자세히 보기</b></summary>

<br>

요구사항을 입력하면 자동으로 코드를 생성해줍니다.

<img src="images/image 6.png" alt="코드 생성" width="700">

</details>

### 3. 코드 검증

<details>
<summary><b>자세히 보기</b></summary>

<br>

작성한 코드를 분석하고 개선 방안을 제시합니다.

<img src="images/image 7.png" alt="코드 검증" width="700">

</details>

<br>

## 📊 3. 구성 모델

| Model | 질의응답 (Kor) | 질의응답 (Eng) | 코드 생성 | 코드 리뷰 | 이미지 생성 | 이미지 리뷰 |
|:---|:---:|:---:|:---:|:---:|:---:|:---:|
| **MS 모델** | ✅ | ✅ | ✅ | ✅ | ➖ | ➖ |
| **IBM 모델** | ⚠️ | ✅ | ✅ | ✅ | ➖ | ➖ |
| **GPT 모델** | ✅ | ✅ | ✅ | ✅ | ➖ | ➖ |
| **Alibaba 모델** | ✅ | ✅ | ✅ | ✅ | ➖ | ➖ |
| **Le Chat 모델** | ❌ | ✅ | ✅ | ✅ | ➖ | ➖ |
| **Deepseek 모델** | ⚠️ | ✅ | ✅ | ✅ | ➖ | ➖ |
| **Gemini 모델** | ✅ | ✅ | ✅ | ✅ | ➖ | ➖ |

### 범례
- ✅ 완전 지원
- ⚠️ 부분 지원 (제한적)
- ❌ 미지원
- ➖ 해당 없음

### 주의사항
- **IBM 모델**: 간혹 영어로 생성되는 경우 있음
- **Le Chat 모델**: 한국어가 제대로 생성되지 않는 경우가 많음
- **Deepseek 모델**: 간혹 한문, 영어로 생성됨