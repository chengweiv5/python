# break 语句

```python
#!/usr/bin/env python

while True:
	s = raw_input("your name(type 'quit' to quit):")
	if s == "quit":
		break
	print "your name is", s
else:
	print "while finished."
```
