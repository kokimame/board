# board
This repository will provide a bunch of board games with simple graphics.

You can play these games through Python interactive shell.

This repository is inspired by the gym module of OpenAI, especially its structure.


The module is assumed to be used as follows:
```python

>>> import board
>>> game, me, cpu = board.set("Reversi")
>>> cpu.set_agent("agent_file.py")
>>> game.start(me, "first")
>>> me.put(3,4)
>>> me.undo()
...
```
