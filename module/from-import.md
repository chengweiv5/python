# from..import 语句

import 语句会引入整个模块，例如：

```python
import sys

print sys.path
```

但是，如果你想省略每次都输入 sys., 而直接输入 path，那么可以使用 `from..import` 语句，例如：

```python
from sys import path
from sys import *
```
