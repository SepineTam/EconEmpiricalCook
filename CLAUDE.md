- 当用户要求你帮忙提交git但没有明确指明要提交什么文件的时候，优先去看CookBook里的内容是否发生变更。
- 提交git的时候遵循 `type: content` 的形式进行提交

## 提交类型

| 类型 | 描述 | 示例 |
|------|------|------|
| `add` | 添加新功能 | `add: add pearson correlation calculation` |
| `fix` | 修复bug | `fix: handle null values in correlation` |
| `update` | 更新现有功能 | `update: improve performance of OLS estimator` |
| `refactor` | 重构代码 | `refactor: simplify correlation base class` |
| `docs` | 文档更新 | `docs: update API documentation` |
| `test` | 测试相关 | `test: add unit tests for spearman correlation` |
| `style` | 代码格式 | `style: format code with black` |
| `chore` | 构建/工具 | `chore: update dependencies` |
| `remove` | 删除功能 | `remove: deprecated correlation methods` |
