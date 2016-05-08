

Node.js: chcitys
--------
`chcitys` 查询最新的中国境内行政区划信息，返回各级省市县区的名称，编码和归属关系。


数据来源
----
数据来源于[中华人民共和国民政部网站](http://www.mca.gov.cn/article/sj/tjbz/a/2016/201603/201604281751.html)



Installation
------------

    npm install --save chcitys



Usage
-----


```js
var cityree = require('chcitys').getCityTree 
var city1 = citytree('安徽省');
// ...
var city1 = citytree('合肥市');
// ...
```



Methods
-------
- [getCityTree](#getCityTree)

**NOTE:** You can still use the native Node.js methods. They are copied over to `fs-extra`.


### getCityTree()

**getCityTree(cityname)**

返回指定城市或者省的信息，以及其下属城市树，树的结构如下:
```json
  {
       id : '110000', name : '北京市',
       nodes : [
       		{ id : '110101' , name : '东城区'},
			...
       ] 
  }
```
  * params:
    @`cityname` ：城市或者省名称，例如 ： '北京市' '安徽省'
  * result:
    返回城市树，不存在则返回undefined



License
-------

Licensed under MIT

Copyright (c) 2011-2015 [JP Richardson](https://github.com/jprichardson)