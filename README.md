# rpc

compile:


  for server: <br>
    gcc -Wall -o test_server test_clnt.c test_srv_func.c test_svc.c

	for client:
		gcc -Wall -o test_client test_client.c test_clnt.c

run:

	for server:
		./test_server
    
	for client:
		./test_client <server_ip>
