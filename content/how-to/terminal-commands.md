---
title: "Vital Terminal Tools"
date: 2022-11-26
tags: ["Linux"]
image: "/images/how-to/terminal-commands/main.png"
type: "post"
draft: false
showtableOfContents: true
---

## [TLDR](https://github.com/tldr-pages/tldr)
A humane version of man pages. 

### Install 
```bash
pip3 install tldr
```

![](/images/terminal-commands/1.png)

## [AutoJump](https://github.com/wting/autojump)

A faster way to navigate your filesystem. Saves a lot of time.

### Install 

```bash
sudo apt install autojump
```

![](/images/terminal-commands/2.png)

## [Trash-CLI](https://github.com/andreafrancia/trash-cli)

Deletes the files to recycle bin in terminal. 

### Install
```bash
sudo apt install trash-cli
```

You can make a alias for "rm" to trash-cli by adding the following alias to ~/.bashrc file.

```bash
alias rm="trash" 
```
## [Ccrypt](https://github.com/wvangeit/ccrypt)

Secure encryption and decryption of files and streams.

### Install 
```bash
sudo apt install ccrypt
```

#### Encrypt

```bash
ccencrypt path-to-file
```

#### Decrypt
```bash
ccdecrypt path-to-file
```

that's it ✌🏽

-------------------------------------------------------------

{{< rawhtml >}} 
<script src="https://utteranc.es/client.js"
        repo="mansoorbarri/website"
        issue-term="title"
        theme="dark-blue"
        crossorigin="anonymous"
        async>
</script>
{{< /rawhtml >}}