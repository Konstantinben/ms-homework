# ms-homework

#### Образ собран командой:
`docker buildx build --platform linux/amd64 -t kpolyanichko/ms-homework-amd64:latest --push .`
<br/>
<br/>
#### Запуск:
`docker run -d -p 8080:8080 kpolyanichko/ms-homework-amd64`
`docker run --platform linux/amd64 -d -p 8080:8080 kpolyanichko/ms-homework-amd64`
<br/>
<br/>
#### Эндпоинт:
http://localhost:8080/health