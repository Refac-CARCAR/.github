🐌

##





## VM 주소
`34.64.228.162:5000`

### VM 작동방법

#### (백엔드 실행-띄어쓰기 중요) yarn start 대신 pm2로 실행
pm2 --name express start npm -- run start

#### (참고) pm2로 실행 중인 프로세스 보기
pm2 list

#### (참고) pm2로 실행 중인 프로세스 종료
pm2 delete <번호>
