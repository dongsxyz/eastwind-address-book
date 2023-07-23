# 人工智能类

这里列举了一些作者自己常用的 AI、ML 工具。它们可以作为工作和生活的辅助，让繁琐的事情变得轻松简单，你也可以试试。

## 通用 AI

1. [Rust AI](https://github.com/dongsxyz/rust-ai/blob/master/rust-ai/README.md)

   这是作者自己编写的集成了多家 AI/ML 能力的供应商的 API 的 SDK 套件。`rust-ai` 使用 Rust 语言编写，支持使用配置文件或环境变量进行配置。目前只有 OpenAI 的各项服务以及 Microsoft Azure 的语音相关服务，所以仓库中标记了“不适用于生产环境”。不过，笔者自己已经在多个生产项目中使用了它，总体来说还不错，你可以使用 FFI 工具链将其用于 C/C++/Golang 等其他类型的语言中。

## 图像类

1. [Midjourney](https://www.midjourney.com/)

   业界领先的 AI 作图工具，免费版本有一些限制，不过如果你不经常使用，那么它完全可以胜任。需要注意的是，最方便的用法是通过 Discord 使用 Midjourney。不过现在国内版本已经在测试使用中，可以通过小程序和 QQ 频道来访问（付费）。

2. [Bigjpg](https://bigjpg.com/)

   使用神经网络进行图片放大、降噪、内容补充的在线工具（含 API）。它尤其适合线条感明显的内容（比如漫画、动漫），对光影类图像的降噪能力尚可接受。