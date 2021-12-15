toddla23.github.io 라는 repository를 생성함
gem intall bundler jekyll을 실행하면 기본 블로그가 생성됨

jekyll lanyon으로 테마를 설정하려 했으나 테마가 깨지는 현상이 일어나 
https://zeddios.tistory.com/1223를 참고하여 테마를 설정함

post 생성후 댓글 작성 창에
 "We were unable to load Disqus. If you are a moderator please see our troubleshooting guide."
 라는 오류 메시지가 생성되는것을 확인함.
 광고 메시지나 과도한 동시작업과 관련된 오류로 판별됨.
 TRUSTED DOMAIN을 설정했으나 계속 오류 메시지가 생성 되어 처음부터 다시 disqus를 적용함.
 오류가 사라짐

Gemfile에 gem 'jekyll-admin', group: :jekyll_plugins 한 줄 추가 함으로써 
jekyll-admin 설정 가능 딱히 어려운건 없었음

https://favicon.io/favicon-generator/ 에서 파피콘 생성과 적용함
include의 head.html 파일 수정하면 금방 적용 됨. 이거도 설명대로 하면 되는거여서 딱히 어려운건 없었음
