# WePy遇到的问题

## 编译后报错

报错原因:`找不到app.json或者读取app.json文件出错`

解决方法:编译后将`project.config.json`拷贝到dist目录下,并删除里面的`"miniprogramRoot": "./dist"`,重新编译即可。
