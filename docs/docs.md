# scdl-go

## Usage
> This tool can download songs and playlists from soundcloud

scdl-go

## Flags
|Flag|Usage|
|----|-----|
|`--debug`|enable debug messages|
|`--disable-update-checks`|disables update checks|
|`--raw`|print unstyled raw output (set it if output is written to a file)|

## Commands
|Command|Usage|
|-------|-----|
|`scdl-go completion`|Generate the autocompletion script for the specified shell|
|`scdl-go help`|Help about any command|
# ... completion
`scdl-go completion`

## Usage
> Generate the autocompletion script for the specified shell

scdl-go completion

## Description

```
Generate the autocompletion script for scdl-go for the specified shell.
See each sub-command's help for details on how to use the generated script.

```

## Commands
|Command|Usage|
|-------|-----|
|`scdl-go completion bash`|Generate the autocompletion script for bash|
|`scdl-go completion fish`|Generate the autocompletion script for fish|
|`scdl-go completion powershell`|Generate the autocompletion script for powershell|
|`scdl-go completion zsh`|Generate the autocompletion script for zsh|
# ... completion bash
`scdl-go completion bash`

## Usage
> Generate the autocompletion script for bash

scdl-go completion bash

## Description

```
Generate the autocompletion script for the bash shell.

This script depends on the 'bash-completion' package.
If it is not installed already, you can install it via your OS's package manager.

To load completions in your current shell session:

	source <(scdl-go completion bash)

To load completions for every new session, execute once:

#### Linux:

	scdl-go completion bash > /etc/bash_completion.d/scdl-go

#### macOS:

	scdl-go completion bash > $(brew --prefix)/etc/bash_completion.d/scdl-go

You will need to start a new shell for this setup to take effect.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... completion fish
`scdl-go completion fish`

## Usage
> Generate the autocompletion script for fish

scdl-go completion fish

## Description

```
Generate the autocompletion script for the fish shell.

To load completions in your current shell session:

	scdl-go completion fish | source

To load completions for every new session, execute once:

	scdl-go completion fish > ~/.config/fish/completions/scdl-go.fish

You will need to start a new shell for this setup to take effect.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... completion powershell
`scdl-go completion powershell`

## Usage
> Generate the autocompletion script for powershell

scdl-go completion powershell

## Description

```
Generate the autocompletion script for powershell.

To load completions in your current shell session:

	scdl-go completion powershell | Out-String | Invoke-Expression

To load completions for every new session, add the output of the above command
to your powershell profile.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... completion zsh
`scdl-go completion zsh`

## Usage
> Generate the autocompletion script for zsh

scdl-go completion zsh

## Description

```
Generate the autocompletion script for the zsh shell.

If shell completion is not already enabled in your environment you will need
to enable it.  You can execute the following once:

	echo "autoload -U compinit; compinit" >> ~/.zshrc

To load completions in your current shell session:

	source <(scdl-go completion zsh); compdef _scdl-go scdl-go

To load completions for every new session, execute once:

#### Linux:

	scdl-go completion zsh > "${fpath[1]}/_scdl-go"

#### macOS:

	scdl-go completion zsh > $(brew --prefix)/share/zsh/site-functions/_scdl-go

You will need to start a new shell for this setup to take effect.

```

## Flags
|Flag|Usage|
|----|-----|
|`--no-descriptions`|disable completion descriptions|
# ... help
`scdl-go help`

## Usage
> Help about any command

scdl-go help [command]

## Description

```
Help provides help for any command in the application.
Simply type scdl-go help [path to command] for full details.
```


---
> **Documentation automatically generated with [PTerm](https://github.com/x0f5c3/cli-template) on 01 July 2022**
