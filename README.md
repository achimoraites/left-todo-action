# left-todo-action

A GitHub action that detects and counts TODO comments


```yaml
name: Count TODO

on:
   workflow_dispatch: 

jobs:
   count_todos:
      runs-on: ubuntu-latest
      steps:
        - name: Check out the source code
          uses: actions/checkout@v3
        - name: Count TODOs
          uses: achimoraites/left-todo-action@0.1.0
```
