# Go Cheat Sheet

The following are a list of commands for the Go CLI and tooling to help with Go development. 

##  Go CLI

Build and/or run process

| Command | Description |
|---------|-------------|
| go build | Compile packages and dependencies (creates an executable) |
| go clean | Remove obj files and clears cached files |
| go run &lt;filename&gt; | Compile and run the selected file (e.g go run main.go) |


Packages

| Command | Description |
|---------|-------------|
| go get &lt;url&gt; | Get's packages, downloads to local cache (e.g. go get github.com/putridparrot/GoUnits) |
| go list | List packages or modules |
| go vet | List possible mistakes in packages |
| go mod tidy | Removes any unused dependencies |

Testing

| Command | Description |
|---------|-------------|
| go test | Execute test packages |

## Golint

Install using _go install golang.org/x/lint/golint@latest_

| Command | Description |
|---------|-------------|
| golint ./... | Run golint against a given path |