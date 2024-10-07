# redis-stack-wheel

To install the pre-compiled Redis binaries:

```sh
pip install redis-stack-wheel==<redis-version>
```

Supported versions of Redis Stack:

- `7.2.0-v9`

Supported platforms:

- `manylinux_2_31_x86_64`
- `macosx_14_0_x86_64`
- `macosx_14_0_arm64`

Supported python versions:

- `cp39`
- `cp311` (except mac x64)

To get the paths of pre-compiled Redis binaries:

```python
import redis_stack_wheel

redis_stack_wheel.REDIS_STACK_SERVER_PATH  # redis-stack-server
redis_stack_wheel.REDIS_CLI_PATH  # redis-cli
```
