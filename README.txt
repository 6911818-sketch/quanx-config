# 圈X (Quantumult X) 配置

## 怎么导入到圈X？

### 第一步：复制 [policy] 策略组

打开圈X → ⚙️ → 配置文件 → 编辑

在 `[policy]` 段落（如果没有就自己写一行 `[policy]`），粘贴以下 **7个文件的内容**：

| 文件 | 内容说明 | 去哪复制 |
|------|---------|---------|
| 策略组/01_基础App策略.conf | 海外抖音、AI、苹果等 | GitHub上打开 → Raw按钮 |
| 策略组/02_流媒体策略.conf | Netflix、Disney+等13项 | 同上 |
| 策略组/03_AI服务策略.conf | ChatGPT、Claude等7项 | 同上 |
| 策略组/04_社交媒体策略.conf | Instagram、Discord等9项 | 同上 |
| 策略组/05_游戏平台策略.conf | Steam、PSN等7项 | 同上 |
| 策略组/06_开发技术策略.conf | GitHub、AWS等11项 | 同上 |
| 节点匹配/节点自动匹配.conf | 16个地区节点匹配 | 同上 |

### 第二步：复制 [filter_remote] 分流规则

在 `[filter_remote]` 段落（如果没有就自己写一行 `[filter_remote]`），粘贴 **分流规则/filter_remote.conf** 的全部内容。

> 这个文件已经带 `[filter_remote]` 头了，直接全部复制粘贴即可。

### 第三步：保存

右上角保存，完成！

> 💡 这些分流规则来自 blackmatrix7 的维护仓库，每天自动更新（86400秒），你不需要手动维护。
