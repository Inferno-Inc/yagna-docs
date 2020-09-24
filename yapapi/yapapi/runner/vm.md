Module yapapi.runner.vm
=======================

Functions
---------

    
#### repo

```python3
def repo(
    *,
    image_hash: str,
    min_mem_gib: float = 0.5,
    min_storage_gib: float = 2.0
) -> yapapi.runner.Package
```
Builds reference to application package.

- *image_hash*: finds package by its contents hash.
- *min_mem_gib*: minimal memory required to execute application code.
- *min_storage_gib* minimal disk storage to execute tasks.