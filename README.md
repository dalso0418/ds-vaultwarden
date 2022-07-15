# vaultwarden
패스워드관리 툴 Bitwarden 대체인 vaultwarden입니다.<br>
docker-compose 를 이용하여 구축하였으며
<br>
포트 및 기타 설정값은 docker-compose.yml을 수정하시기바랍니다.<br>
db는 sqlite에 자동으로 저장되며 ./data에 쌓입니다.<br>
<br>

# 사용법
설치 가이드 - https://svrforum.com/svr/360722
<br>
git clone https://github.com/dalso0418/ds-vaultwarden.git<br>
cd ds-vaultwarden<br>
docker-compose up -d<br>
<br>

# PW를 까먹었을때
docker-compose 내의 주석처리되어있는 admin_token을 사용해 관리자페이지 설정값으로 접근 <br>
https://[도메인]/admin

