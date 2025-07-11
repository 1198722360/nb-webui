## 免责声明

> 本项目基于 [open-webui/open-webui at v0.6.5](https://github.com/open-webui/open-webui/tree/v0.6.5) 进行商业化二次开发，该版本遵循 **BSD-3-Clause** 许可证。本项目与Open WebUI官方团队没有任何关联。
>
> 本项目尊重并遵守 [Open WebUI License](https://docs.openwebui.com/license)。用户的相关违规风险请自行承担，用户的违规行为与作者无关。

---

# Open WebUI

官方文档：[🏡 Home | Open WebUI](https://docs.openwebui.com/)

github：[open-webui/open-webui: User-friendly AI Interface (Supports Ollama, OpenAI API, ...)](https://github.com/open-webui/open-webui)

# 部署教程

```bash
git clone https://github.com/1198722360/nb-webui.git
cd nb-webui
./deploy.sh
# 然后访问 http://ip:8188 即可
```

# 更新教程
```bash
./deploy.sh
```

# 已实现功能

* [X] /v1/chat/completions接口计费
* [X] 按量计费
* [X] 按次计费
* [X] 适配one/new api的分组倍率/模型倍率/补全倍率/模型价格
* [X] 对接易支付
* [X] 对接支付宝当面付
* [X] 充值倍率设置
* [X] 模型使用日志
* [X] 用户初始额度
* [X] 模型价格显示
* [X] 部分文字的多语言支持

# 待实现功能

* [ ] 注册时邮箱验证
* [ ] 公告管理
* [ ] 自定义logo
* [ ] 用户分级(VIP1、 VIP2...)
* [ ] Ollama模型计费
* [ ] 更直观的模型价目表
* [ ] 邀请返利
* [ ] 更便捷的模型配置功能(如统一配置各模型调用时是否携带"usage"字段等)
* [ ] ......



### **本项目供免费使用，并将持续更新。另外，如有好的需求或建议，欢迎进群提出，作者将选择性采纳**

![](https://raw.githubusercontent.com/1198722360/picture/main/20250530182801706.png)

# 演示站+公益站

https://free.much-ai.com

# 功能演示

### 模型价格显示

![](https://raw.githubusercontent.com/1198722360/picture/main/20250530181045512.png)

![](https://raw.githubusercontent.com/1198722360/picture/main/20250530191949085.png)

### 余额显示

![](https://raw.githubusercontent.com/1198722360/picture/main/20250530181318202.png)

### 余额管理

![](https://raw.githubusercontent.com/1198722360/picture/main/20250531023845333.png)

### 充值面板

![](https://raw.githubusercontent.com/1198722360/picture/main/20250530181456724.png)

### 使用日志

![](https://raw.githubusercontent.com/1198722360/picture/main/20250530181637968.png)

![](https://raw.githubusercontent.com/1198722360/picture/main/20250530181614803.png)

### 管理员后台

#### 价格配置

![](https://raw.githubusercontent.com/1198722360/picture/main/20250530181806805.png)

#### 支付/充值配置

![](https://raw.githubusercontent.com/1198722360/picture/main/20250530191853800.png)
