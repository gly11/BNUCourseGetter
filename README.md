# 小鸦抢课
一个使用简单, 开源安全的北师大自动抢课/蹲课程序, 支持公选课(已完成)/专业课(开发中)

支持多平台, 后端基于 `Go`, 前端基于 `TypeScript`, 使用 `Wails`、`React`、`Playwright`、`AntD` 等工具开发; 欢迎参与本项目!

二进制文件仅在 `Windows` 下测试过, 其他平台如果有问题请提交 `Issue` 或 `Pull Request`

![](./README.png)

## 使用方法
[点击下载](https://github.com/LeafYeeXYZ/BNUCourseGetter/releases)适用于你的设备的最新版本程序, 直接运行即可 (杀毒软件可能会误报为病毒, 如不放心可自行从源码编译)

请提前**确认各项信息填写正确, 确认无课程时间冲突, 并最后手动二次确认选课结果**

| 选项 | 说明 |
| :---: | :---: |
| 模式 | 抢课模式下, 会在系统未开启时自动刷新; 如果可选人数为零, 则会退出<br>蹲课模式下, 会在系统未开启时退出; 如果可选人数为零, 则会自动刷新 |
| 课程类型 | 请确认相关课程在分类里存在 |
| 刷新速度 | 不要设太快 |
| 学号 | 你的学号, **所有信息都保存在你的设备本地** |
| 密码 | 你的密码, **所有信息都保存在你的设备本地** |
| 课程号 | 你要抢的课程号 |
| 班级号 | 你要抢的班级号 |

## 免责声明
本项目仅供学习交流使用, 开源免费. 请勿用于非法用途, 请严格遵守开源协议, 请勿滥用, 请勿使用此项目牟利, 请自行承担使用此项目的风险
