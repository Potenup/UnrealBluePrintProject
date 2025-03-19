# Unreal
MTVS Final Project

**일정 : 2025.03.19 ~ 2025. 03.26**
---
**마일스톤으로 큰단위의 작업을 설정해 주세요**

**마일스톤 컨벤션**
- 챕터를 크게 나눠서 정리(ex. 큐브 돌리기, 화면 분할 등등)

**마일스톤 컨벤션 예시**
  
- Title : CubeActorRotation

<br/> 

**이슈 작성 후 작업 진행**

<br/> 

**이슈 예**

**[Feat] map 요청 api 작성**

### ISSUE

- Type: feat
- Detail: c++ 플레이어가 선택한 map에 대한 umap과 datatable을 요청한다.

### TODO

- [ ]  http req 셋팅
- [ ]  요청할 맵 식별 id 전달
- [ ]  rep 함수 선언

<br/> 

**작은 변경사항이라도 꼭 중간마다 커밋, 푸쉬**

<br/> 

**브렌치명 컨벤션**
- 브렌치 명 : <날짜>_<기능>

**브렌치명 컨벤션 예**

- 20250319_ProjectGreate

<br/> 

**커밋 컨벤션**

- <유형> : <내용> #이슈번호
- Feat : 새로운 기능을 추가할 경우
- Fix : 버그를 고친 경우
- !HOTFIX : 치명적인 버그를 고친 경우
- Style : Norm 규정, 세미콜론 누락, 코드수정이 없는 경우
- Refactor : 리팩토링
- Comment : 주석 추가 및 변경
- Docs : 문서를 수정한 경우
- Test : 테스트 추가
- Rename : 파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우
- Remove : 파일을 삭제하는 경우

**커밋 컨벤션 예**

- Feat: tokenizer 구현
- Fix: tokenizer 문자열 파싱 버그 수정
- Remove: test.txt 임시파일 삭제
- Rename: test.txt → operator.txt
