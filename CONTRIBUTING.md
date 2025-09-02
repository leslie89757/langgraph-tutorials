# 贡献指南 | Contributing Guide

感谢您对 LangGraph Tutorials 项目的关注和贡献意愿！我们欢迎各种形式的贡献。

## 🤝 如何贡献

### 报告问题 | Reporting Issues

如果您发现了 bug 或有功能建议：

1. 查看现有的 [Issues](../../issues) 确保没有重复
2. 创建新的 Issue 并提供详细信息：
   - 问题描述
   - 重现步骤
   - 期望行为
   - 环境信息（Python 版本、操作系统等）

### 提交代码 | Code Contributions

1. **Fork 项目**
   ```bash
   git clone https://github.com/your-username/langgraph-tutorials.git
   cd langgraph-tutorials
   ```

2. **创建分支**
   ```bash
   git checkout -b feature/your-feature-name
   # 或者
   git checkout -b fix/your-bug-fix
   ```

3. **开发环境设置**
   ```bash
   pip install -r requirements.txt
   ```

4. **进行更改**
   - 保持代码风格一致
   - 添加必要的注释（中英双语）
   - 确保 notebook 可以正常运行

5. **测试您的更改**
   - 运行所有 notebook 确保没有错误
   - 检查输出结果是否正确

6. **提交更改**
   ```bash
   git add .
   git commit -m "feat: add new tutorial for advanced features"
   ```

7. **推送分支**
   ```bash
   git push origin feature/your-feature-name
   ```

8. **创建 Pull Request**

## 📝 代码规范

### Notebook 规范

- **标题格式**: 使用 H1 标题作为主标题，H2 作为章节标题
- **代码注释**: 重要代码添加中文注释说明
- **输出清理**: 提交前清理不必要的输出
- **单元格顺序**: 保持逻辑顺序，便于理解

### 代码风格

```python
# 好的例子
def create_graph_node(name: str, function: Callable) -> dict:
    """
    创建图节点
    
    Args:
        name: 节点名称
        function: 节点执行函数
    
    Returns:
        dict: 节点配置
    """
    return {"name": name, "function": function}
```

### 文档规范

- 使用中英双语标题
- 提供清晰的代码示例
- 包含预期输出
- 添加相关的练习题

## 🎯 贡献类型

### 新教程

- 补充缺失的概念讲解
- 添加实际应用案例
- 创建进阶主题教程

### 改进现有内容

- 修复代码错误
- 改进代码注释
- 优化教程结构
- 更新过时信息

### 翻译和文档

- 改进中英文表达
- 添加术语解释
- 完善使用说明

## 🔍 代码审查

所有 PR 都会经过代码审查：

- 确保代码质量
- 检查教程的准确性
- 验证示例的可运行性
- 评估内容的教育价值

## 💡 贡献建议

### 优先级高的贡献

1. 修复现有 bug
2. 改进代码示例
3. 添加缺失的概念解释
4. 创建实际项目案例

### 贡献想法

- 添加可视化图表
- 创建交互式示例
- 补充性能优化建议
- 添加常见问题解答

## 📮 联系我们

如果您有任何问题或建议：

- 创建 [Issue](../../issues)
- 发起 [Discussion](../../discussions)
- 邮件联系: [leslie89757@126.com]

## 🏆 贡献者

感谢所有贡献者的付出！

<!-- 这里会自动更新贡献者列表 -->

---

再次感谢您的贡献！每一个贡献都让这个项目变得更好。 ❤️