# Changelog

更新日志

## 0.7.0 - 2019-05-11

### Added

* 支持配置http和socks代理，使用 `--proxy=<proxy_rules>` 命令行选项：  
`./Fuck学习强国 --proxy="http://127.0.0.1:1080"`  
（[代理规则的格式](https://electronjs.org/docs/api/session#sessetproxyconfig-callback)）

### Fixed

* 解决无法自动浏览的问题

## 0.6.4 - 2019-04-25

> （这是一个好数字）

### Fixed

* 解决在 Windows 系统中无法打开的问题 ( CI 服务里的 Wine 版本太低，唉)

* 解决每天第二次打开才能登录的问题

## 0.6.3 - 2019-04-12

### Fixed

* 解决无法自动浏览的问题

## 0.6.2 - 2019-04-04

### Changed

* 改变顶部菜单栏中每项积分的[显示格式](https://github.com/fuck-xuexiqiangguo/Fuck-XueXiQiangGuo/issues/240#issuecomment-478416227)

### Fixed

* 解决在最小化窗口后不能继续得分的问题

## 0.6.1 - 2019-04-01 （这是真的）

### Added

* 在顶部菜单栏中显示每项积分

## 0.6.0 - 2019-03-30

### Added

* 在窗口最上方（菜单栏中）和命令行界面中显示目前刷了多少分

* 在窗口最上方（菜单栏中）显示当前版本号

## 0.5.1 - 2019-03-29

### Changed

* 适配最新积分规则

## 0.5.0 - 2019-03-28

### Added

* 支持使用用户名密码自动登录，使用 `--username=<phone_number>` 和 `--passwd=<password>` 命令行选项：  
`./Fuck学习强国 --username=13900000000 --passwd="xxxxxx"`  
（如果是外国手机号，请以 +1-xxxxxxxxxx 的格式输入）

### Fixed

* 解决卡在音频节目上的问题

## 0.4.3 - 2019-03-13

### Fixed

* 解决无法退出登录的问题

## 0.4.2 - 2019-03-13

### Added

* 支持使用自定义 User Agent 启动程序，使用 `--ua=<user_agent>` 命令行选项：  
`./Fuck学习强国 --ua="Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:65.0) Gecko/20100101 Firefox/65.0"`

### Changed

* 在程序多开时自动使用多用户模式

## 0.4.1 - 2019-03-13

### Added

* 增加命令行界面（CLI）, 使用 `./Fuck学习强国 --help` 查看帮助

* 增加使用指定用户ID（作用是区分用户，保存cookies，可随便填写）的多用户模式，使用 `--user=<user_name>` 命令行选项启用： `./Fuck学习强国 --user=abc`

## 0.4.0 - 2019-03-13

### Added

* 增加多开功能（多用户模式），使用 `--multi-user` 命令行选项启用 （不保存cookies，再次打开需要重新登录）

### Fixed

* 解决登录有效期只有6个小时的问题（cookie的有效期只有6个小时）

## 0.3.0 - 2019-03-12

### Added

* 支持使用用户名和密码登录

### Fixed

* 登录界面二维码居中显示
