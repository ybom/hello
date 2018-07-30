# hello

## Create your GOPATH.
This is your Go workspace, which is where you are going to create all your Go projects.
  1. Create your go folder. I created it at `$HOME/repos/go`
  1.	Create the following folders inside `bin`, `pkg`, `src`
  1.	Add the following lines to your shell profile (bash, zsh, fish) and source your shell profile file afterwards:
```
export PATH="/usr/local/go/bin:$PATH"
export GOPATH=$HOME/repos/go
export PATH="$HOME/repos/go/bin:$PATH"
```
  
## Write your first program
  1.	`mkdir $GOPATH/src/github.com/user/hello`
  1.	clone this repo or write hello world code
  1.	Compile it with: `go install github.com/user/hello`
  1.	Execute it with: `$GOPATH/bin/hello`
