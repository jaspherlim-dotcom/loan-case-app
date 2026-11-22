# 贷款案件管理 Loan Case Workflow

马来西亚贷款公司内部用的案件流程工具：客户登记、开案、按贷款类型自动生成文件清单、打勾收文件、案件状态、AI 文件识别。中英文切换。

## 网页版须知

- **数据只存在每个人自己的浏览器 (localStorage)**。换手机、换浏览器或清除浏览器资料，数据就看不到；同事之间不会同步。
- **AI 文件识别**要在页面里输入自己的 Anthropic API Key 才能用。Key 只存在那台设备的浏览器，不会上传到这个 repo。照片直接从设备送去 Anthropic 分析。
- 这个 repo 只有程序，**不要把任何客户资料、IC、文件照片放进来** (PDPA)。
- 文件清单是按马来西亚一般市场做法整理的，请按合作银行 / 贷款方的要求调整。

## 部署

单一文件 `index.html`，用 GitHub Pages 发布 (Settings → Pages → Deploy from branch → `main` / root)。
