# Passportwithmedia
This example for laravel passport with medialibrary
  
# Installation
camposer update or composer install

# Auth Api
http://127.0.0.1:8000/api/register

curl --location --request POST 'http://127.0.0.1:8000/api/register' \
--header 'Accept: application/json' \
--form 'name="sarim ali"' \
--form 'email="sarim2@gmail.com"' \
--form 'password="123456"'

http://127.0.0.1:8000/api/login

curl --location --request POST 'http://127.0.0.1:8000/api/login' \
--header 'Accept: application/json' \
--form 'email="sarim2@gmail.com"' \
--form 'password="123456"'

# Employee Operation
http://127.0.0.1:8000/api/employee

curl --location --request GET 'http://127.0.0.1:8000/api/employee' \
--header 'Accept: application/json' \
--header 'Authorization: Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiJ9.eyJhdWQiOiI5OWI3NTFjMC1kMWJjLTRlYTMtODQyMi0xNWJkZmU4MTNhNTUiLCJqdGkiOiIyNjdhNGE3NzljODYzODllOWE0ZDBkYmU2MzM1MjU0YzMyZGZkOTE2NmFlMGE5NDI2Yzg3YzQwMjZiMTI1ZGExYzBlYWVhZTE3NzNiNmU2OSIsImlhdCI6MTY5MDEyNjMxNi41MTIwNDcsIm5iZiI6MTY5MDEyNjMxNi41MTIwNTEsImV4cCI6MTcyMTc0ODcxNi40MzA1NzEsInN1YiI6IjIyIiwic2NvcGVzIjpbXX0.Ar96BB0rvAmRbRhBc5xODRPDqAhXru_1aJOpzN15gYp69g5kk7k_oYjuTEY6vFdobYXJL7MlLaX-RThBZR3W7-B8uDaqz47DNPjj3rbHWvUlBTdI3GLkgKMGKumHgOdnEO1jOLWLehNczM7BjSUpzMgu0L7BJN9qbaiYvDu7rHgq4K8dB4WBLiCGP9dJXhb3VvPQjkC1R_ILk2Iv6_si4UZW_wPsoVOvA_vrkJwk-DAvGhSm5MdIVTXG-kRZPMv2gfs33Vn8fkdlpBCK6hTMfZ6CSBcKBkv17gDPmZhZhuJoEb5zojl_n_iUCXo62xY7Hm11_uwieu45qSYwye-0R7SCmqlkccFgft56yZk_-M_4h8mjDR_c1_DwPIt5aIZKYsZt4_rJOZ_AQDRkJzL4DPWXL0nJP3T_ws_GTJz-p7g0JN-eODPSu3UepaqjNUFlczNb02otwGw3BS_t1YpQ6MHTNeNhpfQznesK1C_2I0y3gkW1qwPD53MYNlOeQ6RppnKDiK28aD-qBAN_u3mxQRsBluLPvmbdunhiKv-LtfHuuzy4HyWyEZSm2OlxfFCn2bOlpGiQzZX2Xtc-QKTJAEA_MpLepLLb6rRpcjR8KyEHaoc6qCmMH4yyw5sfYgENMYO2Mcb3PhwLk3u02JglEvCQyj4lGk62qtkwO5J0two'


http://127.0.0.1:8000/api/employee


