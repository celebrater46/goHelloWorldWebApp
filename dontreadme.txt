### Must put your project folder into “${GOPATH}/src”. Not /src/myapps.

(${GOPATH} = C:\Users\hoge\sdk\go1.17 or go1.17\bin)
Golang is very rigid about directory. I put my project “first_webapp” in “C:\Users\hoge\sdk\go1.17\src\myapps”. But “go install” was not working. I moved the project into “C:\Users\hoge\sdk\go1.17\src”, it was working.
“first_webapp.exe” existed in GOPATH/bin after “go install”, I clicked it. And then accessed “http://localhost:8080”, “Hello World” succeeded.