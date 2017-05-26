회사 gitlab 생성 및 배포

https://gitlab.회사명.com/ 접속

로그인,

New Project >>
프로젝트 명 설정, private

사용자 추가 >>
프로젝트에 settings >> members >> New project member ( 회사명 깃랩에 계정 추가되있어야함[서버관리자님께 문의])

eclipse[sts] 에서 프로젝트 생성 >> 프로젝트 오른쪽 마우스 클릭 >> team >> 쉐어 >> gitlab에 프로젝트 등록하고 커밋&푸쉬 >> 깃랩 브라우져에서 확인

eclipse[sts] 에서 프로젝트 받기 >> 깃랩 브라우져에서 HTTPS 주소 복사 >> eclipse[sts] >> open perspective[git이 없으면 플러그인 설치] >> git >> 복사한 url 클론 >> spring 패키지 익스플로러로 돌아가 >> 오른쪽마우스 클릭 >> import >> git >> projects from git >> existing local repository >>  working tree/kbs 선택 후 넥스트 >> finish

2017-05-26 devleesk
