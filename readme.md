<center>

## gtl

[English](readme.md) | [简体中文](readme.zh-cn.md)

[![](https://img.shields.io/crates/v/gtl.svg)](https://crates.io/crates/gtl)
[![](https://img.shields.io/crates/d/gtl.svg)](https://img.shields.io/crates/d/gtl.svg)
[![](https://img.shields.io/crates/l/gtl.svg)](./license)

</center>

> `gtl` is a Git-based tool designed to simplify the management of multiple remote repositories. It extends Git's functionality by providing one-click initialization and pushing to multiple remote repositories, making it especially useful for developers who need to maintain multiple remote repositories simultaneously.

## Features

- **Multi-remote repository management**: Supports configuring multiple remote repositories for a single local repository.
- **One-click remote repository initialization**: Allows you to initialize and configure multiple remote repositories in one command.
- **One-click push to multiple remote repositories**: You can push code to all configured remote repositories with a single command, saving time and effort.
- **Git command extensions**: Adds convenient operations to Git, improving work efficiency.

## Installation

Install `gtl` via `cargo`:

```bash
cargo install gtl
```

## Usage

### Configuration file

> Path: /home/.git_helper/config.json

```json
{
  "D:\\code\\gtl": [
    { "name": "gitee", "url": "git@gitee.com:eastspire/gtl.git" },
    { "name": "origin", "url": "git@github.com:eastspire/gtl.git" }
  ]
}
```

### Initialize multiple remote repositories

Assuming you already have a local Git repository and want to link it to multiple remote repositories, use the following command:

```bash
gtl init
```

### One-click push to all remote repositories

After configuring multiple remote repositories, use the following command to push code to all configured remote repositories:

```bash
gtl push
```

### Git add & commit & push

```bash
gtl acp
```

### Version

```bash
gtl -v
gtl version
gtl --version
```

### Help

```bash
gtl help
```

## Appreciate

**If you find `hyperlane` helpful, feel free to donate.**

<img src="https://docs.ltpp.vip/img/wechat-pay.png" width="200">  
<img src="https://docs.ltpp.vip/img/alipay-pay.jpg" width="200">

## License

This project is licensed under the MIT License. For more details, please refer to the [license](license) file.

## Contribution

Contributions are welcome! Please submit issues or create pull requests.

## Contact

If you have any questions, please contact the author: [root@ltpp.vip](mailto:root@ltpp.vip).
