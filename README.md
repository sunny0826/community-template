# Community Template

开源软件社区健康自查清单及相关文件模板

### 基础

- [ ] 官网（或先使用 README）：描述该项目是什么，如何获取，如何贡献和贡献方式，如何反馈
- [ ] 技术文档：包含功能说明，API 文档，快速开始，FAQ
- [ ] 交流渠道：最好使用不需要安装专有软件的可搜索的、公开的讨论渠道，推荐 GitHub Discussion 或 Issue
- [ ] 行为守则：创建 `CODE_OF_CONDUCT.md`，可以使用[行为准则联盟](https://www.contributor-covenant.org/zh-cn/version/2/1/code_of_conduct/)
- [ ] 贡献指南：创建 `CONTRIBUTING.md`，[案例参考](https://github.com/github/docs/blob/main/CONTRIBUTING.md)
- [ ] 许可证声明（LICENSE）
- [ ] 知识产权声明（NOTICE）
- [ ] 新人引导机制：例如设置 `good first issues` 作为新人可以上手解决的贡献，[相关文档](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/encouraging-helpful-contributions-to-your-project-with-labels)，[案例参考](https://github.com/apache/rocketmq/issues/6205)
- [ ] 错误报告流程：建立 Bug Repoart Issue Template，[案例参考](https://github.com/apache/echarts/blob/master/.github/ISSUE_TEMPLATE/bug_report.yml)
- [ ] 功能请求流程：建立 Feature Request IssueTemplate，[案例参考](https://github.com/apache/echarts/blob/master/.github/ISSUE_TEMPLATE/feature_request.yml)
- [ ] 变更请求流程：建立 Pull Request Template，[案例参考](https://github.com/apache/echarts/blob/master/.github/pull_request_template.md)
- [ ] 测试框架：有线上和线下的测试环境
- [ ] 版本发布：每一次发版都要有唯一的版本标识符，并发布相应的 Release Notes

### 进阶

- [ ] 漏洞报告流程：声明 `SECURITY.md` 并开启 GitHub Security Policy，[相关文档](https://docs.github.com/en/code-security/getting-started/adding-a-security-policy-to-your-repository)，[案例参考](https://github.com/apache/dubbo/security/policy)
- [ ] 有社区角色（contributer，reviewer）和晋升机制，开源办后续将协助使用 GitHub Actions 构建流程
- [ ] 项目路线图，阐述未来一年内预期发版的功能，案例参考 [tidb/raodmap.md](https://github.com/pingcap/tidb/blob/master/roadmap.md)
- [ ] 贡献者致谢，创建 `Contributors.md` 公开记录所有进行过代码贡献的开发者 id，[案例参考](https://github.com/all-contributors/all-contributors#contributors-)
- [ ] 如果是需要构建使用的开源软件，提供可工作的构建系统，并用徽章显示状态 build｜pass

### 文件模板：

- [LICENSE](./LICENSE) `Apache 2.0`
- `NOTICE`
- [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md)
- `CONTRIBUTING.md`
- [Contributors.md](https://github.com/all-contributors/all-contributors#contributors-)
- `CHANGELOG.md`
- [SECUTITY.md](./SECURITY.md)
- [.github/ISSUE_TEMPLATE](https://github.com/devspace/awesome-github-templates#bomb-templates-for-issues)
- [.github/PULL_REQUEST_TEMPLATE](https://github.com/devspace/awesome-github-templates#rocket-templates-for-pull-requests)
- `GitHub Discussion`
