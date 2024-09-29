# proto-plugins

Some plugins for proto, the pluggable version manager.

## Available plugins

All plugins available in this repository along with install instructions.

### OpenTofu

The open source infrastructure as code tool.

Install plugin and the latest binary with the following commands:

```bash
proto plugin add tofu "source:https://raw.githubusercontent.com/bjoern-reetz/proto-plugins/main/toml-plugins/tofu.toml"
proto install tofu
```

Visit the [OpenTofu homepage](https://opentofu.org/) or the [OpenTofu repository](https://github.com/opentofu/opentofu) for details about OpenTofu.

### Ruff

An extremely fast Python linter and code formatter, written in Rust.

Install plugin and the latest binary with the following commands:

```bash
proto plugin add ruff "source:https://raw.githubusercontent.com/bjoern-reetz/proto-plugins/main/toml-plugins/ruff.toml"
proto install ruff
```

Visit the [Ruff homepage](https://docs.astral.sh/ruff/) or the [Ruff repository](https://github.com/astral-sh/ruff) for details about Ruff.
