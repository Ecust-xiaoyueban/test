## 全局公共参数
#### 全局Header参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### 全局Query参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### 全局Body参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### 全局认证方式
```text
noauth
```
#### 全局预执行脚本
```javascript
暂无预执行脚本
```
#### 全局后执行脚本
```javascript
暂无后执行脚本
```
## /Iot
```text
暂无描述
```
#### Header参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Query参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Body参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /Iot/guard
```text
电源控制器
```
#### Header参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Query参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### Body参数
参数名 | 示例值 | 参数描述
--- | --- | ---
暂无参数
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
## /Iot/guard/添加用户权限
```text
暂无描述
```
#### 接口状态
> 开发中

#### 接口URL
> http://192.168.0.133:5000/regcard

#### 请求方式
> POST

#### Content-Type
> form-data

#### 请求Body参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
username | 20280212 | String | 是 | 用户工号/学号
cname | 小月半 | String | 是 | 用户名字
user | 154145 | String | 是 | 用户卡号
start | 2023-08-30 00:00:00 | Date | 是 | 权限开始时间
end | 2023-08-30 23:59:59 | Date | 是 | 权限结束时间
devindex | 1 | Integer | 是 | 设备分路
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
#### 成功响应示例
```javascript
{
  "code": "200", 
  "msg": "add add policy: True", 
  "result": true
}
```
#### 错误响应示例
```javascript
{
  "code": "400", 
  "msg": "Missing parameters: username", 
  "result": false
}
```
## /Iot/guard/获取日志
```text
暂无描述
```
#### 接口状态
> 开发中

#### 接口URL
> http://192.168.0.133:5000/logs

#### 请求方式
> GET

#### Content-Type
> form-data

