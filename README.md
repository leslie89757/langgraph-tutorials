# LangGraph Tutorials | LangGraph 完整教程

🚀 **A comprehensive LangGraph tutorial collection with hands-on Jupyter notebooks**

一个全面的 LangGraph 教程项目，通过 Jupyter Notebook 形式展现，涵盖了 LangGraph 的所有核心概念和高级特性。专为开发者学习和实践而设计。

## 🌟 项目特色 | Features

- 📖 **全面覆盖**: 从基础概念到高级应用的完整学习路径
- 💻 **实践导向**: 每个教程都包含可运行的代码示例
- 🔧 **生产就绪**: 包含生产环境部署和最佳实践
- 🌏 **中英双语**: 中文讲解配合英文标准术语
- 🛠️ **即学即用**: 提供完整的环境配置和依赖管理

## 🚀 快速开始 | Quick Start

### 环境要求 | Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab
- Git

### 安装步骤 | Installation

```bash
# Clone the repository
git clone https://github.com/your-username/langgraph-tutorials.git
cd langgraph-tutorials

# Install dependencies
pip install -r requirements.txt

# Start Jupyter
jupyter notebook
```

## 📚 课程目录

### 基础篇

1. **[01_基础概念和节点边.ipynb](./01_基础概念和节点边.ipynb)**
   - LangGraph 简介和核心概念
   - 节点（Nodes）的定义和使用
   - 边（Edges）的创建和连接
   - 基础图结构的构建
   - 简单的执行流程

2. **[02_状态管理和StateGraph.ipynb](./02_状态管理和StateGraph.ipynb)**
   - State 的概念和设计
   - StateGraph 的创建和配置
   - 状态的更新和传递
   - Reducer 函数的使用
   - 状态注解和类型定义

3. **[03_条件边和决策逻辑.ipynb](./03_条件边和决策逻辑.ipynb)**
   - 条件边（Conditional Edges）的概念
   - 决策函数的编写
   - 多分支路由
   - END 节点的使用
   - 循环和递归结构

### 进阶篇

4. **[04_工具调用和Agent.ipynb](./04_工具调用和Agent.ipynb)**
   - 工具（Tools）集成
   - ToolNode 的使用
   - Agent 执行器的构建
   - 工具调用的状态管理
   - 错误处理和重试机制

5. **[05_子图和嵌套图.ipynb](./05_子图和嵌套图.ipynb)**
   - 子图（Subgraphs）的概念
   - 嵌套图结构的设计
   - 子图的编译和执行
   - 状态在子图间的传递
   - 模块化设计模式

6. **[06_持久化和检查点.ipynb](./06_持久化和检查点.ipynb)**
   - 检查点（Checkpointer）机制
   - 内存检查点（MemorySaver）
   - 持久化存储配置
   - 状态恢复和回溯
   - 线程管理和配置

### 高级篇

7. **[07_并行执行和Map-Reduce.ipynb](./07_并行执行和Map-Reduce.ipynb)**
   - 并行节点执行
   - Map-Reduce 模式
   - Send API 的使用
   - 动态并行任务
   - 结果聚合策略

8. **[08_Human-in-the-Loop.ipynb](./08_Human-in-the-Loop.ipynb)**
   - 人机交互节点
   - 中断（Interrupt）机制
   - 人工审批流程
   - 输入验证和确认
   - 交互式对话系统

9. **[09_流式输出和实时交互.ipynb](./09_流式输出和实时交互.ipynb)**
   - 流式输出（Streaming）
   - 事件流处理
   - 实时状态更新
   - Token 级别的流式响应
   - 异步执行模式

10. **[10_高级应用案例.ipynb](./10_高级应用案例.ipynb)**
    - RAG（检索增强生成）系统
    - 多智能体协作系统
    - 复杂工作流编排
    - 自适应对话系统
    - 生产环境最佳实践

## 🚀 快速开始

### 环境要求

- Python 3.8+
- Jupyter Notebook 或 JupyterLab

### 安装依赖

```bash
pip install -r requirements.txt
```

### 运行教程

1. 启动 Jupyter Notebook：
```bash
jupyter notebook
```

2. 在浏览器中打开相应的 `.ipynb` 文件

3. 按照教程顺序学习，每个 notebook 都包含：
   - 详细的概念解释
   - 可运行的代码示例
   - 实践练习
   - 进阶技巧

## 📖 学习建议

1. **循序渐进**：建议按照编号顺序学习，每个教程都建立在前面的基础之上
2. **动手实践**：每个示例代码都可以直接运行，建议边学边练
3. **修改实验**：尝试修改代码参数，观察不同的运行结果
4. **查看可视化**：运行代码后会生成图结构的可视化，帮助理解执行流程

## 🔧 常见问题

如果遇到导入错误，请确保已安装所有依赖：
```bash
pip install --upgrade langgraph langchain langchain-openai python-dotenv
```

如果需要使用 OpenAI 模型，请设置环境变量：
```bash
export OPENAI_API_KEY="your-api-key"
```

## 📚 其他资源 | Additional Resources

- [LangGraph 官方文档](https://langchain-ai.github.io/langgraph/)
- [LangChain 文档](https://python.langchain.com/)
- [示例代码库](https://github.com/langchain-ai/langgraph/tree/main/examples)

## 🤝 贡献 | Contributing

欢迎贡献！如果您发现问题或有改进建议：

1. Fork 这个仓库
2. 创建您的功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

## ⭐ 如果这个项目对您有帮助，请给个星标！

## 📄 许可证 | License

本项目采用 MIT 许可证。查看 [LICENSE](LICENSE) 文件了解更多信息。

## 👤 作者 | Author

- **Your Name** - *Initial work* - [YourGitHub](https://github.com/your-username)

## 🙏 致谢 | Acknowledgments

- 感谢 LangChain 团队开发的优秀 LangGraph 框架
- 感谢所有为开源社区做出贡献的开发者

---

**如果您觉得这个教程有用，请不要忘记给个 ⭐！**

*Made with ❤️ by the community*

每个 notebook 都包含了详细的中文注释和解释，帮助你深入理解 LangGraph 的工作原理和最佳实践。

祝学习愉快！ 🎉