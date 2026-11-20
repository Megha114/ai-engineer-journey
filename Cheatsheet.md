# 🚀 AI Engineer Journey — Cheat Sheet

---

## 📘 Day 1 — What is AI?

**The big picture**
- **AI** → any machine that acts smart (even simple rules). *e.g. chess bot*
- **ML** → learns from examples, not rules. *e.g. Netflix suggestions*
- **DL** → ML with many-layered neural networks. *e.g. face unlock*
- **GenAI** → DL that creates new content. *e.g. ChatGPT, Claude*
- **Data Science** → turning data into insights and decisions

> AI ⊃ ML ⊃ DL ⊃ GenAI

**3 types of ML**
- **Supervised** → learns from labelled answers. *e.g. spam filter, cat vs dog*
- **Unsupervised** → finds groups by itself, no labels. *e.g. customer segments*
- **Reinforcement** → learns from rewards and penalties. *e.g. robot vacuum*

> Quick test: labels = supervised · groups = unsupervised · rewards = reinforcement

---

## 🐍 Day 2 — Variables, Data Types & Operators

**Variables**
- A labelled box that holds a value → `age = 30`
- Starts with a letter or `_`, no spaces, case-sensitive
- Use `snake_case` → `total_price`
- Check type → `type(x)`

**Basic types**
- `int` → whole numbers → `42`
- `float` → decimals → `3.14`
- `str` → text → `"hello"`
- `bool` → `True` / `False`
- `None` → no value yet

**Collections**
- `list` → ordered, changeable → `[1, 2, 3]`
- `tuple` → ordered, fixed → `(1, 2, 3)`
- `set` → unique items, no order → `{1, 2, 3}`
- `dict` → key : value pairs → `{"name": "Naman"}`

> Changeable (mutable): list, dict, set · Fixed (immutable): everything else

**Type conversion**
- `int("5")` → `5` · `float("2.5")` → `2.5` · `str(10)` → `"10"`
- `int(3.9)` → `3` (cuts off, doesn't round)
- `input()` always returns text → use `int(input())` for numbers
- Falsy values: `0`, `""`, `[]`, `{}`, `None`

**Operators**
- Maths → `+ - * /` · `//` floor (7//2 = 3) · `%` remainder (7%2 = 1) · `**` power
- Compare → `== != > < >= <=` (gives True/False)
- Logic → `and` both true · `or` either true · `not` flips
- Shortcut → `x += 3` means `x = x + 3`
- Membership → `"a" in "apple"` → True
- Identity → `x is None` (same object, not just same value)

**Watch out**
- `"5" + "3"` → `"53"` (strings join)
- `"5" + 3` → error (can't mix text and numbers)
- `2 + 3 * 4` → `14` (multiply first)