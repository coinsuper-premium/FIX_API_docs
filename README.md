# FIX API

简介

```
Exchange API 是交易所面向外部开发者提供的开发接口。
```

------

更新历史

| 版本        | 时间       | 说明   | 作者     |
| --------- | -------- | ---- | ------ |
| v1.0.0(α) | 20190114 | 创建文档 | liyong |

------

## [一、全局规则](https://github.com/coinsuper-premium/FIX_API_docs/wiki#%E4%B8%80%E5%85%A8%E5%B1%80%E8%A7%84%E5%88%99)

#### [接口访问地址信息](https://github.com/coinsuper-premium/FIX_API_docs/wiki#%E6%8E%A5%E5%8F%A3%E8%AE%BF%E9%97%AE%E5%9C%B0%E5%9D%80%E4%BF%A1%E6%81%AF)

#### [接口规则](https://github.com/coinsuper-premium/FIX_API_docs/wiki#%E6%8E%A5%E5%8F%A3%E8%A7%84%E5%88%99)

##### [全局数据格式定义](https://github.com/coinsuper-premium/FIX_API_docs/wiki#%E5%85%A8%E5%B1%80%E6%95%B0%E6%8D%AE%E6%A0%BC%E5%BC%8F%E5%AE%9A%E4%B9%89)

##### [登录签名描述](https://github.com/coinsuper-premium/FIX_API_docs/wiki#%E7%99%BB%E5%BD%95%E7%AD%BE%E5%90%8D%E6%8F%8F%E8%BF%B0) 

#####  [签名生成方法示例](https://github.com/coinsuper-premium/FIX_API_docs/wiki#%E7%AD%BE%E5%90%8D%E7%94%9F%E6%88%90%E6%96%B9%E6%B3%95%E7%A4%BA%E4%BE%8B) 

####  [全局通用异常信息](https://github.com/coinsuper-premium/FIX_API_docs/wiki#%E5%85%A8%E5%B1%80%E9%80%9A%E7%94%A8%E5%BC%82%E5%B8%B8%E4%BF%A1%E6%81%AF) 

------

## [二、详细接口定义](https://github.com/coinsuper-premium/FIX_API_docs/wiki#%E4%BA%8C%E8%AF%A6%E7%BB%86%E6%8E%A5%E5%8F%A3%E5%AE%9A%E4%B9%89)

### [API 接口定义](https://github.com/coinsuper-premium/FIX_API_docs/wiki#api-%E6%8E%A5%E5%8F%A3%E5%AE%9A%E4%B9%89)

#### [1. 会话类](https://github.com/coinsuper-premium/FIX_API_docs/wiki#1-%E4%BC%9A%E8%AF%9D%E7%B1%BB)

##### [1.1 登录](https://github.com/coinsuper-premium/FIX_API_docs/wiki#11-%E7%99%BB%E5%BD%95)

##### [1.2 注销](https://github.com/coinsuper-premium/FIX_API_docs/wiki#12-%E6%B3%A8%E9%94%80)

##### [1.3 心跳](https://github.com/coinsuper-premium/FIX_API_docs/wiki#13-%E5%BF%83%E8%B7%B3)

#### [2. 交易类](https://github.com/coinsuper-premium/FIX_API_docs/wiki#2-%E4%BA%A4%E6%98%93%E7%B1%BB)

##### [2.1 下单委托](https://github.com/coinsuper-premium/FIX_API_docs/wiki#21-%E4%B8%8B%E5%8D%95%E5%A7%94%E6%89%98)

##### [2.2 撤单委托](https://github.com/coinsuper-premium/FIX_API_docs/wiki#22-%E6%92%A4%E5%8D%95%E5%A7%94%E6%89%98)

#### [3. 信息查询类](https://github.com/coinsuper-premium/FIX_API_docs/wiki#3-%E4%BF%A1%E6%81%AF%E6%9F%A5%E8%AF%A2%E7%B1%BB)

##### [3.1 查询未完成订单](https://github.com/coinsuper-premium/FIX_API_docs/wiki#31-%E6%9F%A5%E8%AF%A2%E6%9C%AA%E5%AE%8C%E6%88%90%E8%AE%A2%E5%8D%95)
