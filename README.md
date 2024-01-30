how to host invidious in docker gitpod
1. run sudo apt update
2. run openssl rand -hex 20
3. copy the key
4. nano docker-compose.yml
5. paste the key into "hmac_key"
6. in ports on line 16, change it to "3000:3000"
7. save the modified file
8. run docker-compose up
9. profit
