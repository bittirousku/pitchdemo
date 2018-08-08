# GITPITCH presentation sample

Here it is.

---

## Python example

```python
class TestLibrary(object):
	"""A very simple library to test variable values."""

	def __init__(self):
		self.status = "PASS"

	def execute_integer_assertion(self, result, expected):
		try:
			assert result == expected
			print(result, "is", expected)
		except AssertionError:
			print(result, "is not", expected)
			self.status = "FAIL"
```
