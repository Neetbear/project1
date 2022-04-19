# project1
### html css javascirpt로 홈페이지 만들기

로그인, 회원가입 기능은 db를 배우기 전이라 로컬 스토리지를 사용하였다
``` 
  // 회원가입시 아이디 비밀번호 캐시를 이용하여 키 밸류 쌍으로 로컬스토리지에 저장
  localStorage.setItem(currentId, currentPassword);
  localStorage.setItem("loginstate", "");
  // 로그인 확인시 로그인 상태값을 okay로 변경해 로그인 상태를 유지시키려고 하였다
  localStorage.setItem("loginstate", "okay");
``` 
완성 후 확인 결과 보안상의 문제로 유저 정보는 로컬스토리지에 담으면 안된다는 것을 알았다
