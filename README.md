# bupt-ncov-report-action

使用 GitHub Actions 自动填报北邮 2019-nCoV 疫情信息。

这个 Actions 会自动在北京时间的每天 8:00 AM 进行填报。

## 使用方法

首先，点击上方绿色的 **Use this template**，使用这个模板创建你自己的 Repository；

然后，在仓库 Setting 中的 Secrets 中设置以下信息：

- `BUPT_USERNAME`: 你用来登录的学号；
- `BUPT_PASSWORD`: 你用来登录的密码。