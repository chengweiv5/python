# 模块的\_\_name\_\_

每个模块都有一个名字，即：\_\_name\_\_。

一个模块被引入或者自己主动执行的时候，模块的主块会被执行，如果想要区分这两种情况，那么只需要判断 \_\_name\_\_ 是否等于 \_\_main\_\_ 即可。

例如：

```python

if __name__ == "__main__":
	print "run as main"
	do something
else:
	print "imported by others"
```
