# redis-stack-wheel

To install the pre-compiled Redis binaries:

```sh
pip install redis-stack-wheel==<redis-version>
```

Supported versions of Redis:

- `7.2.0`

Supported platforms:

- `manylinux2014_x86_64`
- `macosx_11_0_x86_64`

Supported python versions:

- `cp39`

To get the paths of pre-compiled Redis binaries:

```python
import redis_stack_wheel

redis_stack_wheel.REDIS_STACK_SERVER_PATH  # redis-stack-server
```
