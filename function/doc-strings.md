# 文档字符串

函数可以定义自己的文档字符串，并且可以用 pydoc 等工具提取函数的文档字符串，甚至使用函数的 `__doc__` 属性。

例如：

```python
def max(a, b):
	"""This is a function.

	Will return the max number between a and b."""

	if a > b:
		return a
	else
		return b
```

文档字符串第一行为描述，第二行为空行，第三行为详细描述，例如：参数，返回值等。

文档字符串也可以在类中定义。
