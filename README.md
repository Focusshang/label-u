## 特性

- 📝本项目包含@lebel-u/lb-annotation、@label-u/lb-components、@label-u/lb-utils及@label-u/lb-web等4个工程。

- 📝采用rollup esbuild插件及vite编译，让开发者上高速，开发效率更高

- 📝采用lerna进行多工程管理。

- 📝合理的代码分层：

  - 📝lb-utils提供国际化能力。

  - 📝lb-annotation作为工具层，主要实现标注能力的封装，此外提供AnnotationEngine用于调用标注能力。

  - 📝lb-components实现标注能力集成，作为直接暴露在外的标注组件，使用者通过对AnnotationOperation的配置即可实现标注界面。（目前主要是针对图片标注，视频，音频，文本和点云也在开发当中）

  - 📝lb-web提供一个开箱即用的标注服务，基于lb-components暴露组件实现，支持对工具的yaml 和 可视化配置，并提供模板供用户参考和标注界面预览。

## 安装

```bash
# npm
npm install lerna -g
npm install
npm run bootstrap
npm run build
npm run start

```


## 使用

详细文档尽请期待。

## 致谢

我们在使用此款智能标注工具时，参考了以来了labelbee 项目，在此对labelbee的作者表示感谢。