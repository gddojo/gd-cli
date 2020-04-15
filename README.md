# Environment Variables

**GODOT_CHANNEL**: Channel to install/run such as stable, beta, or alpha

**GODOT_VERSION**: Version to run/install

**GODOT_PATH**: Directory to run/install godot

```sh
Usage: gd-cli [--help|-h] <command>

Flags:
    --help | -h    Show help (this prompt)

Commands:

install:

Usage: gd-cli [--channel|-c <channel>] [--version|-v <version>] [--path|-p <path>] [--export|-e] install

Flags:
    --channel | -c <channel>    Channel to run, default: $GODOT_CHANNEL or stable
    --version | -v <version>    Version to run, default: $GODOT_VERSION
    --path    | -p <path>       Path to installation, default: $GODOT_PATH or /bin/godot/
    --export  | -e              Installs export templates

run:

Usage: gd-cli [--channel|-c <channel>] [--version|-v <version>] [--path|-p <path>] run -- <arguments>

Flags:
    --channel | -c <channel>    Channel to run, default: $GODOT_CHANNEL or stable
    --version | -v <version>    Version to run, default: $GODOT_VERSION
    --path    | -p <path>       Path to installation, default: $GODOT_PATH or /bin/godot/
    <arguments>                 Additional arguments to send to godot
```