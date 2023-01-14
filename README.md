<div data-target="readme-toc.content" class="Box-body px-5 pb-5">
            <article class="markdown-body entry-content container-lg" itemprop="text"><p dir="auto"><br><br></p>
<p align="center" dir="auto">
<img width="1000" alt="zero9Main" src="https://user-images.githubusercontent.com/72180863/212448323-1bfbf4eb-ed3a-42c7-93cf-a2ee12a093a5.png">

<p align="center" dir="auto">
“ 크리에이터들의 공구 정보,마케팅,판매제공 사이트 “<br><br> <strong>Zero9</strong>
</p>
<br>
<h2 dir="auto"><a id="user-content---여러 크리에이터들의 공구상품을 한눈에 보고 싶다면? 나를 마케팅 하고 싶다면?" class="anchor" aria-hidden="true" href="#--여러 크리에이터들의 공구상품을 한눈에 보고 싶다면? 나를 마케팅 하고 싶다면?"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a> <g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji> 여러 크리에이터들의 공구상품을 한눈에 보고 싶다면? 나를 마케팅 하고 싶다면?</h2>
              
              
<p dir="auto">Z9는 광고보다 인플루언서의 경험을 더 신뢰하는 현대인을 위한 공동구매 플랫폼으로, 공동구매의 0부터 9까지 모두 다루겠다는 의미를 이름에 담았다.<br/>
  2022년 현재 인플루언서가 공동구매(이하 공구)를 개최할 때 제품사 쇼핑몰 혹은 N사의 스토어를 이용한다.<br/>전용 플랫폼이 아니기에 공구가 언제 열릴지, 얼마나 팔리는지,  현황을 알 수 없다.
  Z9는 단순 URL 공유를 넘어 인플루언서의 개성을 그대로 이어가는 데 목표를 뒀다. 공구 예약 시스템, 다양한 상세페이지, 실시간 판매량 표기 등 여러 기능을 도입한다.
  <br/>소비자는 더 나은 공동구매 방식을 경험하고, 인플루언서는 깔끔한 공구 진행으로 프로페셔널한 이미지를 얻을 수 있다.</p>
<br/>
                        
<h2 dir="auto"><a id="user-content--프론트엔드-기술" class="anchor" aria-hidden="true" href="#-프론트엔드-기술"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji>프론트엔드 기술</h2>

              
### 📟 신미연
- **디자인** : Photoshop, figma를 이용한 사이트 디자인
- **CSS & styled-component** : animation, state props를 이용한 UI 에니메이션 구현
- **타이머** : Date를 받아 공통컴포넌트 제작, 실시간 시간, 마감날짜, 시작예정 남은 시간 계산 로직 구현
- **메인페이지** :
  - CSS animation 구현, 원페이지 구현
  - SessionStorage에 로그인 Token정보를 저장하고 refresh Token를 서버측과 통신하여 로그인 유지 기능 구현.
              
- **상세페이지** :
  - 크리에이터가 상세페이지 템플릿을 고르고 등록하면 나오는 3개의 페이지 디자인, 기능 구현
  - Url 복사
  - 구매 갯수만큼 남은 갯수 게이지 styled-component 구현
  - 상세이미지 클릭시 대표이미지로 바뀌는 기능 구현
  - 상품 금액 로직 구현
              
- **Q&A** :
  - 질의응답 CRUD 구현
  - 마이페이지에서 유저,크리에이터가 질문&답변을 확인할 수 있게 공통컴포넌트로 제작

- **리스트페이지** :
  - 시작전, 남은시간, 마감시간 의 타이머 실시간 정보 제공
  - 더보기 클릭시 데이터가 4개씩 추가되는 기능 구현
  - 전제, 진행예정, 진행중, 종료 tab 기능 구현
  - 조회수, 찜 갯수 기능 구현

<br/>
<br/>

### 📟 이상현
- **배포** : GCP, Docker를 활용하여 프론트엔드 서버 배포.
- **PWA** : Next-pwa를 적용해 PWA 적용.
- **회원가입/로그인** :
  - Yup을 활용하여 아이디, 비밀번호확인 검증 기능 구현.
  - SessionStorage에 로그인 Token정보를 저장하고 refresh Token를 서버측과 통신하여 로그인 유지 기능 구현.
              
