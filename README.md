# 📖 分支

当前正在 signin 分支

点击 [此处](https://github.com/postyizhan/share-plugins-config) 回到主页

# 📷 照骗

<details>
  <summary>点击展开</summary>

![](https://img.fastmirror.net/s/2024/08/20/66c4779828bc6.png)

![](https://img.fastmirror.net/s/2024/08/20/66c477986a1e4.png)

![](https://img.fastmirror.net/s/2024/08/20/66c47798c0871.png)

![](https://img.fastmirror.net/s/2024/08/20/66c4779938d63.png)

</details>

# 📦 安装

你需要安装 [Checkitem](https://yizhan.wiki/NitWikit/Java/process/plugin/Front-Plugin/PlaceHolderAPI/CheckItem#%E5%AE%89%E8%A3%85%E6%AD%A4%E6%89%A9%E5%B1%95) 扩展并 [启用give和remove](https://yizhan.wiki/NitWikit/Java/process/plugin/Front-Plugin/PlaceHolderAPI/CheckItem#%E5%90%AF%E7%94%A8give%E5%92%8Cremove)

你需要安装 [Vulpecula](https://github.com/Lanscarlos/Vulpecula) 插件，因为我用到了它提供的 if* 语句

覆盖文件后重启服务端

# ⚙️ 配置

## 补签卡

默认会使用名为 `&a&l补签卡` 的物品作为补签卡，你可以找到下方的变量

```
%checkitem_amount_nameequals:&a&l补签卡%
%checkitem_remove_nameequals:&a&l补签卡,amt:1%
%checkitem_amount_nameequals:&a&l补签卡%
```

修改他们来修改签到使用的补签卡

## 签到奖励

找到 `tell "&a&l! &7签到成功！"` 在上下文中可配置签到奖励
