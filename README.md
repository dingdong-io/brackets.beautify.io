beautify.io
# 功能性修改 (在beautify基础上)
修改方法:在settings.json修改字段.(虽然brackets-beautify提到{"js":{},"css":{}}的写法,但测试未过,还不知道html和css的beautify要怎么改.一个需求是html的行内处理得不好)

目前产生修改的:
"comma_first":true  //前置逗号风格,不单允许前置逗号,在使用beautify时,会默认将后置逗号改前置.
"brace_style": "end-expand"  //else换行--方便brackets折叠
"preserve_newlines": false  //保持换行 -true时,前置逗号行每beautify一次,会新增一换行,故改为false
"max_preserve_newlines": 2  //最大空行:2


# 其它
* 2016年2月26日
brackets插件管理器搜出来的beautify (!!而不是brackets-beautify) ,[原项目地址]https://github.com/brackets-beautify/brackets-beautify,  
注:插件下载的与github下的略不同,拷贝自 插件管理器下载的beautify 1.2.0

删除\thirdparty\js-beautify\ 下的.git,否则无法直接提交
