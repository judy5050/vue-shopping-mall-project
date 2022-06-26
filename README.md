# vue-shopping-mall-project

### 인프런의 실습 UI 개발로 배워보는 순수 javascript 와 Vue JS 개발강의를 듣으며 진행하는 프로젝트입니다.

#### 요구사항 분석 

- 검색폼 구현 
    - [x] 검색 상품명 입력 폼이 위치한다. 검색어가 없는 경우이므로 x 버튼을 숨긴다.
    - [x] 검색어를 입력하면 x 버튼이 보인다.
    - [x] 엔터를 입력하면 검색 결과가 보인다. (컨트롤러에게 위임)
    - [x] x 버튼을 클릭하거나, 검색어를 삭제하면 검색 결과를 삭제한다. 
    
- 검색 결과 구현
    - [] 검색 결과가 검색폼 아래 위치한다.
    - [] 검색 결과가 보인다.
    - [] x 버튼을 클릭하면 검색폼이 초기화 되고, 검색 결과가 사라진다.
    
- 탭 구현
    - [] 추천 검색어, 최근 검색어  탭이 검색폼 아래 위치한다.
    - [] 기본으로 추천 검색어 탭을 선택한다.
    - [] 각 탭을 클릭하면 탭 아래 내용이 변경된다.
    
- 추천 검색어 구현
    - [] 번호, 추천 검색어 목록이 탭 아래 위치한다.
    - [] 목록에서 검색어를 클릭하면 선택된 검색어로 검색 결과 화면으로 이동
    - [] 검색폼에 선택된 추천 검색어 설정
    
- 최근 검색어 구현 
    - [] 최근 검색어, 목록이 탭 아래 위치한다.
    - [] 목록에서 검색어를 클릭하면 선택된 검색어로 검색 결과 화면으로 이동
    - [] 검색일자, 버튼 목록이 탭 아래 위치한다.
    - [] 목록에서 x 버튼을 클릭하면 선택된 검색어가 목록에서 삭제 
    - [] 검색시마다 최근 검색어 목록에 추가된다. 