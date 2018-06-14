Install [the Go programming language](https://golang.org/) on Raspbian with this command.

Set the `goversion` at the start of the command to your desired version.

`export goversion=1.9.2; git clone https://github.com/gonutz/getgopi.git; chmod u+x getgopi/getgo; sudo -E getgopi/getgo; rm -rf getgopi`

This will install the 32 bit Linux version and set the `GOPATH` to the folder `go` in your user's home folder.

After you are done, log out and back in to apply the environment variable changes.
