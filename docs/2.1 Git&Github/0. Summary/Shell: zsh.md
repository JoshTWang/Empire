# ZSH

## Bash --> zsh

```shell
The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
```

## Install oh my zsh

https://github.com/ohmyzsh/ohmyzsh

```shell
zsh --version
zsh 5.8.1 (x86_64-apple-darwin21.0)

morningstar@crc-dot1x-nat-10-239-200-127 novel % sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
Cloning Oh My Zsh...
remote: Enumerating objects: 1276, done.
remote: Counting objects: 100% (1276/1276), done.
remote: Compressing objects: 100% (1232/1232), done.
remote: Total 1276 (delta 24), reused 1198 (delta 24), pack-reused 0
Receiving objects: 100% (1276/1276), 1.06 MiB | 9.88 MiB/s, done.
Resolving deltas: 100% (24/24), done.
From https://github.com/ohmyzsh/ohmyzsh
 * [new branch]      master     -> origin/master
branch 'master' set up to track 'origin/master'.
Already on 'master'
/Users/morningstar/git/codes/basics/novel

Looking for an existing zsh config...
Found ~/.zshrc. Backing up to /Users/morningstar/.zshrc.pre-oh-my-zsh
Using the Oh My Zsh template file and adding it to ~/.zshrc.

         __                                     __   
  ____  / /_     ____ ___  __  __   ____  _____/ /_  
 / __ \/ __ \   / __ `__ \/ / / /  /_  / / ___/ __ \ 
/ /_/ / / / /  / / / / / / /_/ /    / /_(__  ) / / / 
\____/_/ /_/  /_/ /_/ /_/\__, /    /___/____/_/ /_/  
                        /____/                       ....is now installed!


Before you scream Oh My Zsh! look over the `.zshrc` file to select plugins, themes, and options.

• Follow us on Twitter: https://twitter.com/ohmyzsh
• Join our Discord community: https://discord.gg/ohmyzsh
• Get stickers, t-shirts, coffee mugs and more: https://shop.planetargon.com/collections/oh-my-zsh
```

- `.zshrc`
- `.zshrc.pre-oh-my-zsh`
- `.zsh_history`



### cURL

cURL is **a command-line tool that lets you transfer data to/from a server using various protocols**.

```shell
morningstar@crc-dot1x-nat-10-239-200-127 novel % which curl
which curl
/usr/bin/curl
morningstar@crc-dot1x-nat-10-239-200-127 novel % curl --version
curl --version
curl 7.79.1 (x86_64-apple-darwin21.0) libcurl/7.79.1 (SecureTransport) LibreSSL/3.3.6 zlib/1.2.11 nghttp2/1.45.1
Release-Date: 2021-09-22
```



## changing the default shell in VScode

1. command + shift + p
2. **`Terminal: Select Default Profile`**