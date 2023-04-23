# books.xfoss.com

## 书籍

- [最新：Rust 编程语言 ⚙️](https://rust-lang.xfoss.com/)


- [60 天通过 CCNA 考试（计算机网络） 🛰️](https://ccna60d.xfoss.com) <iframe src="https://ghbtns.com/github-btn.html?user=gnu4cn&repo=ccna60d&type=star&count=true" frameborder="0" scrolling="0" width="150" height="20" title="GitHub"></iframe>


- [Java 编程语言 ☕️](https://java.xfoss.com/)


- [代码 snippets 与技术笔记 · ✨](https://snippets.xfoss.com/)


- [TypeScript 编程语言 📃](https://ts.xfoss.com/)


<details>

<summary>在本地阅读</summary>

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

</details>



<details>
    <summary>打赏，donate 💰</summary>

>
> **为何要打赏**？
>
> 由于 xfoss.com 运营需要一点开支（每年大概 ￥500）。所以如果你觉得这里的内容有帮助，那么请通过下列渠道进行打赏。
>
> 也欢迎向这个代码仓库: [gnu4cn/buy-me-a-coffee](https://github.com/gnu4cn/buy-me-a-coffee) 提交 PR，加入你想加入的内容。我经过考虑后，可合并 PR。由于此网站内容会定时同步那个代码仓库的内容，因此合并的 PRs 将接近实时显示出来。
>
>



![支付宝-Alipay: laxers@gmail.com](alipay-laxers.png)

*支付宝 - Alipay，扫码付款*




![微信支付-WeChat Pay: xfoss-com](wechat-pay-lenny.png)

*微信支付 - WeChat Pay, 扫码付款*


</details>


