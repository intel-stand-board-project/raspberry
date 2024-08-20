# raspberry
server for raspberryPI 4

| files | description |
| --- | --- |
| iot_server.c | 소켓을 열어두고 클라이언트 간의 정보 송수신을 중계해 주는 서버 코드 |
| iot_client.c | 임시 조정을 위해 명령어를 보내기 위한 클라이언트 코드 |
| iot_client_bluetooth.c | 블루투스를 통해서 송수신하는 정보를 중계하기 위한 클라이언트 코드 |
| iot_client_sql.c | DB 입출력을 위한 클라이언트 |
