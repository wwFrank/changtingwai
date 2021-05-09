# changtingwai
公益相亲
## 服务端接口：
### 1、登录
http://www.changtingwai.love/login.htm
请求方式POST
返回数据
```json
{
  "result":{
    "userId":"122323",
    "session":"ssewe2sa"
  },
  "success":"true"
}
```

### 2、注册
http://www.changtingwai.love/register.htm

请求方式POST
参数
mobile:13769112262
identifyCode:112332
返回数据
```json
{
  "result":{
    "mobile":"13769112262"
  },
  "success":"true"
}
```

### 3、择偶意向
http://www.changtingwai.love/user/intent/update.htm
请求方式POST
```json
{
  "gender":"男",
  "age":"28",
  "height":"167",
  "education":"学历",
  "salary":"30w",
  "prov":"28",
  "marriage":"未婚",
  "house":"有房",
  "car":"有车",
  "children":"无"
}
```
返回数据
```json
{
  "result":{
    "userId":"122323",
    "session":"ssewe2sa"
  },
  "success":"true"
}
```


### 3、找回密码
http://www.changtingwai.love/register.htm
请求方式POST
返回数据
```json
{
  "result":{
    "userId":"122323",
    "session":"ssewe2sa"
  },
  "success":"true"
}
```