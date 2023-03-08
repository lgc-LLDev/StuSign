<!-- markdownlint-disable MD031 MD033 MD036 -->

# StuSign

简洁的签到插件

## 介绍

### Features

_自用插件，功能虽然比不上论坛里的其它插件，但就是图简洁，满足自己需求_

- 入服签到，并在**聊天栏**提醒，不挡公告
- 对接 LLMoney
- 每次签到随机给钱，可配置

## 安装方法

将 `StuSign.lls.js` 扔进 BDS 插件目录即可

## 配置文件

插件配置文件位于`BDS根目录/plugins/StuSign/config.json`（插件加载成功后自动生成）  
请根据下面 json 中的注释修改配置文件

```jsonc
{
  // 签到给予最少金钱数
  "minMoney": 500,

  // 签到给予最多金钱数
  "maxMoney": 2000
}
```

## 更新日志

- 0.1.1
  - 添加每天 0:00 自动给所有服务器内玩家签到
