# if 语句

```
#!/usr/bin/env python

age = 23
guess = int(raw_input("Please guess my age:"))

if guess == age:
	print "Wow, fantastic!"
	print "But no price. :-)"
elif guess > age:
	print "Your answer is a little larger."
else:
	print "Your answer is a litte smaller."
```
