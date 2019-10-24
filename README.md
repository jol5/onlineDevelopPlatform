# onlineDevelopPlatform
通用 管理系统 在线开发平台 文档仓库

目的
* 一套 分布式 ，高可扩展的 管理系统 在线开发平台
* 通过该平台，快速配置生成 **高质量的** 各类管理系统;
* 生成的系统拥有良好的流畅度和代码可扩展度;
* 降低用户奔波于无聊又琐碎重复的非业务细节，以便节省更多时间用于开发业务类逻辑；
* 前期可能更加适合用作于 grid 场景较多；
* 界面全配置化， 业务逻辑以 Python为扩展点；


NOTE
* 对于此项目，目前还在计划中，为项目寻找更符合市场的需求以及更好的实现方法;(因为，我现在做的这个不大理想。理念却是不错的)

Q&A
* 对于快速开发一个系统，为什么不直接选择 开源的模板框架呢？
  /r 答：成熟的快速开源框架很多，也很用以上手，不过，由于 IDE 方式编程，本身就牵涉很多 技术上的东西；导致，开发人员，也无法把精力投入到 业务开发中来；
  而且对于一些，经常需要变动调整的系统，如WMS等，如果采用传统开发，会导致 版本频繁变动，做了很多 重复的工作。当然，有docker之后，这也简化了很多。
  而且，在平台上开发，避免了一些开发人员的素质不一致所带来的的 项目进度慢，因为，他们只需要 在 开发平台上，点击几个按钮，就可以配置出他们想要的界面了。  对于数据填充，他们也只需要简单配置就可以了。同时，也提供了，强大的 python作为 后台程序运行钩子，已达到最大的扩展性。
