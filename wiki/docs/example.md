# Markdown 与图片使用示例

## 文字格式

普通段落文字，**加粗文字**，*斜体文字*，~~删除线~~，`行内代码`。

> 这是一段引用文字，适合记录重要提示或摘录。

## 列表

**无序列表：**
- 知识点 A
- 知识点 B
  - 子知识点 B-1
  - 子知识点 B-2

**有序列表：**
1. 第一步
2. 第二步
3. 第三步

## 表格

| 名称 | 类型 | 说明 |
|------|------|------|
| 示例A | 概念 | 这是一个概念说明 |
| 示例B | 工具 | 这是一个工具说明 |

## 代码块

```python
# Python 示例
def hello(name):
    print(f"Hello, {name}!")

hello("世界")
```

```bash
# Shell 示例
echo "Hello World"
ls -la
```

## 图片使用

将图片文件放到 `docs/images/` 目录下，然后用以下方式引用：

```markdown
![图片描述](docs/images/你的图片名.png)
```

示例（图片点击可放大）：

![示例占位图](https://via.placeholder.com/600x300/4a90e2/ffffff?text=在这里放你的图片)

## 链接

- [跳转到主页](/)
- [外部链接示例](https://www.example.com)
