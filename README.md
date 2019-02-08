# 코드랩 진행하고 코드 다 같다붙임

web-start 폴더에 있는거만 쓰면됨  

명령프롬프트 창 :  
npm -g install firebase-tools  
firebase --version ( 4.x 이상 확인)  
firebase login (web에서 로그인하게됨, 구글 아이디 패스워드)  
firebase use --add (파일들 있는 로컬경로 들어가서, 예 : web-start, 생성한 파베 프로젝트 선택)  
firebase serve --only hosting (파일들 있는 로컬경로 들어가서, 예 : web-start)  
  
firebase deploy --except functions (배포)  

# Firebase Codelab: FriendlyChat

This is the source code for the Firebase FriendlyChat codelab. It includes start and end versions of the
code for Web and Cloud Functions. To get started open the codelab instructions:

 - [Firebase Web Codelab](https://codelabs.developers.google.com/codelabs/firebase-web/).
 - [Firebase SDK for Cloud Functions Codelab](https://codelabs.developers.google.com/codelabs/firebase-cloud-functions/).


## How to make contributions?
Please read and follow the steps in the [CONTRIBUTING.md](CONTRIBUTING.md)


## License
See [LICENSE](LICENSE)
