---
name: go-coding-standards
description: 提供 Go 开发的编码规范和最佳实践指南，当进行 Go 语言编程时调用，以确保代码质量和可维护性。
---

# 何时使用
- 当进行 Go 语言编程时
- 当需要确保代码符合 Go 最佳实践时
- 当需要统一团队编码风格时
- 当编写新的 Go 模块或重构现有代码时

# 何时不使用
- 当编写非 Go 语言代码时
- 当项目已有特定编码规范且明确要求遵循时

# 核心规范摘要
1. 遵循标准项目结构（App/internal/pkg/clib 分层）
2. 遵循 `go fmt` 格式化规则（缩进、空格、换行）
3. 使用有意义的命名（驼峰式、包名小写）
4. 错误处理优先（错误作为返回值、及时检查）
5. 使用 `defer` 进行资源清理
6. 遵循简洁的注释规范（包注释、函数注释）
7. 合理使用 goroutine 和 channel
8. 避免 goroutine 泄漏
9. 使用 `go vet` 和 `staticcheck` 进行静态分析

👉 完整规范见：[references/go_coding_standards.md](references/go_coding_standards.md)
