# 构建自己的模块

构建自己的模块非常简单，首先需要确保模块文件以 .py 结尾，然后就可以从其它模块中引入这个模块了，文件名既是这个模块名。

例如：

```python
#!/usr/bin/env python
# file: mymodule.py

def hello():
	print "hello"

version = 0.1
```

在另一个模块中引入 mymodule，如下：

```python
#!/usr/bin/env python

import mymodule

hello()
print mymodule.version
```
