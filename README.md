# How to use
- You can place this bash file at the root directory of your Golang application.
- Add the path of your entrypoint file on ENTRYPOINT variable on the script.
- Call `bash hotreload.sh` everytime you change an file tracked by git, `go run ...` will
be called automatically, so you will dont have to be recompiling the project manually everytime.

# Teste
- Clone this repo, call `bash hotreload.sh` and change something on `main.go` file.
