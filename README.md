Install [the Go programming language](https://golang.org/) on Linux with this command.

Set the `goversion` at the start of the command to your desired version.

`export goversion=1.9.2; git clone https://github.com/gonutz/getgo.git; chmod u+x getgo/getgo; sudo -E getgo/getgo; rm -rf getgo`

This will install the 32 bit Linux version and set the `GOPATH` to the folder `go` in your user's home folder.

After you are done, log out and back in to apply the environment variable changes.

`gnome-session-quit`

Here is the full command line, including log out:

`export goversion=1.9.2; git clone https://github.com/gonutz/getgo.git; chmod u+x getgo/getgo; sudo -E getgo/getgo; rm -rf getgo; gnome-session-quit`
