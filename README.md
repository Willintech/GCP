# GCP
go lang Google Cloud project 

*download golonag for windows*:   https://go.dev/dl/
*command to migrate installation to your path (bash terminal):   export PATH="/c/Program Files/Go/bin:$PATH
*command to verify go is installed*:   go version
*command to clone this repository*:    https://github.com/Willintech/GCP.git

- cd gcp-go-app                (location of project)
- go mod tidy                  (ensures dependencies are correct)
- go run main.go               (runs the server, *Loading*, accept windows security)

*TEST EVERYTHING WORKS*
- http://localhost:8080        (test in browser)
                           OR
- curl.exe http://localhost:8080 (test GCP server in powershell terminal)

You should see: HELLO FROM GO ON GOOGLE CLOUD

to exit/quit server run this command in the BASH terminal: ctrl + c         (control button and c key)
