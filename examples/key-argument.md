#!/usr/bin/env python

def foo(a, b, c, d=1, e=2, f=3):
	print a, b, c, d, e, f

foo(1,2,3)
foo(a=2, c=3, b=5)
foo(c=1)
