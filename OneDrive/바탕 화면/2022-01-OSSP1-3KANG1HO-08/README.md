# 2022-01-OSSP1-3KANG1HO-08

> Today I Learned 태그 분석을 통한 개발 공부자료 추천 웹 

<br />

## 💭 About

> 자신이 매일 공부한 내용을 태그와 함께 업로드를 하면 분석을 하여 내일에 하면 좋을 공부를 추천해주는 웹  
> 양질의 컨텐츠를 제공하여 질좋은 TIL 공부를 할 수 있도록 격려


<br />

## ✨ Main Feat

- **`회원가입 & 로그인`**
<img src="https://user-images.githubusercontent.com/59119468/167071531-8c951a4e-6015-4f9d-b7e3-86fb953ba074.png" width="800" height="400"/>
<img src="https://user-images.githubusercontent.com/59119468/167071538-5d723bae-e853-473d-b695-c443da81332c.png" width="800" height="400"/>

- **`글 업로드 & 좋아요`**   
<img src="https://user-images.githubusercontent.com/59119468/167635548-0e5a2669-c15f-4e38-88cd-16f0e1c855d0.png" width="800" height="400"/>
<img src="https://user-images.githubusercontent.com/59119468/167635543-75d69e38-3ded-40fd-b205-99535909f907.png" width="800" height="400"/>

- **`공부자료 추천`**  
<img src="https://user-images.githubusercontent.com/59119468/167635537-36bfee73-649b-4ec1-8424-f2119ea2f49b.png" width="800" height="400"/>


<br /> 

## Team Member 

| -- | -- | -- | -- |
|:--:|:--:|:--:|:--:|
|**강지영**|**박광렬**|**정원호**|**최강희**|
|**FE**|**BE**|**FE**|**BE**|
|[@zzi](https://github.com/99-zziy)|[@pgrgrgrgr](https://github.com/pgrgrgrgr)|[@wonho](https://github.com/wonho1401)|[@rkdgml3577](https://github.com/rkdgml3577)|



<br />

## 📚 Tech Stack
- **React**
- **Redux**
- **styled-components**
- **Express**
- **Neo4j**
- **MongoDB**


<br />


## 📍 Commit Convention
|**Type**|설명|
|:--:|:--:|
|**Docs** |  문서 작성 및 수정 작업(README 등)  |
|**Add**  |  기능이 아닌 것 생성 및 추가 작업(파일·익스텐션·프로토콜 등)  |
|**Feat**  | 새로운 기능 추가 작업  |
|**Style** |  UI 관련 작업(UI 컴포넌트, Xib 파일, 컬러·폰트 작업 등)  |
|**Fix** |  에러 및 버그 수정, 기능에 대한 수정 작업  |
|**Edit** |  Fix가 아닌 모든 수정 작업(주석, 파일 및 폴더 위치, 코드 스타일 등)  |
|**Del**   | 파일, 에셋 등 삭제 작업  |
|**Set**   | 세팅 관련 작업  |
|**Test**  |  테스트 관련 작업  |

<br />

## 🐾 Branch Strategy

<details markdown="1">
<summary>브랜치 종류 소개</summary>

`develop` - default 
- protected → 승인 받아야만 merge 가능

`feature`
- feature/#이슈번호
- feature/#1

</details>

<details markdown="1">
<summary>시나리오</summary>

> 1️⃣ **Issue**
> 1. 이슈생성

> 2️⃣ **Branch**
> - ex. feature/#16

> 3️⃣ **Pull request**
> 1. reviewer → 4명
> 2. 4명 중 2명이 승인(approve)을 해야 merge 가능

> 4️⃣ **Code Review**
> 1. 수정 요청
> 2. 대상자(작업자)가 수정을 하고 다시 커밋을 날림
> 3. 수정 반영하고 답글로 커밋로그 남기기
>    - 수정사항은 커밋번호로 남기기

> 5️⃣ **merge**
> 1. 팀원 호출
> 2. 간단한 리뷰, 피드백, 회의 마친 후
> 3. 다 같이 보는 자리에서 합칠 수 있도록 하기

</details>
<br />

## 🗂 Folder Architecture
### - FE
 **|-- comonents  => 공통 컴포넌트 관리 <br />
   |-- store => 리덕스 관련 모듈들 <br />
   |-- hooks => 공통 hooks 관리 <br />
   |-- pages  => router 페이지 관리 <br />
   |-- utils => util 파일 관리 <br />
   |-- api => api 목록들  <br />
   |-- constants => 상수(매직넘버)  <br />
   |-- assets => 프로젝트에 쓸 font, image 등 <br />**

