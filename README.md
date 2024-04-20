# scrapy_study

## scrapy 项目结构

```
tutorial/
    scrapy.cfg                  # 部署配置文件
    tutorial/                     # 项目的python模块，你将从这里导入你的代码
        __init__.py              
        items.py                # 项目items定义文件
        middlewares.py    # 项目中间件文件
        pipelines.py          # 项目管道文件
        settings.py            # 项目设置文件
        spiders/                 # 用于之后放置你的spiders
            __init__.py
```