curl --location --request POST 'http://127.0.0.1:8000/api/employee' \
--header 'Accept: application/json' \
--header 'Authorization: Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiJ9.eyJhdWQiOiI5OWI3NTFjMC1kMWJjLTRlYTMtODQyMi0xNWJkZmU4MTNhNTUiLCJqdGkiOiIyNjdhNGE3NzljODYzODllOWE0ZDBkYmU2MzM1MjU0YzMyZGZkOTE2NmFlMGE5NDI2Yzg3YzQwMjZiMTI1ZGExYzBlYWVhZTE3NzNiNmU2OSIsImlhdCI6MTY5MDEyNjMxNi41MTIwNDcsIm5iZiI6MTY5MDEyNjMxNi41MTIwNTEsImV4cCI6MTcyMTc0ODcxNi40MzA1NzEsInN1YiI6IjIyIiwic2NvcGVzIjpbXX0.Ar96BB0rvAmRbRhBc5xODRPDqAhXru_1aJOpzN15gYp69g5kk7k_oYjuTEY6vFdobYXJL7MlLaX-RThBZR3W7-B8uDaqz47DNPjj3rbHWvUlBTdI3GLkgKMGKumHgOdnEO1jOLWLehNczM7BjSUpzMgu0L7BJN9qbaiYvDu7rHgq4K8dB4WBLiCGP9dJXhb3VvPQjkC1R_ILk2Iv6_si4UZW_wPsoVOvA_vrkJwk-DAvGhSm5MdIVTXG-kRZPMv2gfs33Vn8fkdlpBCK6hTMfZ6CSBcKBkv17gDPmZhZhuJoEb5zojl_n_iUCXo62xY7Hm11_uwieu45qSYwye-0R7SCmqlkccFgft56yZk_-M_4h8mjDR_c1_DwPIt5aIZKYsZt4_rJOZ_AQDRkJzL4DPWXL0nJP3T_ws_GTJz-p7g0JN-eODPSu3UepaqjNUFlczNb02otwGw3BS_t1YpQ6MHTNeNhpfQznesK1C_2I0y3gkW1qwPD53MYNlOeQ6RppnKDiK28aD-qBAN_u3mxQRsBluLPvmbdunhiKv-LtfHuuzy4HyWyEZSm2OlxfFCn2bOlpGiQzZX2Xtc-QKTJAEA_MpLepLLb6rRpcjR8KyEHaoc6qCmMH4yyw5sfYgENMYO2Mcb3PhwLk3u02JglEvCQyj4lGk62qtkwO5J0two' \
--header 'Cookie: XSRF-TOKEN=eyJpdiI6Ik9QL2JHeERGb0crd3lQeEc4R1R1R0E9PSIsInZhbHVlIjoiV28rYUFxY1ZocXI2NnZhVEl0S2xPMmdtUWpsbExaS1Q1cFUvejlXTFlRRi94bkIwT0pFdDRhKzBzMXlLY1Vxb29OS1dlN1VQTVY2eVViaFZRVlFhenh3LzVTZmtTZzluMXg5Ym5ZZnFTN1ZqQmVqRitIY210VEpSeU9NMFdha3giLCJtYWMiOiJlMGZiODc5NjZhMzc0OWM2NTM2MzNhMGU4MGNlMWI4NzRjYjY2OTllMzZhNTViOTAxOGU0ZTRjNjllMzg4M2VjIiwidGFnIjoiIn0%3D; laravel_session=eyJpdiI6IlRsSlZ0WHR1UlA1dklEaXR3K0ROMXc9PSIsInZhbHVlIjoiNWEzdktaY2RvWXd3dUEzWWN2VVFCblF6VXBRakdCUGFVMGhQWGV5M2pSVXl2bnNvMVZBZmJMR3loTjg3SkV0WGcwRVNLUGZuaVhzenNseWtzZzI0aU1Ca3pORU1uZ1U4dDdVYUNobk4ydjhCWWpCWldieERwT3N1NWJEMDZMZ0UiLCJtYWMiOiIwMDNmY2ZkOGU3MDkxZDg1Y2M0ZDllYmU2OGM5ODlkZjNhZjRhYzE2YzQzN2Y4NGFlMjFlZTExOWViODZjZWIwIiwidGFnIjoiIn0%3D' \
--form 'name="sarim"' \
--form 'age="15"' \
--form 'job="php laravel"' \
--form 'salary="120"' \
--form 'image=@"/C:/Users/Asus/Downloads/pexels-pixabay-268533.jpg"'



http://127.0.0.1:8000/api/employee/13


curl --location --request PATCH 'http://127.0.0.1:8000/api/employee/13' \
--header 'Accept: application/json' \
--header 'Authorization: Bearer eyJ0eXAiOiJKV1QiLCJhbGciOiJSUzI1NiJ9.eyJhdWQiOiI5OWI3NTFjMC1kMWJjLTRlYTMtODQyMi0xNWJkZmU4MTNhNTUiLCJqdGkiOiIyNjdhNGE3NzljODYzODllOWE0ZDBkYmU2MzM1MjU0YzMyZGZkOTE2NmFlMGE5NDI2Yzg3YzQwMjZiMTI1ZGExYzBlYWVhZTE3NzNiNmU2OSIsImlhdCI6MTY5MDEyNjMxNi41MTIwNDcsIm5iZiI6MTY5MDEyNjMxNi41MTIwNTEsImV4cCI6MTcyMTc0ODcxNi40MzA1NzEsInN1YiI6IjIyIiwic2NvcGVzIjpbXX0.Ar96BB0rvAmRbRhBc5xODRPDqAhXru_1aJOpzN15gYp69g5kk7k_oYjuTEY6vFdobYXJL7MlLaX-RThBZR3W7-B8uDaqz47DNPjj3rbHWvUlBTdI3GLkgKMGKumHgOdnEO1jOLWLehNczM7BjSUpzMgu0L7BJN9qbaiYvDu7rHgq4K8dB4WBLiCGP9dJXhb3VvPQjkC1R_ILk2Iv6_si4UZW_wPsoVOvA_vrkJwk-DAvGhSm5MdIVTXG-kRZPMv2gfs33Vn8fkdlpBCK6hTMfZ6CSBcKBkv17gDPmZhZhuJoEb5zojl_n_iUCXo62xY7Hm11_uwieu45qSYwye-0R7SCmqlkccFgft56yZk_-M_4h8mjDR_c1_DwPIt5aIZKYsZt4_rJOZ_AQDRkJzL4DPWXL0nJP3T_ws_GTJz-p7g0JN-eODPSu3UepaqjNUFlczNb02otwGw3BS_t1YpQ6MHTNeNhpfQznesK1C_2I0y3gkW1qwPD53MYNlOeQ6RppnKDiK28aD-qBAN_u3mxQRsBluLPvmbdunhiKv-LtfHuuzy4HyWyEZSm2OlxfFCn2bOlpGiQzZX2Xtc-QKTJAEA_MpLepLLb6rRpcjR8KyEHaoc6qCmMH4yyw5sfYgENMYO2Mcb3PhwLk3u02JglEvCQyj4lGk62qtkwO5J0two' \
--form 'name="jeanne"' \
--form 'age="15"' \
--form 'job="php laravel"' \
--form 'salary="120"' \
--form 'image=@"/C:/Users/Asus/Downloads/thumbnail.png"'
