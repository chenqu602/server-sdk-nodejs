## 用户在线状态

### OnlineStatus.check(user){#check}

检查用户是否在线，调用频率 每秒 100 次

`user` 参数的**属性说明**：

| 参数   	 |	类型		| 必填	| 说明 							|最低版本		|
| :----------|:--------	|:-----	|:------------------------------|:-------- 
|	id		 |	string	|	是 	| 唯一标识，最大长度 30 个字符	| 3.0.0|

##### 请求成功

```json
{
    "code": 200,
    "status": 0
}
```

| 参数   	 |	类型		| 说明	
| :----------|:--------	|:-----	
|	status	 |	number	| 1: 在线  0: 离线