#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
#### 成功响应示例
```javascript
{
  "code": "200", 
  "data": [
    {
      "cardnumber": "1479893360", 
      "datetime": "2023-07-17 14:02:20"
    }, 
    {
      "cardnumber": "261632", 
      "datetime": "2023-08-09 12:24:46"
    }, 
    {
      "cardnumber": "261632", 
      "datetime": "2023-08-09 12:29:00"
    }, 
    {
      "cardnumber": "114514", 
      "cmd": "open", 
      "cname": "\u9ad8\u5b87\u58f0", 
      "datetime": "2023-08-29 12:21:22", 
      "devindex": {}, 
      "username": "20230077"
    }, 
    {
      "cardnumber": "114514", 
      "cmd": "open", 
      "cname": "\u9ad8\u5b87\u58f0", 
      "datetime": "2023-08-29 12:21:22", 
      "devindex": {}, 
      "username": "20230077"
    }, 
    {
      "cardnumber": "114514", 
      "cmd": "open", 
      "cname": "\u9ad8\u5b87\u58f0", 
      "datetime": "2023-08-29 12:21:34", 
      "devindex": {}, 
      "username": "20230077"
    }, 
    {
      "cardnumber": "114514", 
      "cmd": "open", 
      "cname": "\u9ad8\u5b87\u58f0", 
      "datetime": "2023-08-29 12:21:34", 
      "devindex": {}, 
      "username": "20230077"
    }, 
    {
      "cardnumber": "114514", 
      "cmd": "open", 
      "cname": "\u9ad8\u5b87\u58f0", 
      "datetime": "2023-08-29 13:31:25", 
      "devindex": {}, 
      "username": "20230077"
    }, 
    {
      "cardnumber": "114514", 
      "cmd": "open", 
      "cname": "\u9ad8\u5b87\u58f0", 
      "datetime": "2023-08-29 13:31:25", 
      "devindex": {}, 
      "username": "20230077"
    }, 
    {
      "cardnumber": "114514", 
      "cmd": "open", 
      "cname": "\u9ad8\u5b87\u58f0", 
      "datetime": "2023-08-29 13:33:05", 
      "devindex": {}, 
      "username": "20230077"
    }, 
    {
      "cardnumber": "114514", 
      "cmd": "open", 
      "cname": "\u9ad8\u5b87\u58f0", 
      "datetime": "2023-08-29 13:33:05", 
      "devindex": {}, 
      "username": "20230077"
    }, 
    {
      "cardnumber": "1577914", 
      "cmd": "open", 
      "cname": "\u6d4b\u8bd5\u6570\u636e1", 
      "datetime": "2023-08-29 13:34:44", 
      "devindex": {}, 
      "username": null
    }, 
    {
      "cardnumber": "1577914", 
      "cmd": "open", 
      "cname": "\u6d4b\u8bd5\u6570\u636e1", 
      "datetime": "2023-08-29 13:34:44", 
      "devindex": {}, 
      "username": null
    }, 
    {
      "cardnumber": "1577914", 
      "cmd": "open", 
      "cname": "\u6d4b\u8bd5\u6570\u636e1", 
      "datetime": "2023-08-29 13:34:44", 
      "devindex": {}, 
      "username": null
    }, 
    {
      "cardnumber": "55555", 
      "cmd": "open", 
      "cname": "\u94f6\u5ddd", 
      "datetime": "2023-08-29 14:24:59", 
      "devindex": {}, 
      "username": "20230088"
    }, 
    {
      "cardnumber": "55555", 
      "cmd": "close", 
      "cname": "\u94f6\u5ddd", 
      "datetime": "2023-08-29 14:26:01", 
      "devindex": 1, 
      "username": "20230088"
    }, 
    {
      "cardnumber": "55555", 
      "cmd": "open", 
      "cname": "\u94f6\u5ddd", 
      "datetime": "2023-08-29 14:26:40", 
      "devindex": {}, 
      "username": "20230088"
    }, 
    {
      "cardnumber": "55555", 
      "cmd": "close", 
      "cname": "\u94f6\u5ddd", 
      "datetime": "2023-08-29 14:28:20", 
      "devindex": 1, 
      "username": "20230088"
    }, 
    {
      "cardnumber": "11111", 
      "cmd": "open", 
      "cname": "\u5f20\u4e09", 
      "datetime": "2023-08-29 14:47:11", 
      "devindex": {}, 
      "username": "20230088"
    }, 
    {
      "cardnumber": "11111", 
      "cmd": "close", 
      "cname": "\u5f20\u4e09", 
      "datetime": "2023-08-29 14:47:26", 
      "devindex": 1, 
      "username": "20230088"
    }, 
    {
      "cardnumber": "132114", 
      "datetime": "2023-08-30 10:52:13"
    }, 
    {
      "cardnumber": "11111", 
      "datetime": "2023-08-30 10:52:47"
    }, 
    {
      "cardnumber": "1577914", 
      "cmd": "open", 
      "cname": "\u6d4b\u8bd5\u6570\u636e1", 
      "datetime": "2023-08-30 10:53:28", 
      "devindex": {}, 
      "username": null
    }, 
    {
      "cardnumber": "1577914", 
      "cmd": "open", 
      "cname": "\u6d4b\u8bd5\u6570\u636e1", 
      "datetime": "2023-08-30 10:53:28", 
      "devindex": {}, 
      "username": null
    }, 
    {
      "cardnumber": "1577914", 
      "cmd": "open", 
      "cname": "\u6d4b\u8bd5\u6570\u636e1", 
      "datetime": "2023-08-30 10:53:28", 
      "devindex": {}, 
      "username": null
    }, 
    {
      "cardnumber": "1577914", 
      "cmd": "close", 
      "cname": "\u6d4b\u8bd5\u6570\u636e1", 
      "datetime": "2023-08-30 10:53:39", 
      "devindex": "1", 
      "username": null
    }, 
    {
      "cardnumber": "132144", 
      "cmd": "open", 
      "cname": "\u90d1\u91d1\u745e", 
      "datetime": "2023-08-30 12:35:40", 
      "devindex": {}, 
      "username": "20230076"
    }, 
    {
      "cardnumber": "132144", 
      "cmd": "open", 
      "cname": "\u90d1\u91d1\u745e", 
      "datetime": "2023-08-30 12:35:40", 
      "devindex": {}, 
      "username": "20230076"
    }, 
    {
      "cardnumber": "132144", 
      "cmd": "open", 
      "cname": "\u90d1\u91d1\u745e", 
      "datetime": "2023-08-30 12:35:40", 
      "devindex": {}, 
      "username": "20230076"
    }, 
    {
      "cardnumber": "132144", 
      "cmd": "close", 
      "cname": "\u90d1\u91d1\u745e", 
      "datetime": "2023-08-30 12:35:51", 
      "devindex": "1", 
      "username": "20230076"
    }, 
    {
      "cardnumber": "976631", 
      "cmd": "open", 
      "cname": "\u738b\u4e00", 
      "datetime": "2023-08-30 12:38:32", 
      "devindex": {}, 
      "username": "20250001"
    }, 
    {
      "cardnumber": "976631", 
      "cmd": "close", 
      "cname": "\u738b\u4e00", 
      "datetime": "2023-08-30 12:38:40", 
      "devindex": 1, 
      "username": "20250001"
    }, 
    {
      "cardnumber": "132144", 
      "cmd": "open", 
      "cname": "\u90d1\u91d1\u745e", 
      "datetime": "2023-08-30 12:40:12", 
      "devindex": {}, 
      "username": "20230076"
    }, 
    {
      "cardnumber": "132144", 
      "cmd": "open", 
      "cname": "\u90d1\u91d1\u745e", 
      "datetime": "2023-08-30 12:40:12", 
      "devindex": {}, 
      "username": "20230076"
    }, 
    {
      "cardnumber": "132144", 
      "cmd": "open", 
      "cname": "\u90d1\u91d1\u745e", 
      "datetime": "2023-08-30 12:40:12", 
      "devindex": {}, 
      "username": "20230076"
    }, 
    {
      "cardnumber": "132144", 
      "cmd": "close", 
      "cname": "\u90d1\u91d1\u745e", 
      "datetime": "2023-08-30 12:40:31", 
      "devindex": "1", 
      "username": "20230076"
    }
  ], 
  "msg": "\u65e5\u5fd7\u83b7\u53d6\u6210\u529f", 
  "result": true
}
```
## /Iot/guard/打开电源
```text
暂无描述
```
#### 接口状态
> 开发中

#### 接口URL
> http://192.168.0.133:5000/poweron?devindex=1

#### 请求方式
> GET

#### Content-Type
> none

#### 请求Query参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
devindex | 1 | Integer | 否 | 设备分路
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
#### 成功响应示例
```javascript
{
  "code": "200", 
  "msg": "\u5206\u8def1\u7535\u6e90\u5f00\u542f", 
  "result": true
}
```
## /Iot/guard/关闭电源
```text
暂无描述
```
#### 接口状态
> 开发中

#### 接口URL
> http://192.168.0.133:5000/poweroff?devindex=1

#### 请求方式
> GET

#### Content-Type
> none

#### 请求Query参数
参数名 | 示例值 | 参数类型 | 是否必填 | 参数描述
--- | --- | --- | --- | ---
devindex | 1 | Integer | 否 | 设备分路
#### 认证方式
```text
noauth
```
#### 预执行脚本
```javascript
暂无预执行脚本
```
#### 后执行脚本
```javascript
暂无后执行脚本
```
#### 成功响应示例
```javascript
{
  "code": "200", 
  "msg": "\u5206\u8def1\u7535\u6e90\u5173\u95ed", 
  "result": true
}
```