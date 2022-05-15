# dadjokes
This CLI tool provides random jokes using this API https://icanhazdadjoke.com/api. 


## To use the tool 
```
go get github.com/example/dadjoke
```

```
$dadjokes --help
Dadjoke CLI is a tool that gives you a random dad joke

Usage:
  dadjokes [flags]
  dadjokes [command]

Available Commands:
  completion  Generate the autocompletion script for the specified shell
  help        Help about any command
  random      Get a random dad joke

Flags:
      --config string   config file (default is $HOME/.dadjokes.yaml)
  -h, --help            help for dadjokes
  -t, --toggle          Help message for toggle

Use "dadjokes [command] --help" for more information about a command.

```

## With this, we learned
* Using Cobra to create cli
* Add command to the tool
* Add global and local flags

### Initialize the project with Cobra
```
cobra init --pkg-name github.com/akankshakumari393/dadjoke
```

### Add command to the tool
```
cobra add random
```
