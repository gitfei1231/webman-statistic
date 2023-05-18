
# webman-statistic 应用监控插件

## 简介

> 用于监控上报 [webman](https://github.com/walkor/webman) 应用调用、请求量、调用耗时、状态码异常、sql日志、redis日志等。配合 [TransferStatistics](https://github.com/gitfei1231/transfer-statistics) v2+ 使用查看上报数据


## 安装

` composer require gitfei1231/webman-statistic `


## 配置

修改 ` config/plugin/gitfei1231/statistic/app.php ` 文件，设置相关参数


## 注意

` illuminate/database ` 、` illuminate/redis ` 日志需要安装 ` composer require illuminate/events `