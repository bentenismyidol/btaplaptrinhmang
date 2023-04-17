# btaplaptrinhmang
nguyen viet thanh-20207632
cach chay:
+)
gcc sv_server.c -o sv_server

./sv_server

gcc sv_client.c -o sv_client

./sv_client 127.0.0.1 9000

+)

gcc tcp_server.c -o tcp_server

./tcp_server 9000 ./txt/hello.txt ./txt/log_tcp_server.txt

gcc tcp_client.c -o tcp_client

./tcp_client 127.0.0.1 9000
