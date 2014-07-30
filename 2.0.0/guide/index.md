## 综述

探测国产浏览器

* 版本： 1.1
* 基于： kissy 1.3
* 作者： kissy


## 组件使用


### 1.加载 ua-extra 模块

```javascript
    KISSY.use('kg/ua-extra/2.0.0//', function (S, extraUA) {
    	S.log(extraUA.maxthon);    
    })
```
**提醒**：use()的回调，第一个参数是KISSY，第二个参数才是组件。


### Attributes
- **maxthon** 
  + {Number} maxthon 版本号
- **se360** 
  + {Number} se360 版本号
- **tt** 
  + {Number} tt 版本号
- **theword** 
  + {Number} theword 版本号    
- **sougou** 
  + {Number} sougou 版本号   
- **shell** 
  + {String} "sougou" or "tt" or "theword" or "se360" or "maxthon"