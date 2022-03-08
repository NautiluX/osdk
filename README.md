# osdk
Version switcher for operator-sdk

## Install/Update

```
curl https://raw.githubusercontent.com/NautiluX/osdk/main/osdk -o ~/Downloads/osdk;chmod +x ~/Downloads/osdk; sudo mv ~/Downloads/osdk /usr/bin/osdk;
```

## Usage

```
$ osdk 1.18.0
Now using operator-sdk version: "v1.18.0", commit: "c9c61b6921b29d731e64cd3cc33d268215fb3b25", kubernetes version: "1.21", go version: "go1.17.7", GOOS: "linux", GOARCH: "amd64"
To force reinstall, delete '/usr/local/bin/osdk/operator-sdk_v1.18.0' and run 'osdk v1.18.0' again

$ osdk v1.18.0
Now using operator-sdk version: "v1.18.0", commit: "c9c61b6921b29d731e64cd3cc33d268215fb3b25", kubernetes version: "1.21", go version: "go1.17.7", GOOS: "linux", GOARCH: "amd64"
To force reinstall, delete '/usr/local/bin/osdk/operator-sdk_v1.18.0' and run 'osdk v1.18.0' again

$ ./osdk 0.18.0
Now using operator-sdk version: "v0.18.0", commit: "921c33982687d6e9219fe0a1a326515fb37ae040", kubernetes version: "v1.18.2", go version: "go1.13.10 linux/amd64"
To force reinstall, delete '/usr/local/bin/osdk/operator-sdk_v0.18.0' and run 'osdk v0.18.0' again
```
