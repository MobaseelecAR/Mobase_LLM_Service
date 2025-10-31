<img src="images/Mobase_LLM_Service.png" alt="SVG 이미지 설명" width="1536" height="1024">


# 1.  계정 생성 및 로그인 방법

## 1. 지정된 IP로 접속

![image.png](images/image.png)

## 2. 계정이 없을 경우 가입 클릭

![image.png](images/image%201.png)

## 3. 계정 생성

![image.png](images/image%202.png)

## 4. 로그인

![image.png](images/image%203.png)

# 2.  사용 방법

## 1. 사용할 LLM 모델 설정

![image.png](images/0b7906c6-7143-44f6-91b3-03a3a389a4f0.png)

## 2. 파일 업로드 지원(추후 캡처, 웹페이지, 노트 첨부 기능 추가예정)

![image.png](images/image%204.png)

# 3. 구성기능

## 1. 일반 질의 응답
    
![image.png](images/image%205.png)
    

## 2. 코드 생성
    
![image.png](images/image%206.png)
    

## 3. 코드 검증
    
![image.png](images/image%207.png)
    

# 4.  구성모델

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