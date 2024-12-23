# Unexpected Null Return in JavaScript Function

This repository demonstrates a common yet subtle bug in JavaScript functions involving null checks. The `foo` function is designed to add two numbers, but it prematurely returns `null` if either input is `null`. This behavior might be unexpected if the intention was to handle `null` values differently (e.g., treat them as 0).

The bug is highlighted in `bug.js`, and a possible solution is provided in `bugSolution.js`.