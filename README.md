# [GMS는 광명경영회계고등학교 학생관리 시스템입니다.]

2018-08-01
 - Classtime 폼의 소스코드 삭제 & 달력기능 추가
   
 - 데이터베이스 관련 작업들 모듈화
   - 데이터베이스 연결/연결해제/데이터값 읽기/수정/추가/삭제 기능 함수화 
   
 - 속도향상을 위한 불필요한 소스코드 삭제
   - SpreadDesigner를 이용해서 Spread 불필요한 소스코드는 삭제
   
 - 메인화면에 불필요한 버튼 제거
   - FpSpread 7.0 기능을 이용해서 Spread로 메뉴선택 기능 추가
 
 - 데이터베이스 외부접속 허용
   - PORT번호 8080
 
 - 학과 추가 및 학과코드 변경(관광경영과 & 콘텐츠디자인과)
 
 2018-08-02
 - 성적 등록/관리에 필요한 테이블 재설계
   - TABLE_RECORD와 각종 코드를 관리해주는 TABLE_CODE 테이블 설계 & 생성
 
 - 학생 정보를 등록/관리 메뉴가 새롭게 추가되었습니다.
   - 학생 정보관리 폼 생성 & 메인메뉴에 추가
   - TABLE_STUDENT_INFO 메뉴 추가
 
 - 성적 등록/관리 화면 컨트롤 재배치
