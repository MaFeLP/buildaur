# Developing
## Using PyCharm
### Warnings:
 - In [buildaur](./buildaur):
   - `def update(willinst=[]):`
      - You can safely ignore this message.
   - All `Package.*` is not references errors:
      - You can also ignore this message, because the variables are created with the `exec()` function.
   - in `main()`: `Local variable 'secarg' might be referenced before assignment.`
      - This can also be ignored, because if secarg initialisation would fail, the program would exit.