```py
Hello = type("Hello", (), {"World": lambda message: print(message)})
Hello.World("print")
```
