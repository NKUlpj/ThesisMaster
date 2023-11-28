# require

## Mac
[`MacTeX`](https://www.tug.org/mactex/)

## Windows
[`See 👉`](https://zhuanlan.zhihu.com/p/64574294)

！！！不要使用Vscode的Latex_workshop等插件编译。因为本模板使用的是`biber` 而非 `BibTex`,或者可自行修改配置文件。

# how to compile

```sh
xelatex main
biber main
xelatex main
xelatex main
```