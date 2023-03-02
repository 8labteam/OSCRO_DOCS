# OSCRO_DOCS

octa services computing resources operator

在这个项目中，会持续展示OSCRO平台对外使用和说明的文档及外部使用的Q&A+


通过这里的介绍，可以让大家对代码所见即所得的状态，有持续的了解，
还有具体的示例如何进行的操作，
最后，还有持续发布系统升级，变化的情况，以便更多的技术爱好者追踪和加入


# Release Notes

| OSCRO Version                                   | Version Explain     | OS Version Supported                          |
| --                                                          | --                                                               | --                                                |
| <b>[alpha-v1030](release_notes/alpha-v1030.md)</b> (Oct 30, 2022)  | 内部功能确认测试完成(https://bitbucket.org/8labteam) |  |
| <b>[v1.0](release_notes/v1.0.md)</b> (Dec 23, 2022)  | 功能构架组件测试通过，具备对外发布使用能力(https://bitbucket.org/8labteam) |  |

# VALUE

通过技术社区标准的构建，推动生产力发展，计算资源精准投放，人员成本开销降低，运行更加可靠智能，最终实现IT新基建的变革

# HOW TO USE

详细使用说明(https://8labteam.github.io/OSCRO_DOCS/)

## 本分支用于更新版本前的测试开发
> 参考地址： https://www.mkdocs.org/user-guide/
> mkdocs-materila 主题 https://squidfunk.github.io/mkdocs-material/getting-started/
- MkDocs 是一个快速、简单且完全华丽的静态站点生成器，适用于构建项目文档。文档源文件以 Markdown 编写，并使用单个 YAML 配置文件进行配置 
- 项目持续构建使用github action, 发布分支gh-pages
- 开发环境启动`mkdocs serve -a 0.0.0.0:8000`