- **마이페이지** :
  - 마이페이지 전용 레이아웃을 별도 컴포넌트로 구성.
  - 아임포트를 이용해 포인트 충전 결제 구현.
              
- **상품등록페이지** :
  - fileReader를 사용해 업로드 전 이미지 미리보기 구현.
  - 셀렉트박스 값에 따라 State를 조절해 옵션 수 조절.
              
<br/><br/>
              
<h2 dir="auto"><a id="user-content--팀원-소개" class="anchor" aria-hidden="true" href="#-팀원-소개"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji> 팀원 소개</h2>                                 



<p dir="auto"><img width="1000px" alt="team 이미지" src="https://user-images.githubusercontent.com/72180863/212448586-dbc8f587-47f0-42aa-a1e2-e1f00347d244.png"/></p>
<br/>
<br/>
              
<table>
<thead>
<tr>
<th>이름</th>
<th>역할</th>
<th>작업 부분</th>
</tr>
</thead>
<tbody>
<tr>
<td>신미연</td>
<td>FE</td>
<td>사이트 디자인,메인페이지, 상세페이지1,2,3, Q&A, 리스트페이지, FE GIt 관리자, 노션 관리자, 상품 타이머</td>
</tr>
<tr>
<td>이상현</td>
<td>FE</td>
<td>CRUD's, 마이페이지 디자인&Func, 충전,인출, 로그인&로그아웃, PWA, FE 팀장, 발표자료준비</td>
</tr>

<tr>
<td>황교진</td>
<td>BE,팀장</td>
<td>Product API, Q&A API, Migrate OPEN API's, (Business & Bank),<br/>Dev & Production Deploy, Project Management</td>
</tr>
<tr>
<td>홍민우</td>
<td>BE</td>
<td>File Upload(Image)API, Point API, Purchase API, Category API,<br/>Optional Search API, Product Like API, CI/CD, FE & BE QC, FE & BE Git Management</td>
</tr>
<tr>
<td>박진화</td>
<td>BE</td>
<td>Signup API, Login/Logout API, Auth API, Payment API, Custom Search Engine, Demonstration</td>
</tr>

</tbody>
</table>
              
<br/><br/>

<h2 dir="auto"><a id="user-content--Git-flow" class="anchor" aria-hidden="true" href="#-Git-flow"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg></a><g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji>Git-flow</h2>              

              
### Branch 이름 형식

1. master - production 환경으로 배포되는 메인 브랜치
    1. 버전 넘버로 tagging
2. develop - dev 환경으로 테스팅이 가능하며 개발을 이어나가는 브랜치
3. feature - 기능 개발 시 작업하는 브랜치 (develop에서 분기하여 develop으로 merge)
    1. feature 브랜치 명명 규칙
        1. feature-카테고리명
        2. feature-카테고리명 브랜치에는 각각의 이슈를 Resolve 하여 merge 하여 진행
4. release - develop 브랜치에서 개발이 완료된 릴리즈 버전을 production으로 전환하기 위한 브랜치 (develop에서 분기하여  최종적으로 master와 develop으로 merge)
    1. release 브랜치 명명 규칙
        1. release-버전 번호
        2. 신규 릴리즈의 버전 번호는 항상 master의 최신 태그보다 높은 숫자여야 하며, master에 merge 하는 경우 release의 버전 번호를 master의 tag로 사용
5. hotfix - production 환경의 급한 수정사항을 위한 브랜치 (master에서 분기하여 develop과 master로 merge)
    1. hotfix 브랜치 명명 규칙
        1. hotfix-이슈번호
        2. hotfix를 master로 merge 하는 경우에는 최신 버전의 태그를 그대로 사용
6. 이슈와 관련된 브랜치 - 이슈 단위로 이루어진 실제 작업이 이루어 지는 경우 생성되는 브랜치
    1. 이슈 브랜치 명명 규칙
        1. issue-이슈번호-이슈명
