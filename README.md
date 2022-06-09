<a href='https://postimg.cc/7JqMVspS' target='_blank'><img src='https://i.postimg.cc/7JqMVspS/1654777427878.jpg' border='0' alt='1654777427878'/></a>

# iOSDiffHelper

## 版本: **1.7.0(2022-03-08)**

### 更新日志:

```
修复一些小bug
当前版本已失效，当前版本已失效，当前版本已失效，请不要下载
```

# 介绍

## iOSDiffHelper

> iOS 代码差异化工具，它是针对现有 iOS 项目代码进行差异化的工具，开发者一直在使用和开发中

### 您的 star 是我更新最大的动力

**符号(symbol)**

```
iOS项目中 类、分类、协议、方法、属性、宏、静态变量、静态常量、block、枚举等等的统称
iPA安装包中的二进制(可执行)文件能找到以上所有的符号，所以他们是需要被修改的
```

## 优势

1. 处理后的符号(符号的概念见上面的术语解释)更加接近开发人员的命名习惯，处理后的代码可阅读性高(没有使用随机的单词组合)，这也是过机审的关键
2. 支持 OC 所有的语法
3. 所涉及到的文件名同步修改
4. 支持几乎所有主流的资源类型(修改名字，修改文件 md5)
5. 支持多种白名单
6. 其实 1 才是优势(也是绝对的优势)

## 1. 运行环境:

> MacOS 系统 Python3.10.0 版本 

## 2. 支持混淆的语言

> Objective-C(暂不支持 Swift)

## 3. 关于试用版

> 1. 直接下载即为试用版(试用版会一直提供)
> 2. 试用版会随机混淆 30%左右的代码
> 3. 随机不混淆的 70%部分只会在原符号基础上前后添加字母(这是试用版的限制)
> 4. 试用版增加了限制机制，多次混淆不会增加混淆比例

**示例：**

> +(void)hello; //原方法

**如果在混淆的 30%里:**

> +(void)xxx; //混淆结果未知(不是随机单词)

**如果在不混淆的 70%里:**

> +(void)AXDQ_Hello_QDXA; //大概是这样,只会有前后随机字母的差别,这是试用版的限制

## 4. 关于 VIP 版

```
VIP版本100%混淆
如需VIP版本，请关注微信公众号联系开发者
```

### VIP 版本效果展示

**混淆示例:**

```
类名 AFNetworkActivityIndicatorManager 修改为: OutMeshingInactivityIndicantManager
类名 CocoaSecurityResult 修改为: HotChocolateSuretyResult
属性 networkActivityActionBlock 修改为: meshActionActivenessBlock
属性 verCodeBtn 修改为: forwardCodeSelection
方法 screenShotWithName 修改为: blindJibeSetName
方法 forgetPasswordController 修改为: blockWatchwordController
资源:png titleHelper 修改为: claimHelper
资源:xib LowlyController 修改为: HumbleController
xcassets IQKeyboardManager 修改为: CaptionParentalManager
define StrongObject 修改为: StrongTarget
static tupe 修改为: variance
protocol Optional 修改为: Several
...
```
