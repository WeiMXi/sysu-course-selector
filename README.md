# 中山大学(SYSU)新版选课系统的抢课软件

## 这是什么？

这是一个基于 python3 的抢课软件，系我在贵校就读三年来，从未选上理想的课程，愤然而作。

实践证明，有了它的帮助，我的确选到了我想要的课程。

## 如何使用？

1. 我只提供了源代码，所以首先你得准备一个 [python 3.7.0](https://www.python.org/downloads/)，
2. 安装对应的依赖 `pip install -r requirements.txt`，
3. 根据你的实际情况修改 `info.py`，
4. 运行 `main.py` `python main.py`，
5. 根据 `code.bmp` 中的验证码，输入验证码，
6. 输入你想选的课的课程号，
7. 别关掉它，耐心等待。

需要注意的是，这个抢课软件也仅仅是在有人退课的情况下为你尽快抢选这门课程。因此，它不能保证你一定能够选上这门课——说不定大家都不退课，或者有别人也用了这个软件捷足先登了呢。

## 我是真的不会用怎么办？

请带上一杯奶茶找我，我帮你。如果我们素未谋面，请在 issue 留下您的邮箱。

## 它安全吗？

全部的代码就放在这里。你，信，还是不信；课，抢，还是不抢。

## 我想请你喝奶茶

我得想个办法，不让任何一个想请我喝奶茶的愿望落空。

## 出现了bug？

请在提交 issue 时附带运行时生成的 `log3.log`，这样能方便我定位错误。

## 更新计划

- 打包成二进制可执行文件（没什么动力）。
- 我的代码只在SE专业的专选课程进行过测试，希望能够将适用性扩展到更多专业和更多课程类别。
- 二维码的机器识别。
- TBD