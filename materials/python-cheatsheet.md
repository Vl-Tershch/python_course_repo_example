# Шпаргалка Python

## Коллекции

```python
numbers = [1, 2, 3]
unique = {1, 2, 3}
point = (10, 20)
user = {"name": "Ada", "age": 36}
```

## Comprehensions

```python
squares = [x * x for x in range(10) if x % 2 == 0]
index = {name: i for i, name in enumerate(["A", "B"])}
```

## Контекстный менеджер

```python
with open("data.txt", encoding="utf-8") as f:
    text = f.read()
```
