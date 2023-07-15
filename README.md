<div align ="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&text=Commit%20Message%20Rules&fontSize=60&animation=fadeIn&fontAlignY=38&descAlignY=51&descAlign=62)

🦁림대 멋사 아기사자🦁들의 원활한 협업을 위한 commit 규칙을 정리해두었습니다🧐  </div>
</div> 

# 🧾 Formats for Commit Messages
<p>먼저 커밋 메시지는 크게 <strong>제목, 본문, 꼬리말</strong> 세 가지로 나뉘고, 각 파트는 <b>공백 줄로</b> 구분합니다.</p>

```
type(타입) : title(제목) //Subject

Body(본문, 생략 가능)

Footer(생략 가능)
```

## 🔖  Message Tag 
<p>타입은 태그와 제목으로 구성되고, 태그는 영어로 작성, 첫 문자는 대문자로 합니다.</p>
<p><strong>"태그: 제목"의 형태이며, : 뒤에 공백을 넣어주세요.</strong></p>

|태그 이름|태그 설명|
|:---:|:---:|
|Feat|새로운 기능 추가|
|Fix|버그 수정|
|!BREAKING CHANGE |커다란 API 변경의 경우|
|!HOTFIX|급한 치명적 버그 수정|
|Build|빌드 관련 파일 수정|
|Design|CSS를 포함 UI 디자인 변경|
|Docs|문서(문서 추가, 수정, 삭제)|
|Style|스타일(코드 형식, 세미콜론 추가: 비즈니스 로직에 변경 없는 경우)|
|Refactor|코드 리팩토링|
|Comment|필요한 주석 추가 및 변경|
|Test|테스트(테스트 코드 추가, 수정, 삭제: 비즈니스 로직에 변경 없는 경우)|
|Rename|파일, 폴더명 이름 수정|
|Remove|파일, 폴더 삭제|

## ▫️ Commit Message Subject 규칙
- 첫 글자는 대문자로 입력하고, 제목 줄을 마침표로 끝내지 않는다.
- 마지막에는 .(period)을 찍지 않으며 영문 기준 최대 50자를 넘지 않는다.
- 제목은 동사원형을 사용해 명령문의 형태로 작성한다.
- 본문과 주제를 공백 라인으로 구분한다.

#### Example of Subject 
```
Fix: 축제 관리자만 부스 목록에서 모든 데이터를 확인하도록 수정
```
## ▫️ Commit Message Body 규칙
- 선택 사항이므로 모든 커밋에 작성할 필요는 없다.
- 각 줄은 최대 72자를 넘지 않도록 한다.
- 어떻게 변경했는지보다, 무엇을 변경했고, 왜 변경했는지를 <b>자세히</b> 설명한다.
- 설명뿐만 아니라 커밋의 이유를 작성할 때도 작성합니다.

#### Example of Subject 
```
축제 관리자만 부스 목록에서 모든 데이터를 확인하도록 수정
  - BoothMapView.vue: 관리자 유형에 따른 부스 페이지에 대한 권한을 부여함. 
```

## ▫️ Commit Message Footer 규칙
- 선택사항이며, 관련된 이슈를 언급한다. 예) Fixes: #1, #2
- 주로 Closes(종료), Fixes(수정), Resolves(해결), Ref(참고), Related to(관련) 키워드를 사용한다.
- 이슈를 추적하기 위한 ID를 추가할 때 사용합니다.
  - 해결 : 해결한 이슈 ID
  - 관련 : 해당 커밋에 관련된 이슈 ID
  - 참고 : 참고할만한 이슈 ID

```
해결: #123
관련: #321
참고: #222
```
## ▫️ Exmample of Full Commmit Message
```
Fix: 축제 관리자만 부스 목록에서 모든 데이터를 확인하도록 수정(#123)

축제 관리자만 부스 목록에서 모든 데이터를 확인하도록 수정
  - BoothMapView.vue: 관리자 유형에 따른 부스 페이지에 대한 권한을 부여함. 

해결: #123
```

## ▫️ 림대 Builder들의 실제 프로젝트 커밋 메세지 예시
<img src="https://github.com/Hallym-LIKELION/.github/assets/53892427/f10943ec-2f49-4c40-825b-cf14c9a76bce" width=70% /> 

## ▫️ 부적절한 커밋 메세지 예시 
- 이렇게 쓰면 다른 개발자가 어떤 내용을 개발했는지 파악이 안됩니다...
  
![image](https://github.com/Hallym-LIKELION/.github/assets/53892427/0eb07517-72d0-44e3-a8b2-f0ce1847ad13)

## 🫢 Written by.
|[@osohyun0224](https://github.com/osohyun0224)|
| :--------------------------------------------:|
| <img width="100px" src="https://github.com/osohyun0224/Oh_my_Garden/assets/53892427/c46c109d-ddb5-4c3e-becf-f00fdd115c84" /> |
|                          11기 림대 멋사 운영진 & <br/> 프론트엔드 빌더 🫡                     | 

## 🙇🏻‍♀️ References
- [Github Commit Message Rules - Junhyunny's Devlogs
 ](https://junhyunny.github.io/information/github/git-commit-message-rule/#example-of-subject)
- [LikeLion-at-DGU : README](https://github.com/LikeLion-at-DGU/.github/blob/main/profile/README.md)
 
