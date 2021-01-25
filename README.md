#### 钉钉SDK

`封装了一些常用的钉钉小程序服务端API，获取用户信息`

install

```
npm install dingding
```

usage

```
import dingding from "dingding"

实例化sdk类
const dd = new dingding(appKey, appSecret)
```

##### 获取access_token

```
getAccessToken(): Promise<IToken>
```
##### 获取用户ID

```
getUserId(code: string, token?: string)
```

##### 获取用户信息

```
getUser(code: string, token?: string)
```