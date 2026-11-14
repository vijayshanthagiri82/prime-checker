# Prime checker execution report

- File: `prime_checker.ipynb`
- Tested GitHub commit: `cebbc2be078dd6e35c4607e1531d4fa2dcb71f10`
- Runner: Codex's local CPython 3.11.9 on Windows
- Method: Read the notebook from the fetched Git commit with `git show cebbc2be078dd6e35c4607e1531d4fa2dcb71f10:prime_checker.ipynb`. Parsed its JSON, ran every code cell in order using Python's `compile` and `exec`, then called the same `is_prime` function on 0, 3, 23 and 25 and checked the returned values. All assertions in the committed notebook passed.

| Input | Actual result | Check |
| ---: | --- | --- |
| 0 | `False` | Pass |
| 3 | `True` | Pass |
| 23 | `True` | Pass |
| 25 | `False` | Pass |

Wizo checks the notebook and this report in GitHub. The execution evidence above comes from the Python runner named here. The report is committed separately from the tested notebook.
