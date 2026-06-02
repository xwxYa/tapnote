# TapNote

> Fork 自 [vorniches/tapnote](https://github.com/vorniches/tapnote)，兼容了 B站视频链接。

TapNote 是一个极简的自托管发布平台，灵感来自 Telegra.ph，专注于即时 Markdown 内容创作。它提供无干扰的写作体验和即时发布能力，非常适合快速记笔记、写博客或分享文档。

![Demo](media/demo.gif)

## 功能特性

- **极简写作体验**
  - 干净、无干扰的 Markdown 编辑器
  - 无需注册账号
  - 一键即时发布
  - 支持完整 Markdown 语法
  - 自托管：完全掌控你的内容

- **内容管理**
  - 每篇文章拥有独立 URL
  - 通过安全 token 编辑已发布内容
  - 正确渲染所有 Markdown 元素
  - 支持图片和代码片段

## 快速开始

1. 克隆仓库：
```bash
git clone https://github.com/xwxYa/tapnote.git
cd tapnote
```

2. 使用 Docker 启动：
```bash
chmod +x setup.sh
./setup.sh
```

3. 访问 TapNote：`http://localhost:9009`

## 示例

```Markdown
# 一级标题
这是一段普通文本。

![图片](https://themepreview.home.blog/wp-content/uploads/2019/07/boat.jpg)

## 二级标题
包含 **粗体**、*斜体* 和 ~~删除线~~ 的文本。

### 三级标题
1. 有序列表项
2. 又一个有序列表项

'```python
# Python 代码片段
def greet(name):
    return f"Hello, {name}!"
```'

#### 四级标题
引用块：
> 这是一段引用！

- 无序列表项
- 无序列表项

#### 表格示例
| 列 A | 列 B |
|------|------|
| 格 1A | 格 1B |
| 格 2A | 格 2B |

# B站视频
https://www.bilibili.com/video/BV1xx411c7mD
```

> 注意：代码块示例中的 `'` 符号在实际使用时请移除。
