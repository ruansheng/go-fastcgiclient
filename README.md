# go-fcgiclient

## start php server listen port 9000
	./php-fpm

## replace php script file
	vim testclient.go
	replace SCRIPT_FILENAME
## go run testclient.go
	content: X-Powered-By: PHP/5.6.9
	Content-type: text/html; charset=UTF-8
	
	hello world%