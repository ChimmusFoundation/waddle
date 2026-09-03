# Waddle

A simple python framework for a dashboard.

Add text in `output.text`:
```python
output.text = (f"{utime}".center(get_width())) 
```

Commands can be added in `commands`:
```python
if cmds[0] == "hi":
  print("hi")
```