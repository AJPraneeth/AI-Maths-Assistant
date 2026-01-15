# UV Enviroment
```bash
uv init
uv sync --frozen   # - Sync without updating the `uv.lock` file
uv sync --locked   # - Assert that the `uv.lock` will remain unchanged
```

# Install Required Libraries

```bash
uv sync --frozen   # - Sync without updating the `uv.lock` file
uv sync --locked   # - Assert that the `uv.lock` will remain unchanged

uv sync --dev # install with dev group packeges , by default install production libraries
```