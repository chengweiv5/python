# while 语句

```python
#!/usr/bin/env python

age = 23
guess = 0

while age != guess:
	if guess > age:
		print "enter a small number"
	else:
		print "enter a large number"
	guess = int(raw_input("Please guess my age: "))
else:
	print "You got it, wow!"
```
