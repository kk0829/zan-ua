## Zan UA

### Install

```
npm install zan-ua --save
or
yarn add zan-ua
```

### Usage

### 判断设备是否为iOS系统

```
UA.isIOS(ctx.headers['user-agent']);
```

### 获取 iOS 系统版本号

```
UA.getIOSVersion(ctx.headers['user-agent']);
```

### 判断设备是否为Android系统

```
UA.isAndroid(ctx.headers['user-agent']);
```

### 获取 Android 系统版本号

```
UA.getAndroidVersion(ctx.headers['user-agent']);
```

### 判断是否是微信

```
UA.isWeixin(ctx.headers['user-agent']);
```

### 判断是否是支付宝

```
UA.isAlipay(ctx.headers['user-agent']);
```

### 判断是否是QQ

```
UA.isQQ(ctx.headers['user-agent']);
```

### 判断是否是 iPad 设备

```
UA.isIPad(ctx.headers['user-agent']);
```

### 判断是否是 Safari 浏览器

```
UA.isSafari(ctx.headers['user-agent']);
```

### 获取 Safari 浏览器版本号

```
UA.getSafariVersion(ctx.headers['user-agent']);
```

### 获取 Safari 浏览器完整版本号

```
UA.getFullSafariVersion(ctx.headers['user-agent']);
```

### 判断是否是 Chrome 浏览器

```
UA.isChrome(ctx.headers['user-agent']);
```

### 获取 Chrome 浏览器版本号

```
UA.getChromeVersion(ctx.headers['user-agent']);
```

### 获取 Chrome 浏览器完整版本号

```
UA.getFullChromeVersion(ctx.headers['user-agent']);
```
