# mdout-config

这个项目是mdout的附属项目，为mdout提供html模板以及配置文件，目前有三套主题

- `default`  
    这个主题是mdout目前的默认主题，改自[zhangjikai/markdown-css](https://github.com/zhangjikai/markdown-css)，进行了一些修改，并且加入了比较合适的hljs配色。
- `mathjax`  
    这个主题是`default`主题的升级版，保留所有`default`的基础上加入了`mathjax`数学公式渲染，但是由于`mathjax`库有60MB之大，我在github上找了一个600k精简版[tiborsimon/mathjax-minimal-package](https://github.com/tiborsimon/mathjax-minimal-package)替换了官方库，实际测试中在一些平台会遇到报错找不到文件，但是任然可以正常渲染，如果遇到渲染不了的，可以手动下载官方的库并替换。如果你有更稳定的精简版，可以提PR。

- `github`
    这个主题改自[sindresorhus/github-markdown-css](https://github.com/sindresorhus/github-markdown-css)，为了适配mdout，我稍作了修改，并且原主题并不适配hljs，因此我加入了hljs官方的github主题。
