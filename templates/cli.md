<!--
  CLI 命令行工具 README 模板
  使用说明：替换所有【占位符】，删除不需要的章节，删掉本注释块
-->

<div align="center">

# 【工具名】

**【一句话说清这个 CLI 干什么，例如：一个命令把你的项目依赖安全检查一遍】**

[![npm version](https://img.shields.io/npm/v/【包名】)](https://www.npmjs.com/package/【包名】)
[![license](https://img.shields.io/github/license/【用户名】/【仓库名】)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/【用户名】/【仓库名】?style=social)](https://github.com/【用户名】/【仓库名】)

</div>

---

## 📦 安装

```bash
npm install -g 【包名】
```

也可以不安装直接运行：

```bash
npx 【包名】
```

## 🚀 使用

```bash
【命令】 [选项] [参数]
```

### 示例

```bash
# 【示例1说明】
$ 【命令】 【参数】
【输出效果截图或文字】

# 【示例2说明】
$ 【命令】 --【选项】
```

<!-- 强烈建议：用 asciinema 或终端截图放一个真实运行效果 -->

## ⚙️ 选项

| 选项 | 缩写 | 说明 | 默认值 |
| --- | --- | --- | --- |
| `--【选项1】` | `-【x】` | 【说明】 | 【默认值】 |
| `--help` | `-h` | 显示帮助 | - |
| `--version` | `-v` | 显示版本 | - |

## ⚙️ 配置文件

支持在项目根目录放 `【工具名】.config.json`：

```json
{
  "【配置项1】": "【值】",
  "【配置项2】": true
}
```

## 🔧 系统要求

- Node.js >= 【版本】
- 【其他要求】

## 🤝 贡献

欢迎 Issue 和 PR！详见 [贡献指南](CONTRIBUTING.md)。

## 📄 开源协议

[MIT](LICENSE) © 【你的名字】
