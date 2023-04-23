# 在本地阅读

在本地阅读本书，先将对应书本的代码仓库克隆到本地，并需要安装 `mdbook` 程序。根据操作系统的不同，安装 `mdbook` 程序有所不同。


### 在 Linux 系统上

```console
$ curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
$ cargo install mdbook
```

### 在 Windows 上

```powershell
# 在 "Administrator: Windows Powershell" 中，先安装 choco
> Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
# 经由 choco 安装 msys2
> choco install -y msys2
```

```console
# 在 msys2 中安装 mdbook
$ pacman -S mingw-w64-x86_64-mdbook
```

安装好 `mdbook` 后, 带一些命令行参数和开关运行服务器：

```console
$ mdbook serve ~/ccna60d -p 8080 -n 127.0.0.1 --open
```

> 注：当在 Windows 系统上时，咱们要在 `msys2` 的终端窗口中运行此命令。

此时，将在操作系统的默认浏览器中，打开本书。

如需帮助，请加微信：`xfoss-com`
