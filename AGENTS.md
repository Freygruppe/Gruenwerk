# AGENTS.md

## 项目概况

- 项目名称：Grünwerk Dietenbach
- 仓库：`https://github.com/freygruppe/Gruenwerk.git`
- 线上域名：`https://gruenwerk-dietenbach.de`
- 技术栈：静态 HTML、CSS、JavaScript
- 当前没有 Vite、React、npm 构建流程或自动化测试
- GitHub Pages 通过仓库根目录文件直接发布
- `CNAME` 必须保留为 `gruenwerk-dietenbach.de`

## 页面与资源

- `index.html`：首页
- `projekt.html`：项目介绍
- `vision.html`：愿景页面
- `impressum.html`：Impressum
- `datenschutz.html`：Datenschutz
- `images/`：网站图片资源

## 修改规则

- 默认使用中文沟通。
- 页面文案保持现有德语品牌语气，建筑、规划和 Baugruppe 内容使用专业表达。
- 修改前先检查相关页面中的内联 CSS、JavaScript、导航和响应式规则。
- 优先复用现有 HTML 结构、CSS 类、颜色、字体、间距和交互方式。
- 非必要不引入框架、构建工具、第三方依赖或全局重构。
- 修改导航或页脚时检查所有 HTML 页面，避免页面间链接不一致。
- 修改图片时保留合理尺寸和格式，并检查文件名中的空格及德语字符引用。
- 不删除或改写 `CNAME`，除非用户明确要求变更域名。
- 不提交密钥、Token、个人凭证、`.env` 或其他敏感信息。
- 不删除用户未要求删除的页面、内容或资源。

## 验证要求

- 修改后检查 `git diff`，确认没有无关格式化或文件变更。
- 使用本地静态 HTTP 服务预览，不依赖直接打开 `file://`。
- 检查桌面端和移动端布局。
- 检查所有页面导航、内部链接、图片、邮件链接和法律页面。
- 当前没有构建命令；不要声称执行过 `npm run build`。
- 涉及 UI 的修改应尽量提供浏览器截图或明确描述视觉变化。

## Git 工作流

- 默认分支：`main`
- 小型、低风险修改在验证后可直接提交并 push 到 `main`，但任务中需得到用户明确授权。
- 较大、结构性或高风险修改使用 `codex/*` 分支，并通过 Pull Request 合并。
- 提交信息使用简洁前缀，例如 `feat:`、`fix:`、`style:`、`docs:`。
- push 后检查 GitHub Pages 或线上域名，确认部署结果。

## 完成任务后的说明

需向用户说明：

1. 修改了哪些文件
2. 做了哪些改动及原因
3. 使用了哪些验证方式
4. 是否已 commit、push 和部署
5. 尚存的风险或潜在影响
