# yapi-plugin-import-rap-multi-level-folder

1. `yapi plugin --name yapi-plugin-import-rap-multi-level-folder`

2. 在config.json中新增插件配置
    <pre>
    "plugins": [{
        "name": "import-rap-multi-level-folder",
        "options": {
            "rapOrigin": "http://192.168.1.100:8000" // rap项目地址
        }
    }]
    </pre>

3. 在yapi项目的菜单中会增加“Rap项目导入”菜单，填写rap project id ，执行即可。


### 说明：

项目为支持多级目录的 YAPI 而开发，在原插件项目[https://github.com/wxxcarl/yapi-plugin-import-rap](https://github.com/wxxcarl/yapi-plugin-import-rap)的基础上进行了调整。

支持多级目录的 YAPI 项目地址： [https://github.com/zeyongTsai/yapi](https://github.com/zeyongTsai/yapi)


### 更新日志
0.1.0  兼容RAP1 多级目录导入
0.1.1  增加导入过程的日志记录，以备后续排查错误

