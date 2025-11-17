# ADM转换工具

一个简单易用的在线工具，用于将RTB Bid Response中的ADM内容转换为可预览的HTML文件。

## 功能特性

- 🔄 **JSON解析**: 自动解析Bid Response JSON格式
- 🎨 **实时预览**: 内置iframe预览转换后的广告效果
- 📥 **文件下载**: 一键下载转换后的HTML文件
- 📋 **复制功能**: 快速复制HTML代码到剪贴板
- 🌐 **响应式设计**: 支持桌面和移动设备
- ⚡ **纯前端**: 无需服务器，数据不会上传

## 使用方法

1. 将完整的Bid Response JSON粘贴到输入框
2. 点击"转换ADM"按钮
3. 查看转换结果和预览效果
4. 下载HTML文件或复制代码

## 支持的格式

工具会自动查找JSON中的`seatbid[].bid[].adm`字段，并解码其中的HTML内容。

### 示例输入格式

```json
{
    "id": "46cb0e34-7388-41cc-99cb-d0af69fbe960",
    "seatbid": [
        {
            "bid": [
                {
                    "adm": "<!DOCTYPE html>..."
                }
            ]
        }
    ]
}
```

## 在线访问

访问 GitHub Pages: [https://yourusername.github.io/adm-converter](https://yourusername.github.io/adm-converter)

## 本地运行

1. 克隆仓库
```bash
git clone https://github.com/yourusername/adm-converter.git
```

2. 直接在浏览器中打开 `index.html`

## 技术栈

- 纯HTML/CSS/JavaScript
- 无外部依赖
- 响应式设计

## 贡献

欢迎提交Issue和Pull Request来改进这个工具。

## 许可证

MIT License
