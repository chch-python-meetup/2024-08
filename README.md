# Random Notes About Kiwi PyCon 2024  

## Race Condition Coding Comp

Writing code under pressure is hard!


## rye and uv

- rye is awesome and uv recently has gain many rye/poetry like features
- super fast and great UX
- no more need for poetry, pip-tools, twine etc


# Security Checks in Python CI Pipelines

There's a lot of easy stuff we can all do to raise the bar


# GIL removal

- requires that the Python interpreter does lots of additional accounting
- Steering Commitee condition that it there's isn't too much single thread performance lost by removing the GIL


# Immortal objects in Python 3.12

- Avoid reference counting and garbage collection accounting for immutable objects
  * `None`, `True`, `False`, integers from -5 to 255
- Avoid unnecessary CPU cache invalidation
- Less private memory use when forking processes; avoids copy-on-write (COW) for immutable objects

# arrow

- Functionality of datetime + timedelta + zoneinfo + pytz + dateutil etc with one consist API
- https://arrow.readthedocs.io/en/latest/

# Melbourne Runaway Train

Amazing talk!


# ruamel.yaml

- Round trip YAML preserving layout and comments
- https://yaml.readthedocs.io/en/latest/detail/

**All talks coming to YouTube soon**
