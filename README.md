# 理发日历生成器

#### 简介

理发日历生成器是一个Python项目，用于根据农历日期生成从指定起始年份到结束年份的理发吉日日历，并输出为ICS文件格式，方便用户在iOS设备上订阅。该项目基于传统的理发吉日理念，通过农历日期判断每一天理发的吉凶，并生成相应的日历事件。

#### 安装指南

1. 克隆仓库到本地
```bash
git clone https://github.com/your-username/haircut-calendar-generator.git
cd haircut-calendar-generator
```

2. 安装依赖
确保你的系统已安装Python 3。安装所需的Python包：
```bash
pip install -r requirements.txt
```

#### 使用说明

1. 运行脚本并输入起止年份：
```bash
python generate_haircut_calendar.py
```
按照提示输入起始年份和结束年份。

2. 生成的ICS文件将保存在项目目录下，文件名格式为 `haircut_calendar_<起始年份>_to_<结束年份>.ics`。

3. 为了方便地在iOS设备上订阅，请使用以下链接：

```
https://raw.githubusercontent.com/Prometheus-INTJ/Haircut-Calendar/main/haircut_calendar.ics
```

在iOS设备上订阅日历的步骤：
- 打开“设置”>“日历”>“账户”>“添加账户”>“其他”>“添加已订阅的日历”
- 输入上述URL地址并完成订阅。

#### 贡献指南

我们欢迎所有形式的贡献，无论是新功能的提议、bug修复，还是文档和示例的改进。如果您愿意为项目作出贡献，请遵循以下步骤：

1. Fork项目到您的GitHub账户。
2. 创建一个新的分支进行修改。
3. 提交您的更改后，创建一个新的Pull Request。

#### 许可协议

本项目采用Apache License 2.0许可协议。有关更多信息，请查看LICENSE文件。