<br/>
<br/>

### Pull Request 형식 - Following Commit Message Rule

Commit Message Example

```
타입(Type): 제목(Subject)(#이슈번호)

본문(Body)

꼬리말(Footer)
```

## 타입 정의

- FEATURE: 새로운 기능 추가
- FIX: 버그 수정
- BUILD: 빌드 관련 파일 수정 (Dockerfile 등)
- CI: Release Automation 관련 파일 수정
- DOCS: 문서 추가, 수정, 삭제
- STYLE: 코드 형식, 세미콜론 등의 단순 변경 (비즈니스 로직 변경 사항이 없는 경우)
- REF: 코드 리팩토링
- TEST: 테스트 코드 추가, 수정, 삭제 등

## 제목 작성 방식

- 최대한 50자를 넘지 않는 선에서 작성 (한/영 혼용 가능)
- 필수적으로 커밋 타입을 명시 (위의 커밋 메시지 예시 참고)
- 제목과 본문이 모두 있는 경우 한 줄을 띄워 분리
- 이슈와 관련된 경우 제목 마지막 소괄호 안에 이슈번호 명시

ex)

```
FEATURE: 상품 등록 API 추가(#1234)
```

## 꼬리말 작성

- 모든 커밋에 꼬리말이 있을 필요 없음
- resolved 또는 closed: 이슈 해결시 사용
- refferal: 해당 커밋에 관련된 이슈 번호(이슈와 관련 있는 커밋이지만 해결은 되지 않은 상태에 주로 사용)
- include: 이미 해결된 이슈를 참조하는 경우

## 커밋 메시지 작성 예시

```
# Scenario 1 
# 이슈번호 159와 관련되어 버그가 발생하는 상품 상태 조회 API의 코드가 수정되어 반영된 경우

FIX: 상품 상태 조회 API 버그 수정(#159)

상품 상태 조회시 파라미터가 하나라도 null로 주어지면 발생하는 오류 수정
상품 상태 조회시 필수 파라미터가 주어지지 않는 경우 Error 메시지와 422 코드를 리턴하도록 수정

resolved #159
```

```
# Scenario 2
# 코드 들여쓰기와 줄바꿈을 수정하여 코드 스타일이 수정된 경우

STYLE: 상품 조회 관련 코드 스타일 수정
```

```
# Scenario 3
# 이슈번호 999와 관련되어 상품 리스트 조회 API를 새롭게 추가한 경우

FEATURE: 상품 리스트 조회 API 추가(#999)

시작날짜와 종료날짜를 전달받아 기간 내에 업로드된 상품 리스트를 조회하는 API 추가
파마리터가 없는 경우 전체 리스트를 조회

closed #999
```
<h2 dir="auto"><a id="user-content--기술-스택" class="anchor" aria-hidden="true" href="#-기술-스택"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.775 3.275a.75.75 0 001.06 1.06l1.25-1.25a2 2 0 112.83 2.83l-2.5 2.5a2 2 0 01-2.83 0 .75.75 0 00-1.06 1.06 3.5 3.5 0 004.95 0l2.5-2.5a3.5 3.5 0 00-4.95-4.95l-1.25 1.25zm-4.69 9.64a2 2 0 010-2.83l2.5-2.5a2 2 0 012.83 0 .75.75 0 001.06-1.06 3.5 3.5 0 00-4.95 0l-2.5 2.5a3.5 3.5 0 004.95 4.95l1.25-1.25a.75.75 0 00-1.06-1.06l-1.25 1.25a2 2 0 01-2.83 0z"></path></svg>
  </a><g-emoji class="g-emoji" alias="white_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2705.png">✅</g-emoji> 기술 스택</h2>
<p dir="auto"><a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/92153061/194533662-98a3d9a0-577c-4c1e-9c2a-14ef35744a30.png"><img src="https://user-images.githubusercontent.com/72180863/212448976-a646b418-424a-4232-b8b3-0ed2ce1e90f3.png" alt="skill" style="max-width: 100%;"></a></p><div/>

              
              
