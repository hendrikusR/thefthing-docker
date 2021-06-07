# TheFThing Docker 

* Step

- Turn of your webserver
- Runing docker-compose up -d ( Jika pull from cache, running docker-compose build --no-cache dan jalankan docker-compose up -d )
- import sql thefthing melalui terminal dengan perintah mysql -u root -h 127.0.0.1 -P 33066 -p thefthing < (your file mysql )
- akses api di port 5000, http://localhost:5000
- akses frontend dengan url http://localhost
