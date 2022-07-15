# vaultwarden
패스워드관리 툴 Bitwarden 대체인 vaultwarden입니다.
docker-compose 를 이용하여 구축하였으며

포트 및 기타 설정값은 docker-compose.yml을 수정하시기바랍니다.
db는 sqlite에 자동으로 저장되며 ./data에 쌓입니다.
#사용법
git clone https://github.com/dalso0418/vaultwarden.git
cd ds-vaultwarden
docker-compose up -d
